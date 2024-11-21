| Adaptations to eLCI as USLCI Library                                                                                  | Script/ Solutions                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| --------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Internal ID errors|from java.util import Date<br>dao = ProcessDao(db)<br>for d in dao.getDescriptors():<br>  p = dao.getForId(d.id)<br>  p.lastInternalId = 0<br>  for e in p.exchanges:<br>    e.internalId = p.lastInternalId + 1<br>    p.lastInternalId += 1<br>  v = Version(p.version)<br>  v.incUpdate()<br>  p.version = v.getValue()<br>  p.lastChange = Date().getTime()<br>  dao.update(p)                                                                        |
| Several exchanges contain 0 amounts, need to delete these to transform into library matrices | [see below](#script-to-remove-zeroes) |
| Third Party Flows folder and subfolders not NAICS aligned                                                             | Created a CUTOFF flows folder under technosphere flows, moved flows, and deleted existing folders                                                                                                                                                                                                             |
| Waste flows folder not NAICS aligned                                                                                  | Moved waste flows from elementary flows to cutoff waste flows folder. Created a cutoff waste flows folder                                                                                                                                                                                                     |
| Output emissions folder, "heat" flow, and "water, reclaimed" flow in the resources folder are not NAICS aligned       | Created a non-fedefl folder under emission and resource, moved flows, deleted emission output folder                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| "water, reclaimed" emission flow is not FEDEFL compatible                                                             | Moved flow to the emission --> non-fedefl                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| Waste, solid flow in 5622 is a cutoff waste flow                                                                      | Moved to the cutoff waste flow folder and deleted folder 56 and 5622 (nothing else in these folders)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| TRACI and NETL aligned TRACI are not compatible with the FLCAC guidelines (preference is to have IA methods separate) | Deleted IA methods                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| Download eLCI flow into USLCI and mapped to it. Then added eLCI library.                                              | Flow downloaded: 3bca3bc6-2443-3184-8976-72dc98d258f6 - Electricity, AC, 120 V<br>Source flows: Electricity, at Grid, US, 2010 - Electricity, at grid                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
## Script to remove zeroes
```# -*- coding: utf-8 -*-
from java.util import ArrayList
from org.openlca.core.database import ProcessDao
from org.openlca.core.model import FlowType

# Access the ProcessDao
pDao = ProcessDao(db)

for descriptor in pDao.getDescriptors():
    try:
        # Fetch the process for the current descriptor
        process = pDao.getForId(descriptor.id)
        if process is None:
            log.warn("Could not load process for descriptor: {}".format(descriptor))
            continue

        toRemove = ArrayList()

        # Iterate over exchanges in the process
        for exchange in process.exchanges:
            # Check if exchange has a zero amount
            if exchange.amount == 0:
                flow = exchange.flow
                if flow is None:
                    log.warn("Exchange in process {} has no associated flow".format(process.name.encode('utf-8')))
                    continue

                # Determine flow type and log removal
                flow_type = flow.flowType
                direction = "input" if exchange.isInput else "output"
                flow_name = flow.name if flow.name else "Unnamed Flow"

                if exchange.id == process.quantitativeReference.id:
                    log.info("Invalid: quantitative reference has zero amount in process {} ({})".format(
                        process.name.encode('utf-8'), process.refId))
                    continue

                # Log and mark for removal
                log.info("Removing zero amount {} {} ({}) from process {} ({})".format(
                    flow_type, direction, flow_name.encode('utf-8'), process.name.encode('utf-8'), process.refId))
                toRemove.add(exchange)

        # Log and remove marked exchanges
        log.info("Number of exchanges to remove from process {}: {}".format(process.name.encode('utf-8'), toRemove.size()))

        if not toRemove.isEmpty():
            process.exchanges.removeAll(toRemove)
            pDao.update(process)

    except Exception as e:
        log.error("An error occurred while processing descriptor {}: {}".format(descriptor, str(e).encode('utf-8')))
```