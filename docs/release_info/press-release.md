# :earth_americas: USLCI Press Releases :newspaper:

[Return to the USLCI Content Wiki](/wiki)

<br>

This page provides quarterly updates and news regarding the [USLCI Database](https://www.lcacommons.gov/lca-collaboration/National_Renewable_Energy_Laboratory/USLCI_Public/datasets) publishing updates. The USLCI is updated quarterly based on the [U.S. Federal Government Fiscal Calendar](https://www.senate.gov/reference/glossary_term/fiscal_year.htm). These updates are compiled by the [USLCI Data Curator](mailto:uslci@erg.com) on the behalf of the [National Renewable Energy Laboratory (NREL)](https://www.nrel.gov/). For more information and publications regarding the creation and evolution of the USLCI, please see NREL's [U.S. Life Cycle Inventory Database](https://www.nrel.gov/lci/about.html) project pages. To see announcements regarding the Federal LCA Commons (FLCAC) as a whole, please see the landing page: [lcacommons.gov](https://www.lcacommons.gov/).


:tv: :sound: <br>

For video guidance on accessing, navigating, versioning, using, and submitting data to the USLCI Database (and more), please see the [USLCI Quick Help Video Series](https://www.youtube.com/playlist?list=PLmIn8Hncs7bFUOyXZNGXwG4LtdoTfLz6Q) on NREL's Learning YouTube channel.
<br> 


:tv: :sound:


***
#### USLCI Conversion to the Federal Elementary FEDEFL-Adapted CED & LCIA Methods

Since Spring quarter 2020, the USLCI has converted to using the [Federal Elementary Flow List (FEDEFL)](https://cfpub.epa.gov/si/si_public_record_report.cfm?dirEntryId=347251&Lab=NRMRL&subject=Land%20and%20Waste%20Management%20Research&showCriteria=0&searchAll=Waste%20Management%20or%20Nitrogen%20Management%20or%20Contaminated%20Sites%20or%20Ground%20Water%20or%20Materials%20Management%20or%20Sediment%20Toxicity&sortBy=revisionDate&startIndex=51&displayIt=Yes), which is available on GitHub [here](https://github.com/USEPA/Federal-LCA-Commons-Elementary-Flow-List) per the emerging Commons standards & conventions. The FEDEFL will become a part of the core database structure across Commons repositories and provide greater standardization and interoperability for Federal LCA data. Life cycle inventory (LCI) and life cycle impact assessment (LCIA) methods are also being converted to be compatible with the FEDEFL being adapted by FLCAC. **For the convenience of end users of USLCI Database (and other FEDEFL-adapted FLCAC data), these [FEDEFL-Adapted Methods](https://www.lcacommons.gov/lcia-methods-without-flows) are provided for running LCI and LCIA calculations in openLCA.**
***
## 2024 Winter Quarter (Scheduled December 31, Occurred December 31)
This USLCI Database release is Version 1 of the USLCI_2024_Q4 or winter 2024 release. This USLCI database version is available on the [NREL USLCI repo](https://www.lcacommons.gov/lca-collaboration/) of the [Federal LCA Commons Collaboration Server](https://www.lcacommons.gov) (FLCAC) as well as via the [USLCI Release Downloads](/docs/release_info/release-downloads.md) page of this GitHub site.

### Overview of 2024\_Q4\_v1 Changes:

- Added cobalt ore, crude cobalt hydroxide, and cobalt sulfate datasets from Argonne National Laboratory.
- Reviewed and revised datasets with multiple product flow outputs and no allocation set. When appropriate, converted product flows into waste flows, applied allocation factors based on the associated publication, or assigned all allocation to the quantitative reference product flow.
- Replaced multiple non-Federal Elementary Flow List (FEDEFL) with FEDEFL flows. Non-FEDEFL flows that remained were moved to “non-FEDEFL” elementary flow folders.
- Corrected multiple errors and added additional information to flows and processes. Please see the change log for more details.

As a reminder, in Q2 2024 the USLCI curation team introduced the FLCAC Electricity Baseline repository as a library to the USLCI database to enhance the quality of electricity processes for background data use. The Data Curators have also developed a [standardized, repository-level version format](https://flcac-admin.github.io/FLCAC-docs/versioning) for FLCAC repositories. Starting in June 2024, previous versions of USLCI are now stored on the FLCAC under the ‘Version’ dropdown. As of December 2024, a change log between versions is now available on the FLCAC.

- The version of the Electricity Baseline that is currently a library in USLCI has been adapted from the [public version of the repository](https://www.lcacommons.gov/lca-collaboration/Federal_LCA_Commons/US_electricity_baseline/datasets). Documentation on this adaptation is provided [here](https://github.com/FLCAC-admin/uslci-content/blob/dev/docs/supporting_docs/eLCI%20Library%20Change%20Log.md). The database from which the library has been generated from can be downloaded [here](https://github.com/FLCAC-admin/uslci-content/blob/dev/downloads/elci_6_2024%20for%20uslci_2024_final_database_format.zip).

### Change Log, Versioning, &amp; Data Submission

Please see the complete [Change Log](/docs/release\_info/change-log.md) for details of all winter 2024 updates. Additionally, please note that current and deleted datasets are always also available in an archive managed by NREL (wherein current and previous USLCI database versions are available) at the [USLCI Downloads Page](/docs/release\_info/release-downloads.md). Finally, please see the [How to Publish in the USLCI](https://flcac-admin.github.io/FLCAC-docs/datasubmissionhandbook) section in the USLCI Data Submission Guidelines and/or contact the contact the [USLCI Data Curator](mailto:uslci@erg.com) if you have any data/metadata publishing goals for the next March 31, 2025 winter release date. We look forward to hearing from you soon.

## 2024 Fall Quarter (Scheduled September 30, Occurred October 9)
This USLCI Database release is Version 1 of the USLCI_2024_Q3 or fall 2024 release. This USLCI database version is available on the [NREL USLCI repo](https://www.lcacommons.gov/lca-collaboration/) of the [Federal LCA Commons Collaboration Server](https://www.lcacommons.gov) as well as via the [USLCI Release Downloads](/docs/release_info/release-downloads.md) page of this GitHub site.

### Overview of 2024\_Q3\_v1 Changes:

-	Fixed errors in processes by removing erroneously assigned provider in the inputs and quantitative reference flows
-	Deleted additional product waste flows and mapped them to waste flows
-	Corrected biodiesel allocation error

As a reminder, in Q2 2024 the USLCI curation team introduced the FLCAC Electricity Baseline repository as a library to the USLCI database to enhance the quality of electricity processes for background data use. 

- The version of the Electricity Baseline that is currently a library in USLCI has been adapted from the [public version of the repository](https://www.lcacommons.gov/lca-collaboration/Federal_LCA_Commons/US_electricity_baseline/datasets). Documentation on this adaptation is provided [here](https://github.com/FLCAC-admin/uslci-content/blob/dev/docs/supporting_docs/eLCI%20Library%20Change%20Log.md). The database from which the library has been generated from can be downloaded [here](https://github.com/FLCAC-admin/uslci-content/blob/dev/downloads/elci_6_2024%20for%20uslci_2024_final_database_format.zip).

### Change Log, Versioning, &amp; Data Submission

Please see the complete [Change Log](/docs/release\_info/change-log.md) for details of all fall 2024 updates. Additionally, please note that current and deleted datasets are always also available in an archive managed by NREL (wherein current and previous USLCI database versions are available) at the [USLCI Downloads Page](/docs/release\_info/release-downloads.md). Finally, please see the [How to Publish in the USLCI](https://flcac-admin.github.io/FLCAC-docs/datasubmissionhandbook) section in the USLCI Data Submission Guidelines and/or contact the contact the [USLCI Data Curator](mailto:uslci@erg.com) if you have any data/metadata publishing goals for the next December 31, 2024 winter release date. We look forward to hearing from you soon.


## 2024 Summer Quarter (Scheduled June 30, Occurred June 28)
This USLCI Database release is Version 1 of the USLCI_2024_Q2 or summer 2024 release. This USLCI database version is available on the [NREL USLCI repo](https://www.lcacommons.gov/lca-collaboration/) of the [Federal LCA Commons Collaboration Server](https://www.lcacommons.gov) as well as via the [USLCI Release Downloads](/docs/release_info/release-downloads.md) page of this GitHub site.

### Overview of 2024\_Q2\_v1 Changes:

-	Added the Federal LCA Commons U.S. Electricity Baseline repository into USLCI as a library. Documentation on using Libraries is provided [here](https://flcac-admin.github.io/FLCAC-docs/flcac-openlca-library-user-guidance) and will continue to be updated.
    - Mapped flows between the library and main database to connect Electricity Baseline flows and providers to existing USLCI exchanges.
    - Replaced the “Electricity, at grid” USLCI flow with the Electricity Baseline “Electricity, AC, 120 V” flow.
    - The version of the Electricity Baseline that is currently a library in USLCI has been adapted from the [public version of the repository](https://www.lcacommons.gov/lca-collaboration/Federal_LCA_Commons/US_electricity_baseline/datasets). Documentation on this adaptation is provided [here](https://github.com/FLCAC-admin/uslci-content/blob/dev/docs/supporting_docs/eLCI%20Library%20Change%20Log.md). The database from which the library has been generated from can be downloaded [here](https://github.com/FLCAC-admin/uslci-content/blob/dev/downloads/elci_6_2024%20for%20uslci_2024_final_database_format.zip).
-	Transitioned datasets using the opposite direction waste end-of-life methodology to the material flow logic allocation to enhance the consistency of end-of-life modeling.
  -	Consolidated disposal flows, standardized waste and recycled material flow names, and reorganized flows into correct folders
-	Updated existing non-road transport datasets (train, ocean freighters, barges, and aircraft) with newer emissions data from GREET, 2023
-	Removed extraneous flow properties, sources, and actors to simplify the database.

### Change Log, Versioning, &amp; Data Submission

Please see the complete [Change Log](/docs/release\_info/change-log.md) for details of all summer 2024 updates. Additionally, please note that current and deleted datasets are always also available in an archive managed by NREL (wherein current and previous USLCI database versions are available) at the [USLCI Downloads Page](/docs/release\_info/release-downloads.md). Finally, please see the [How to Publish in the USLCI](/docs/submission\_handbook/02-how-to-publish-in-the-uslci.md) section in the USLCI Data Submission Guidelines and/or contact the contact the [USLCI Data Curator](mailto:uslci@erg.com) if you have any data/metadata publishing goals for the next September 30, 2024 fall release date. We look forward to hearing from you soon.

## 2024 Spring Quarter (Scheduled March 31, Occurred March 29)
This USLCI Database release is Version 1 of the USLCI_2024_Q1 or spring 2024 release. This USLCI database version is available on the [NREL USLCI repo](https://www.lcacommons.gov/lca-collaboration/) of the [Federal LCA Commons Collaboration Server](https://www.lcacommons.gov) as well as via the [USLCI Release Downloads](/docs/release_info/release-downloads.md) page of this GitHub site.

### Overview of 2024\_Q1\_v1 Changes:

- Updated natural gas extraction processes
- Updated natural gas extraction mixture process
- Fixed database validation errors caused due missing natural gas flows
- Deleted various orphan flows and tar flow

### Change Log, Versioning, &amp; Data Submission

Please see the complete [Change Log](/docs/release\_info/change-log.md) for details of all spring 2024 updates. Additionally, please note that current and deleted datasets are always also available in an archive managed by NREL (wherein current and previous USLCI database versions are available) at the [USLCI Downloads Page](/docs/release\_info/release-downloads.md). Finally, please see the [How to Publish in the USLCI](/docs/submission\_handbook/02-how-to-publish-in-the-uslci.md) section in the USLCI Data Submission Guidelines and/or contact the contact the [USLCI Data Curator](mailto:uslci@erg.com) if you have any data/metadata publishing goals for the next June 30, 2024 summer release date. We look forward to hearing from you soon.

## 2023 Winter Quarter (Scheduled December 31, Occurred December 28)
This USLCI Database release is Version 1 of the USLCI_2023_Q4 or winter 2023 release. This USLCI database version is available on the [NREL USLCI repo](https://www.lcacommons.gov/lca-collaboration/) of the [Federal LCA Commons Collaboration Server](https://www.lcacommons.gov) as well as via the [USLCI Release Downloads](/docs/release_info/release-downloads.md) page of this GitHub site.

### Overview of 2023\_Q4\_v1 Changes:

-	Added crude oil extraction processes (off-shore domestic, off-short import, on-shore domestic, on-shore import)
-	Updated crude oil extraction mixture process
-	Updated petroleum refining process
-	Updated natural gas extraction mixture process
-	Updated multiple flow and process names to improve consistency across categories


### Change Log, Versioning, &amp; Data Submission

Please see the complete [Change Log](/docs/release\_info/change-log.md) for details of all winter 2023 updates. Additionally, please note that current and deleted datasets are always also available in an archive managed by NREL (wherein current and previous USLCI database versions are available) at the [USLCI Downloads Page](/docs/release\_info/release-downloads.md). Finally, please see the [How to Publish in the USLCI](/docs/submission\_handbook/02-how-to-publish-in-the-uslci.md) section in the USLCI Data Submission Guidelines and/or contact the contact the [USLCI Data Curator](mailto:uslci@erg.com) if you have any data/metadata publishing goals for the next March 31, 2024 spring release date. We look forward to hearing from you soon.

***The United States Life Cycle Inventory (USLCI) Database is a publicly available repository of life cycle inventory (LCI) data that supports research, analysis, and decision-making.***

## 2023 Fall Quarter (Scheduled September 30, Occurred September 22)
This USLCI Database release is Version 1 of the USLCI_2023_Q3 or fall 2023 release. This USLCI database version is available on the [NREL USLCI repo](https://www.lcacommons.gov/lca-collaboration/National_Renewable_Energy_Laboratory/USLCI_Public/datasets) of the [Federal LCA Commons Collaboration Server](https://www.lcacommons.gov) as well as via the [USLCI Release Downloads](/docs/release_info/release-downloads.md) page of this GitHub site.

### Overview of 2023\_Q3\_v1 Changes:

-	Fixed database validation errors caused due to product flow errors
-	Added 'Vinyl ester resin, at plant' process
-	Added 'Pultruded product, at plant' process
  
### Errata's Notification & Temporary Solution

Due to a bug in the publication process, some elementary flows are displaying with default providers, which are only intended for intermediate flows. To correct this error, you may use [this script](/development/curation%20issues_fy22_q4.md) in a local openLCA SQL interface. Simply copy and paste the code with your current USLCI database open in openLCA using **_Tools>Developer>SQL>SQL Statement_** and press the _‘Play’_ button as shown in the script link.

***This issue has been resolved in the .zolca version of this release download, but persists in the JSON-LD and Federal LCA Commons Collaboration Server versions.***

### Change Log, Versioning, &amp; Data Submission

Please see the complete [Change Log](/docs/release\_info/change-log.md) for details of all winter 2023 updates. Additionally, please note that current and deleted datasets are always also available in an archive managed by NREL (wherein current and previous USLCI database versions are available) at the [USLCI Downloads Page](/docs/release\_info/release-downloads.md). Finally, please see the [How to Publish in the USLCI](/docs/submission\_handbook/02-how-to-publish-in-the-uslci.md) section in the USLCI Data Submission Guidelines and/or contact the contact the [USLCI Data Curator](mailto:uslci@erg.com) if you have any data/metadata publishing goals for the next March 31, 2023 winter release date. We look forward to hearing from you soon.

***The United States Life Cycle Inventory (USLCI) Database is a publicly available repository of life cycle inventory (LCI) data that supports research, analysis, and decision-making.***


## 2023 Summer Quarter (Scheduled June 30, Occurred June 30)
This USLCI Database release is Version 1 of the USLCI_2023_Q2 or summer 2023 release. This USLCI database version is available on the [NREL USLCI repo](https://www.lcacommons.gov/lca-collaboration/National_Renewable_Energy_Laboratory/USLCI_Public/datasets) of the [Federal LCA Commons Collaboration Server](https://www.lcacommons.gov) as well as via the [USLCI Release Downloads](/docs/release_info/release-downloads.md) page of this GitHub site.

### Overview of 2023\_Q2\_v1 Changes:

-	Edited various processes to resolve internal_id and allocation errors
-	Deleted various orphan flows
-	Replaces the acrylonitrile process dataset with updated data
-	Added ‘Glass cermet; at plant’ process
-	Added ‘Hydrogen; proton exchange membrane water electrolysis; at plant’ process
-	Added ‘Hydrogen; small scale-steam methane reforming; at plant’ process
-	Added ‘Hydrogen; solid oxide electrolysis; at plant’ process
-	Added ‘Proton exchange water electrolysis plant; construction’ process
-	Added ‘Proton exchange water electrolysis stack; 1 MW; at plant’ process
-	Added ‘Solid oxide electrolysis cell; at plant’ process
-	Added ‘Solid oxide electrolysis plant; construction’ process
-	Added ‘Solid oxide electrolysis stack; 150 kW; at plant’ process
-	Added ‘Steam methane reforming plant; small-scale; construction’ process
-	Added ‘Acrylonitrile; at plant’ process
-	Added ‘Carbon fiber; at plant’ process
-	Added ‘Carbon fiber, reinforced polymer; at plant’ process
-	Added ‘Epoxy; at plant’ process
-	Added ‘Methyl methacrylate, MMA; at plant' process
-	Added ‘Polyacrylonitrile, PAN; at plant’ process
-	Added ‘Glass fiber, reinforced polymer; at plant’ process
-	Added ‘Glass fiber; at plant’ process
-	Added ‘Glass fiber, reinforced polymer; fine ground; from wind turbine’ process
-	Added ‘Landfilling, glass fiber, reinforced polymer’ process

### Errata's Notification & Temporary Solution

Due to a bug in the publication process, some elementary flows are displaying with default providers, which are only intended for intermediate flows. To correct this error, you may use [this script](/development/curation%20issues_fy22_q4.md) in a local openLCA SQL interface. Simply copy and paste the code with your current USLCI database open in openLCA using **_Tools>Developer>SQL>SQL Statement_** and press the _‘Play’_ button as shown in the script link.

***This issue has been resolved in the .zolca version of this release download, but persists in the JSON-LD and Federal LCA Commons Collaboration Server versions.***

### Change Log, Versioning, &amp; Data Submission

Please see the complete [Change Log](/docs/release\_info/change-log.md) for details of all summer 2023 updates. Additionally, please note that current and deleted datasets are always also available in an archive managed by NREL (wherein current and previous USLCI database versions are available) at the [USLCI Downloads Page](/docs/release\_info/release-downloads.md). Finally, please see the [How to Publish in the USLCI](/docs/submission\_handbook/02-how-to-publish-in-the-uslci.md) section in the USLCI Data Submission Guidelines and/or contact the contact the [USLCI Data Curator](mailto:uslci@erg.com) if you have any data/metadata publishing goals for the next September 30, 2023 fall release date. We look forward to hearing from you soon.

***The United States Life Cycle Inventory (USLCI) Database is a publicly available repository of life cycle inventory (LCI) data that supports research, analysis, and decision-making.***


## 2023 Spring Quarter (Scheduled March 31, Occurred April 3; April 19)
This USLCI Database release is **Version 2** of the USLCI_2023_Q1 or spring 2023 release. This USLCI database version is available on the [NREL USLCI repo](https://www.lcacommons.gov/lca-collaboration/National_Renewable_Energy_Laboratory/USLCI_Public/datasets) of the [Federal LCA Commons Collaboration Server](https://www.lcacommons.gov/lca-collaboration/search) as well as via the [USLCI Release Downloads](/docs/release_info/release-downloads.md) page of this GitHub site.

### Overview of 2023\_Q1\_v2 Changes:

  - Corrected the dioxin air emission value in the PVC dataset

## 2023 Spring Quarter (Scheduled March 31, Occurred April 3)
This USLCI Database release is Version 1 of the USLCI_2023_Q1 or spring 2023 release. This USLCI database version is available on the [NREL USLCI repo](https://www.lcacommons.gov/lca-collaboration/National_Renewable_Energy_Laboratory/USLCI_Public/datasets) of the [Federal LCA Commons Collaboration Server](https://www.lcacommons.gov/lca-collaboration/search) as well as via the [USLCI Release Downloads](/docs/release_info/release-downloads.md) page of this GitHub site.

### Overview of 2023\_Q1\_v1 Changes:

  - Correction to fix duplicate Internal ID errors across the database
  - Updated the polyether polyol for rigid foam polyurethane dataset
  - Updated the toluene diisocyanate, TDI, with a mass allocation dataset
  - Added the toluene diisocyanate, TDI, with a mass and elemental allocation dataset
  - Updated metadata for coal extraction and combustion processes

### Errata's Notification & Temporary Solution

Due to a bug in the publication process, some elementary flows are displaying with default providers, which are only intended for intermediate flows. To correct this error, you may use [this script](/development/curation%20issues_fy22_q4.md) in a local openLCA SQL interface. Simply copy and paste the code with your current USLCI database open in openLCA using **_Tools>Developer>SQL>SQL Statement_** and press the _‘Play’_ button as shown in the script link.

***This issue has been resolved in the .zolca version of this release download, but persists in the JSON-LD and Federal LCA Commons Collaboration Server versions.***

### Change Log, Versioning, &amp; Data Submission

Please see the complete [Change Log](/docs/release\_info/change-log.md) for details of all spring 2023 updates. Additionally, please note that current and deleted datasets are always also available in an archive managed by NREL (wherein current and previous USLCI database versions are available) at the [USLCI Downloads Page](/docs/release\_info/release-downloads.md). Finally, please see the [How to Publish in the USLCI](/docs/submission\_handbook/02-how-to-publish-in-the-uslci.md) section in the USLCI Data Submission Guidelines and/or contact the contact the [USLCI Data Curator](mailto:uslci@erg.com) if you have any data/metadata publishing goals for the next June 30, 2023 summer release date. We look forward to hearing from you soon.

***The United States Life Cycle Inventory (USLCI) Database is a publicly available repository of life cycle inventory (LCI) data that supports research, analysis, and decision-making.***

## 2022 Winter Quarter (Scheduled December 30, Occurred December 30; February 15)
This USLCI Database release is **Version 2** of the USLCI_2022_Q4 or winter 2022 release. This USLCI database version is available on the [NREL USLCI repo]([https://www.lcacommons.gov/lca-collaboration/National_Renewable_Energy_Laboratory/USLCI_Database_2022_Q4_v2](https://www.lcacommons.gov/lca-collaboration/search/page=1&repositoryId=National_Renewable_Energy_Laboratory%2FUSLCI_Database_2022_Q4_v2)) of the [Federal LCA Commons Collaboration Server](https://www.lcacommons.gov/lca-collaboration/search) as well as via the [USLCI Release Downloads](/docs/release_info/release-downloads.md) page of this GitHub site.

### Overview of 2022\_Q4\_v2 Changes:

- Correction to fix cutoff disposal flows that were used as both input and output flows in various processes. (This issue resulted in incorrect results for processes that included these cutoff disposal flows as inputs.)

  - Prior to this correction, the following cutoff flows were used as both inputs and outputs to processes: “Disposal, slag, to unspecified treatment”, “Disposal, solid waste to incineration with energy recovery”, “Disposal, solid waste to sanitary landfill”, “Disposal, solid waste, process, to waste-to-energy”, “Disposal, solid waste, unspecified, to municipal incineration”, and “Disposal, solid waste, process, to municipal incineration”, “Overburden, stockpiled, on-site, for unspecified beneficial reuse”, “Tailings, stockpiled, on-site, for unspecified beneficial reuse”. 
  - The results of the following datasets were affected by this error: “Steel, billets, at plant”, “Steel, liquid, at plant”, “EPS insulation board, at plant”, “Acrylonitrile, at plant”, “Carbon monoxide, at plant”, “Hydrochloric acid, without water, in 30% solution state, at plant”, “Polyol ether, for rigid foam polyurethane production, at plant”, “Toluene diisocyanate, TDI, at plant”, “Benzene, at plant”, “Butadiene, at plant”, “Chlorine, production mix, at plant”, “Open mold casting, rigid composites part, at plant”, “Open molding, rigid composites part, at plant”, “Pyrolysis gasoline, at plant”, “Unsaturated polyester, UPR, resin, at plant”, “Vacuum infusion, rigid composites part, at plant”, ‘Zinc, sheet – GLO",  and “Zinc, Special High Grade – GLO". 

- Merged multiple cutoff flows to reduce redundant flows. Deleted the “ecoinvent 3.2” folder after merging flows with the “CUTOFF Flows” folder.


## 2022 Winter Quarter (Scheduled December 30, Occurred December 30)

This USLCI Database release is the USLCI_2022_Q4 or winter 2022 release. This USLCI database version is available on the [NREL USLCI repo]([https://www.lcacommons.gov/lca-collaboration/National_Renewable_Energy_Laboratory/USLCI_Database_2022_Q4_v1](https://www.lcacommons.gov/lca-collaboration/search/page=1&repositoryId=National_Renewable_Energy_Laboratory%2FUSLCI_Database_2022_Q4_v1)) of the [Federal LCA Commons Collaboration Server](https://www.lcacommons.gov/lca-collaboration/search) as well as via the [USLCI Release Downloads](/docs/release_info/release-downloads.md) page of this GitHub site.

### Overview of 2022\_Q4\_v1 Changes:

- Updated emissions for e-glass dataset
- Updated water consumption recycled postconsumer polyethylene terephthalate, PET flake 
- New steel hot rolled coil dataset
- New steel pickled hot rolled coil dataset
- New steel cold rolled coil dataset
- New steel hot-dip galvanized coil dataset
- New steel plate dataset
- New steel section dataset
- Updated propylene oxide dataset
- Updated ethylene oxide dataset
- Updated Acrylonitrile-butadiene-styrene, ABS, copolymer resin dataset
- Updated Polypol ether, for flexible foam polyurethane production dataset
- Removed dated steel hot rolled sheet, steel cold rolled sheet datasets, and galvanized steel sheet

### IPCC Method Addition
There is now a method available to run USLCI results in openLCA with different versions of IPCC global warming potentials (AR4, AR5, AR6). This method can be found [here](https://github.com/uslci-admin/uslci-content/blob/dev/docs/methods/IPCC_json_v1.0.3.zip).

### Errata's Notification & Temporary Solution

Due to a bug in the publication process, some elementary flows are displaying with default providers, which are only intended for intermediate flows. To correct this error, you may use [this script](/development/curation%20issues_fy22_q4.md) in a local openLCA SQL interface. Simply copy and paste the code with your current USLCI database open in openLCA using **_Tools>Developer>SQL>SQL Statement_** and press the _‘Play’_ button as shown in the script link.

***This issue has been resolved in the .zolca version of this release download, but persists in the JSON-LD and Federal LCA Commons Collaboration Server versions.***

### Change Log, Versioning, &amp; Data Submission

Please see the complete [Change Log](/docs/release\_info/change-log.md) for details of all winter 2022 updates. Additionally, please note that current and deleted datasets are always also available in an archive managed by NREL (wherein current and previous USLCI database versions are available) at the [USLCI Downloads Page](/docs/release\_info/release-downloads.md). Finally, please see the [How to Publish in the USLCI](/docs/submission\_handbook/02-how-to-publish-in-the-uslci.md) section in the USLCI Data Submission Guidelines and/or contact the contact the [USLCI Data Curator](mailto:uslci@erg.com) if you have any data/metadata publishing goals for the next March 30, 2023 Spring release date. We look forward to hearing from you soon.

***The United States Life Cycle Inventory (USLCI) Database is a publicly available repository of life cycle inventory (LCI) data that supports research, analysis, and decision-making.***


## 2022 Fall Quarter (Scheduled September 30, Occurred September 30)

This USLCI Database release is the USLCI_2022_Q3 or fall 2022 release. This USLCI database version is available on the [NREL USLCI repo](https://www.lcacommons.gov/lca-collaboration/National_Renewable_Energy_Laboratory/USLCI_Database_2022_Q3_v1/datasets) of the [Federal LCA Commons Collaboration Server](https://www.lcacommons.gov/lca-collaboration/search) as well as via the [USLCI Release Downloads](/docs/release_info/release-downloads.md) page of this GitHub site.

### Overview of 2022\_Q3\_v1 Changes:

- Methylene diphenyl diisocyanate (MDI) new/updated datasets with two versions based on different allocation approaches
- Aniline updated dataset
- Styrene updated dataset
- Polystyrene, general purpose (GPPS) updated dataset
- Polybutadiene, butadiene rubber updated dataset
- Polystyrene, high impact (HIPS) updated dataset
- Hydrochloric acid (HCl) from MDI production new dataset 
- Condensed sources and actors
- Added metadata for PLA
- Updated select NAICS classifications
- Updated transport for mixed recyclables collection

### Errata's Notification & Temporary Solution

Due to a bug in the publication process, some elementary flows are displaying with default providers, which are only intended for intermediate flows. To correct this error, you may use [this script](/development/curation%20issues_fy22_q3.md) in a local openLCA SQL interface. Simply copy and paste the code with your current USLCI database open in openLCA using **_Tools>Developer>SQL>SQL Statement_** and press the _‘Play’_ button as shown in the script link.

***This issue has been resolved in the .zolca version of this release download, but persists in the JSON-LD and Federal LCA Commons Collaboration Server versions.***

### Change Log, Versioning, &amp; Data Submission

Please see the complete [Change Log](/docs/release\_info/change-log.md) for details of all fall 2022 updates. Additionally, please note that current and deleted datasets are always also available in an archive managed by NREL (wherein current and previous USLCI database versions are available) at the [USLCI Downloads Page](/docs/release\_info/release-downloads.md). Finally, please see the [How to Publish in the USLCI](/docs/submission\_handbook/02-how-to-publish-in-the-uslci.md) section in the USLCI Data Submission Guidelines and/or contact the contact the [USLCI Data Curator](mailto:uslci@erg.com) if you have any data/metadata publishing goals for the next December 30, 2022 Winter release date. We look forward to hearing from you soon.

***The United States Life Cycle Inventory (USLCI) Database is a publicly available repository of life cycle inventory (LCI) data that supports research, analysis, and decision-making.***



## 2022 Summer Quarter (Scheduled June 30, Occurred July 1)

This USLCI Database release is the USLCI_2022_Q2 or summer 2022 release. This USLCI database version is available on the [NREL USLCI repo](https://www.lcacommons.gov/lca-collaboration/National_Renewable_Energy_Laboratory/USLCI/datasets) of the [Federal LCA Commons Collaboration Server](https://www.lcacommons.gov/lca-collaboration/search) as well as via the [USLCI Release Downloads](/docs/release_info/release-downloads.md) page of this GitHub site. 

### USLCI Database Quarterly Release Resumes

The USLCI Database quarterly release has resumed with NREL remaining the host and manager of the database on the Federal LCA Commons. Quarterly data curation and updates will resume as of this release, under the leadership of Eastern Research Group (ERG). Please contact lci@nrel.gov and/or uslci@erg.com with any questions or concerns you may have about submitting data to the USLCI Database. Thank you for your continued support!

### Overview of 2022\_Q2\_v1 Changes:

- Kodak-Alaris new scanner dataset
- Minor corrections to PVC and EDC-VCM datasets
- Elimination of some duplicate CUTOFF flows and feedback errors
- Corrected naphtha inputs conversion for Calcium carbonate datasets
- Phased out obsolete forestry datasets with incorrect allocation factors
- Corrected volume-to-mass unit conversion factor for petroleum refined, to material use

### Errata's Notification & Temporary Solution

Due to a bug in the publication process, some elementary flows are displaying with default providers, which are only intended for intermediate flows. To correct this error, you may use [this script](/development/curation%20issues_fy22_q2.md) in a local openLCA SQL interface. Simply copy and paste the code with your current USLCI database open in openLCA using **_Tools>Developer>SQL>SQL Statement_** and press the _‘Play’_ button as shown in the script link.

### Change Log, Versioning, &amp; Data Submission

Please see the complete [Change Log](/docs/release\_info/change-log.md) for details of all summer 2022 updates. Additionally, please note that current and deleted datasets are always also available in an archive managed by NREL (wherein current and previous USLCI database versions are available) at the [USLCI Downloads Page](/docs/release\_info/release-downloads.md). Finally, please see the [How to Publish in the USLCI](/docs/submission\_handbook/02-how-to-publish-in-the-uslci.md) section in the USLCI Data Submission Guidelines and/or contact the contact the [USLCI Data Curator](mailto:uslci@erg.com) if you have any data/metadata publishing goals for the next September 30, 2022 Fall release date. We look forward to hearing from you soon.

_**The United States Life Cycle Inventory (USLCI) Database is a publicly available repository of life cycle inventory (LCI) data that supports research, analysis, and decision-making.**_

<br>

## 2021 Fall Quarter (Scheduled September 30, Occurred October 1)

This USLCI Database release is the USLCI_2021_Q3 or fall 2021 release. This USLCI database version is available on the [NREL USLCI repo](https://www.lcacommons.gov/lca-collaboration/National_Renewable_Energy_Laboratory/USLCI/datasets) of the [Federal LCA Commons Collaboration Server](https://www.lcacommons.gov/lca-collaboration/search) as well as via the [USLCI Release Downloads](/docs/release_info/release-downloads.md) page of this GitHub site. This release is intended as an augmentation to the normal fiscal quarter release scheduled for September 30, 2021 to align with several improvements going forward:

- Update to emissions for ACC PCV virgin resin & upstream EDC-VCM unit process datasets

- Update to one and addition of three CFFA single-ply, polyester reinforced PVC roofing membranes

- Update to actors’ contact information

- Improvements to process, product, and elementary flow nomenclature standardization

- Augmented some process and sources metadata (including hyperlinks, where available)

### Updated Method CED_FEDEFL_Adapted_v2

The FEDEFL-adapted Cumulative Energy Demand (CED) Method has been updated to version 2 to include a _’Non-renewable, biomass’_ category that accounts for _”Primary forest”_ elementary flow resource energy demand. The updated method is still accessible via [FEDEFL Adapted LCI & LCIA Methods](https://github.com/uslci-admin/uslci-content/wiki/FEDEFL-Adapted-LCI-&-LCIA-Methods) and the Collaboration Server [CED_Method](https://www.lcacommons.gov/lca-collaboration/National_Renewable_Energy_Laboratory/CED_Method/datasets) repository.

### Errata’s Notification & Temporary Solution

Due to a bug in the publication process, some elementary flows are displaying with default providers, which are only intended for intermediate flows. To correct this error, you may use [this script](/development/curation%20issues_fy21_q3.md) in a local openLCA SQL interface. Simply copy and paste the code with your current USLCI database open in openLCA using **_Tools>Developer>SQL>SQL Statement_** and press the _‘Play’_ button as shown in the script link.

### Change Log, Versioning, & Data Submission

Please see the complete [Change Log](/docs/release\_info/change-log.md) for details of all fall 2021 updates. Additionally, please note that current and deleted datasets are always also available in an archive managed by NREL (wherein current and previous USLCI database versions are available) at the [USLCI Downloads Page](/docs/release\_info/release-downloads.md). Finally, please see the [How to Publish in the USLCI](/docs/submission\_handbook/02-how-to-publish-in-the-uslci.md) section in the USLCI Data Submission Guidelines and/or contact the contact the [USLCI Data Curator](mailto:Rebe.Feraldi@lac-group.com) if you have any data/metadata publishing goals for the next December 31, 2021 Winter release date. We look forward to hearing from you soon.

<br>
<br>


## 2021 Spring Quarter (Scheduled March 31, Occurred April 8)


This USLCI Database release is the USLCI_2021_Q1 or Spring 2021 release. This USLCI database version is available on the [NREL USLCI repo](https://www.lcacommons.gov/lca-collaboration/search/page=1&amp;amp;amp;group=National\_Renewable\_Energy\_Laboratory) of the [Federal LCA Commons Collaboration Server](https://www.lcacommons.gov/lca-collaboration/search) as well as via the [USLCI Release Downloads](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release_info/release-downloads.md) page of this GitHub site. This release is intended as an augmentation to the normal fiscal quarter release scheduled for March 31, 2021 to align with several improvements going forward:

- Addition of ACC updated PCV virgin resin unit process & updates to the PVC resin supply chain (e.g., EDC-VCM, chlorine, sodium hydroxide, hydrogen)

- Addition of two updated Kodak-Alaris Office Scanner products and related China electricity grid mix average

- Update and corrections to coal and natural gas extraction processes (inputs from nature values and/or heating values)

- Correction to and/or establishment of default providers for all process exchanges with USLCI providers

- Correction to some input and output magnitudes to account for 2017-2018 database migration unit conversion errors

- Improvements to process, product, and elementary flow nomenclature standardization

- Augmented some process and sources metadata (including hyperlinks, where available)

Please see the complete [Change Log](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release\_info/change-log.md) for details of all Spring 2021 updates.

Additionally, please note that current and deleted datasets are always also available in an archive managed by NREL (wherein current and previous USLCI database versions are available) at the [USLCI Downloads Page](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release\_info/release-downloads.md).

Finally, please see the [How to Publish in the USLCI](https://github.com/uslci-admin/uslci-content/blob/dev/docs/submission\_handbook/02-how-to-publish-in-the-uslci.md) section in the USLCI Data Submission Guidelines and/or contact the contact the [USLCI Data Curator](mailto:Rebe.Feraldi@lac-group.com) if you have any data/metadata publishing goals for the next June 30, 2021 Spring release date. We look forward to hearing from you soon.

<br>

## 2020 Winter Quarter (Scheduled December 31, 2020; Occurred January 23, 2021)

This USLCI Database release is the USLCI_2020_Q4 or Winter 2020 release. This USLCI database version is available on the [NREL USLCI repo](https://www.lcacommons.gov/lca-collaboration/search/group=National\_Renewable\_Energy\_Laboratory) of the [Federal LCA Commons Collaboration Server](https://www.lcacommons.gov/lca-collaboration/search) as well as via the [USLCI Release Downloads](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release_info/release-downloads.md) page of this GitHub site. This release is intended as an augmentation to the normal fiscal quarter release scheduled for December 31, 2020 to align with several improvements going forward:

- Addition of ACC PP virgin resin unit process updates & updates to the resin supply chain (e.g., olefins, natural gas)

- Differentiation between energy of material resources and energy for combustion in natural gas & petroleum feedstocks

- Correction to and/or establishment of default providers

- Correction to some input and output magnitudes to account for 2017-2018 database migration unit conversion errors

- Elimination of 61 CUTOFF flows

- Improvements to process, product, and elementary flow nomenclature standardization

- Augmented some sources metadata (including hyperlinks, where available)


Please see the complete [Change Log](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release\_info/change-log.md) for details of all Winter 2020 updates.

Additionally, please note that current and deleted datasets are always also available in an archive managed by NREL (wherein current and previous USLCI database versions are available) at the [USLCI Downloads Page](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release\_info/release-downloads.md).

Finally, please see the [How to Publish in the USLCI](https://github.com/uslci-admin/uslci-content/blob/dev/docs/submission\_handbook/02-how-to-publish-in-the-uslci.md) section in the USLCI Data Submission Guidelines and/or contact the [USLCI Data Curator](mailto:Rebe.Feraldi@lac-group.com) if you have any data/metadata publishing goals for the next March 31, 2021 Spring release date. We look forward to hearing from you soon.

### A Note Regarding the US Electricity Baseline

Please note that the Federal LCA Commons has a new [landing page](https://www.lcacommons.gov/) from which you may _Browse Repositories_ if you want to explore other data becoming available from Federal LCA Commons (FLCAC) member agencies such as the [US Electricity Baseline](https://www.lcacommons.gov/lca-collaboration/search/page=1&group=Federal_LCA_Commons). There is a [USLCI Database Quick Help Video Series](https://www.youtube.com/playlist?list=PLmIn8Hncs7bFUOyXZNGXwG4LtdoTfLz6Q) in which many topics are covered including how to link USLCI data to this baseline data and how to reflect USLCI Database updates without breaking these links.

### A Note Regarding Nomenclature

Depending on the version of the USLCI Database and the method you use to calculate results in the past, there have always been elementary flow nomenclature linking gaps. Now, however, these gaps have been largely addressed by aligning the Federal Elementary Flow List (FEDEFL) with FEDEFL-adapted methods (including TRACI). Being adapted to this more standardized and consistent elementary flow nomenclature system enables obtaining consistent life cycle impact assessment (LCIA) results for USLCI datasets. Please see the [**FEDEFL-adapted methods**](https://github.com/uslci-admin/uslci-content/wiki/FEDEFL-Adapted-LCI-&-LCIA-Methods) page on this GitHub site to download and import methods that properly link the USLCI flows to method nomenclature, associated factors, and thus, accurate capture of inventory totals and impacts. Using the FEDEFL in the inventory and making these FEDEFL-adapted methods available to the public eliminates the need for the nomenclature alignment work previously required for users not having a proprietary software license(s).

<br>

## 2020 Fall Quarter (Scheduled September 30, Occurred September 21; October 29)

This USLCI Database release is **Version 2** of the USLCI_2020_Q3 or Fall 2020 release. **USLCI_2020_Q3 Version 1** occurred September 21 to preceed _USLCI Resources Pre-Conference Workshop_ on September 21st at the [American Center for Life Cycle Assessment (ACLCA) 2020 Virtual Conference]([https://aclca.org/aclca-2020/](https://aclca.org/aclca-2020/)). This USLCI database version is available on the [NREL USLCI repo](https://www.lcacommons.gov/lca-collaboration/search/page=1&amp;amp;amp;group=National\_Renewable\_Energy\_Laboratory) of the [Federal LCA Commons Collaboration Server](https://www.lcacommons.gov/lca-collaboration/search) as well as via the [USLCI Release Downloads](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release_info/release-downloads.md) page of this GitHub site. This release is intended as an augmentation to the normal fiscal quarter release scheduled for September 30, 2020 to align with several improvements going forward:

- Addition of ACC HDPE &amp; LLDPE virgin resin unit process updates

- Differentiation between unit &amp; system processes for chemicals &amp; resins

- Correction to some ambiguous and outdated elementary flows

- Improvements to process and product flow nomenclature standardization

From **USLCI_2020_Q3 Version 1** of the Fall release focused on energy &amp; electricity improvements:

- Default providers for **_Electricity, at grid_** were defined for all instances where this product flow is a process input in the USLCI Database. The US 2010 average grid mix process was used as the default provider in most instances as it is the latest available US average in the USLCI Database. Exceptions were to elect a Western or Eastern grid mix from 2014 as the default provider for some regional processes such as regional log yards and sawmills. You can still define any electricity provider you want for each process input instance of electricity but this ensures that a logical default is being used when running analyses in only the USLCI with no other linked database(s). You can bulk replace the default providers for this flow with one from the recently publish [US Electricity Baseline](https://www.lcacommons.gov/lca-collaboration/search/page=1&group=Federal_LCA_Commons) by following the procedure described in [this video](https://www.youtube.com/watch?v=SFGk85HmtL4&amp;list=PLmIn8Hncs7bFUOyXZNGXwG4LtdoTfLz6Q&amp;index=7).
- Several energy conversion errors from **USLCI_2020_Q2 (Summer 2020)** release version were corrected, which mostly affects metals inventories. For instance, 8 exchanges of uranium inputs retained values intended to be in MJ but displayed in kilograms during a prior update. This was significantly affecting the non-renewable, nuclear LCI results of metals such as steel and aluminum in the USLCI and so has been corrected. There was also a steel scrap looping error that was corrected.

Please see the complete [Change Log](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release\_info/change-log.md) for details of all Fall 2020 (Version 1 and 2) updates.

Additionally, please note that current and deleted datasets are always also available in an archive managed by NREL (wherein current and previous USLCI database versions are available) at the [USLCI Downloads Page](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release\_info/release-downloads.md).

Finally, please see the [How to Publish in the USLCI](https://github.com/uslci-admin/uslci-content/blob/dev/docs/submission\_handbook/02-how-to-publish-in-the-uslci.md) section in the USLCI Data Submission Guidelines and/or contact the contact the [USLCI Data Curator](mailto:Rebe.Feraldi@lac-group.com) if you have any data/metadata publishing goals for the next December 31, 2020 Fall release date. We look forward to hearing from you soon.

### A Note Regarding the US Electricity Baseline

Please note that the Federal LCA Commons has a new [landing page](https://www.lcacommons.gov/) from which you may _Browse Repositories_ if you want to explore other data becoming available from Federal LCA Commons (FLCAC) member agencies such as the [US Electricity Baseline](https://www.lcacommons.gov/lca-collaboration/search/page=1&group=Federal_LCA_Commons). There is a [USLCI Database Quick Help Video Series](https://www.youtube.com/playlist?list=PLmIn8Hncs7bFUOyXZNGXwG4LtdoTfLz6Q) in which many topics are covered including how to link USLCI data to this baseline data and how to reflect USLCI Database updates without breaking these links.

### A Note Regarding Nomenclature

Depending on the version of the USLCI Database and the method you use to calculate results in the past, there had always been nomenclature linking gaps. Now, however, these gaps have been largely addressed by aligning the Federal Elementary Flow List (FEDEFL) with FEDEFL-adapted methods. Being adapted to this more standardized and consistent elementary flow nomenclature system enables obtaining consistent life cycle impact assessment (LCIA) results for USLCI datasets. Please see the [**FEDEFL-adapted methods**](https://github.com/uslci-admin/uslci-content/wiki/FEDEFL-Adapted-LCI-&-LCIA-Methods) page on this GitHub site to download and import methods that properly link the USLCI flows to method nomenclature, associated factors, and thus, accurately capture of inventory totals and impacts. Using the FEDEFL in the inventory and making these FEDEFL-adapted methods available to the public eliminates the need for the nomenclature alignment work previously required for users not having a proprietary software license(s).

## ACLCA 2020 Workshops Announcement - September 2020

The American Center for Life Cycle Assessment (ACLCA) is offering Pre-Conference Workshops on September 21st at the [American Center for Life Cycle Assessment (ACLCA) 2020 Virtual Conference](https://aclca.org/aclca-2020/) event.

Two of these workshops focus on using [Federal LCA Commons (FLCAC)](https://www.lcacommons.gov/) resources:

1. 10:00 - 1:00 PM (ET): [**Using the Federal LCA Commons Elementary Flow List Toolkit**](https://www.eventbrite.com/e/using-the-federal-lca-commons-elementary-flow-list-toolkit-tickets-115650027345?aff=WebsiteLink): This course will provide step-by-step instruction for the use and application of Federal LCA Commons Elementary Flow List (FEDEFL) and associated tools.
2. 4:00 - 5:30 PM (ET): [**Using Federal LCA Commons Resources to Submit Data to the USLCI**](https://www.eventbrite.com/e/using-federal-lca-commons-resources-to-submit-data-to-the-uslci-tickets-115661457533?aff=WebsiteLink):  The course will show you how to obtain public data for your use and how to submit data for publication in the USLCI database.

LCACP CEU&#39;s are available. All registrants will receive the video recording of the workshop and materials. Find more details on timing and registration [here](https://aclca.org/aclca-2020/pre-conference-events/).
<br>
<br>


## 2020 Summer Quarter (Scheduled June 30, Occurred July 14)

This USLCI Database release occurred on July 14, 2020 to the USLCI database available on the [NREL USLCI repo](https://www.lcacommons.gov/lca-collaboration/search/page=1&amp;amp;group=National\_Renewable\_Energy\_Laboratory) of the [Federal LCA Commons Collaboration Server](https://www.lcacommons.gov/lca-collaboration/search), intended as the normal fiscal quarter release scheduled for June 30, 2020 to align with several improvements going forward:

- Correction to &quot;Petroleum refining, at refinery&quot; allocation factors &amp; product linking

- Update to ACC LDPE plastic resin data

- Update of USLCI forestry products nomenclature to match CORRIM repo for linking

- Augmented user rights &amp; and process-level data quality metadata for some processes

- Corrections to the following as noted in the [Spring Quarter Release Errata](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release_info/press-release.md#2020-spring-quarter-release-errata):

  - Carbon dioxide emissions for **_Diesel, combusted in industrial boiler_** was on a _m3_ diesel output basis (2,727 _kg / m3_ diesel). However, the remainder of the exchanges for this process are on the basis of 1 _L_ diesel output. Please note the carbon dioxide emission factor was corrected to 2.727 _kg / L_ diesel output to match the units of the quantitative reference and other exchanges for this process.

  - For **_Transport, combination truck, diesel powered_**, corrected units of **_Diesel, at refinery_** inputs from _m3_ to _L_ per output of _t*km_ transport

  - For **_Steam, purchased by containerboard mills_**, corrected units of residual fuel oil inputs from _m3_ to _L_ and value from _gal_ to _L_; corrected natural gas value converted from _ft3_ to _m3_ (British units originally submitted)

  - For **_Transport, ocean freighter, residual fuel oil powered_**, corrected units of residual fuel oil inputs from _m3_ to _L_

  - For the following processes, a bug error caused the quantitative reference output to be eliminated from the process (not the database). These output products with their respective values, units, and exchange comments were reinstated to their respecitive processes:

    - Corrugated product, average production, at mill

    - Aluminum, primary ingot, at plant

    - Acetic acid, at plant

    - Ethanol, denatured, corn dry mill

    - Aluminum, secondary ingot, at plant

    - Steel, stainless 304, scrap

    - Pulp, kraft market, bleached, average production, at mill

    - Wood Combusted, at boiler, at cellulosic fiberboard mill

Please see the complete [Change Log](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release\_info/change-log.md) for details.

Please note that the Federal LCA Commons has a new [landing page](https://www.lcacommons.gov/) from which you may \_&quot;Browse Repositories&quot;\_ if you want to explore other data becoming available from Federal LCA Commons (FLCAC) member agencies.

Additionally, please see the [How to Publish in the USLCI](https://github.com/uslci-admin/uslci-content/blob/dev/docs/submission\_handbook/02-how-to-publish-in-the-uslci.md) section in the USLCI Data Submission Guidelines and/or contact the contact the [USLCI Data Curator](mailto:Rebe.Feraldi@lac-group.com) if you have any data/metadata publishing goals for the next September 30, 2020 Fall release date. We look forward to hearing from you soon.

Finally, please note that current and deleted datasets are always also available in an archive managed by NREL (wherein current and previous USLCI database versions are available) at the [USLCI Downloads Page](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release\_info/release-downloads.md).


### A Note on Allocation Default Methods in oLCA

Using &#39;NONE&#39; or &#39;CAUSAL&#39; as the default allocation method, as designated by data providers in many USLCI multi-output processes, can produce unexpected LCI &amp; LCIA results in oLCA. The &#39;PHYSICAL&#39; and &#39;ECONOMIC&#39; default methods produce expected results. Further, selecting &#39;AS DEFINED IN PROCESS&#39; during calculations also produces expected results. See [this double counting thread on allocation](https://ask.openlca.org/2281/allocation-in-multifunctional-processes) and this [unit properties in allocation thread](https://github.com/GreenDelta/olca-app/issues/83) in the oLCA issues/Q&amp;A and GitHub Issues lists, respectively.

Until default allocation methods for multi-output processes in USLCI are adjusted and additional guidance is provided, NREL recommends using the &#39;AS DEFINED IN PROCESS&#39; default allocation when running calculations on USLCI data in oLCA.
<br>
### Reminder of FLCAC Adaptation of the Federal Elementary Flow List (FEDEFL) & TRACIv2.1

Since Spring quarter 2020, the USLCI is now the first repo on the [Federal LCA Commons (FLCAC)](https://www.lcacommons.gov/) to be compatible with the [Federal Elementary Flow List (FEDEFL)](https://github.com/USEPA/Federal-LCA-Commons-Elementary-Flow-List). The US EPA, the lead agency on the FEDEFL, worked with NREL to help map and convert the USLCI database to the FEDEFL. Per the emerging FLCAC standards & conventions, the FEDEFL will become a part of the core database structure across FLCAC repositories. The [CORRIM Forestry & Forestry Products](https://www.lcacommons.gov/lca-collaboration/search/page=1&group=CORRIM) database is in the process of being converted to the FEDEFL and other repos will follow. The FEDEFL will provide greater standardization and interoperability for Federal LCA data and can also serve as a standard for elementary flows for a broader community. 

Please note that there has also been a release of [TRACI 2.1 LCIA Method](https://www.lcacommons.gov/lca-collaboration/US\_Environmental\_Protection\_Agency/TRACI) repo on the FLCAC server that is compatible to the FEDEFL. **This version of TRACI must be used in order to obtain results for life cycle impact assessment (LCIA) calculations on FLCAC data adapted to the FEDEFL (e.g., USLCI Database).** A repo with [ReCiPe 2016 Midpoint and Endpoint ](https://www.lcacommons.gov/lca-collaboration/search/page=1&amp;group=Federal_LCA_Commons)methods that are FEDEFL-compatible has also been published to the FLCAC.
<br>

For more information regarding any of these changes, contact the [USLCI Data Curator](mailto:Rebe.Feraldi@lac-group.com) or the [USLCI Administrator](mailto:lci@nrel.gov).
<br>
<br>
<br>


## 2020 Spring Quarter Release Errata

**Please NOTE: the following errors have been identified in the current USLCI Database version and will be corrected for release to the public database for the June 30 quarterly publication update:**
<br>
- The carbon dioxide emissions for **_Diesel, combusted in industrial boiler_** are on a m3 diesel output basis (2,727 kg / m3 diesel). However, the remainder of the exchanges for this process are on the basis of 1 L diesel output. Please note the carbon dioxide emission factor should be corrected to 2.727 kg / L diesel output to match the quantitative reference and other exchanges for this process.
- For **_Transport, combination truck, diesel powered_**, correct units of Diesel, at refinery inputs from m3 to L per output of t*km transport
- For **_Steam, purchased by containerboard mills_**, correct units of residual fuel oil inputs from m3 to L and value from gal to L; corrected natural gas value converted from ft3 to m3 (British units originally submitted)
- For **_Transport, ocean freighter, residual fuel oil powered_**, correct units of residual fuel oil inputs from m3 to L
- For **_Coil, coating, m2, at plant_**, correct units of Disposal, liquid wastes, unspecified to waste water treatment inputs from m3 to L
- For **_Cotton, whole plant, at field_**, change quantitative reference from cotton straw to cotton; correct diesel fuel combusted in industrial boiler inputs unit from m3 to L
- For **_Potato, whole plant, at field_**, change quantitative reference from potato leaves to potatos; correct diesel fuel combusted in industrial boiler inputs unit from m3 to L
<br>

- For the following processes, a bug error caused the quantitative reference output to be eliminated. These outputs will be reinstated at the June 30 update. For now, please note that they are currently without the correct main product:
  - Corrugated product, average production, at mill
  - Aluminum, primary ingot, at plant
  - Acetic acid, at plant
  - Ethanol, denatured, corn dry mill
  - Aluminum, secondary ingot, at plant
  - Steel, stainless 304, scrap
  - Pulp, kraft market, bleached, average production, at mill
  - Wood Combusted, at boiler, at cellulosic fiberboard mill
  
Until the June 30 update, to determine the correct quantity for the output and/or read comments for these flows, please refer to the previous [USLCI Database version from Fall Interim Release 2019](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release_info/release-downloads.md#table-1-uslci-release-downloads), i.e., FY2019.Q4.02 in whichever file format you prefer.
  <br>
  <br>
  
  

## 2020 Spring Quarter (Scheduled March 31, Occurred April 24)

This USLCI Database release occurred on April 24, 2020 to the USLCI database available on the [NREL USLCI repo](https://www.lcacommons.gov/lca-collaboration/search/page=1&amp;group=National\_Renewable\_Energy\_Laboratory) of the [Federal LCA Commons Collaboration Server](https://www.lcacommons.gov/lca-collaboration/search), intended as the normal fiscal quarter release scheduled for March 31, 2020 to align with several improvements going forward:

- Addition of 4 processes for asphalt binder from the Asphalt Institute
- Corrections to units for volume and energy units for liquid fuels and electricity exchanges, respectively
- Improvements to the USLCI adaptation of the Federal Elementary Flow List (FEDEFL)

Please see the complete [Change Log](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release\_info/change-log.md) for details.

Please note that the Federal LCA Commons has a new [landing page](https://www.lcacommons.gov/) from which you may _"Browse Repositories"_ if you want to explore other data becoming available from Federal LCA Commons (FLCAC) member agencies.

Additionally, please see the [How to Publish in the USLCI](https://github.com/uslci-admin/uslci-content/blob/dev/docs/submission\_handbook/02-how-to-publish-in-the-uslci.md) section in the USLCI Data Submission Guidelines and/or contact the contact the [USLCI Data Curator](mailto:Rebe.Feraldi@lac-group.com) if you have any data/metadata publishing goals for the next June 30, 2020 Summer release date. We look forward to hearing from you soon.

Finally, please note that deleted datasets are always still available in an archive managed by NREL (wherein previous USLCI database versions are available) at the [USLCI Downloads Page](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release\_info/release-downloads.md).

<br>

**Asphalt Binder Datasets**

Life cycle inventory (LCI) data for four (4) new processes were added to the USLCI:

  1) [Asphalt binder, 0.5% polyphosphoric acid (PPA), consumption mix, at terminal, from crude oil, 0.5% polyphosphoric acid](https://www.lcacommons.gov/lca-collaboration/National_Renewable_Energy_Laboratory/USLCI/dataset/PROCESS/28d7d56e-a751-492c-9bb1-08f19ea4ac37)
  2) [Asphalt binder, 3.5% styrene-butadiene-styrene (SBS), consumption mix, at terminal, from crude oil, 3.5% styrene-butadiene-styrene](https://www.lcacommons.gov/lca-collaboration/National_Renewable_Energy_Laboratory/USLCI/dataset/PROCESS/bbf3dc45-a370-405e-8996-7358b7f1841c)
  3) [Asphalt binder, 8% ground rubber tire (GRT), consumption mix, at terminal, from crude oil, 8% ground rubber tire](https://www.lcacommons.gov/lca-collaboration/National_Renewable_Energy_Laboratory/USLCI/dataset/PROCESS/72d5a381-8cae-4e1d-b0a3-26cc43b69867)
  4) [Asphalt binder, no additives, consumption mix, at terminal, from crude oil](https://www.lcacommons.gov/lca-collaboration/National_Renewable_Energy_Laboratory/USLCI/dataset/PROCESS/f8ce5199-1666-452b-a267-8797c94d0560)

These data were compiled by [Sphera](https://sphera.com/) LCA consultants (who [recently acquired ThinkStep](https://sphera.com/news/sphera-signs-agreement-to-acquire-thinkstep/)) for the [Asphalt Institute](http://asphaltinstitute.org/). The LCA Report is available [here](http://www.asphaltinstitute.org/engineering/lca-study-on-asphalt-binders/). 

The product boundary begins with crude oil input to the refinery and ends at the asphalt terminal. Refining steps relevant to the production of asphalt binder include atmospheric distillation and vacuum distillation. The LCI data are system-level and represent the annual industry average for the US and Canada for 12 consecutive months during the 2015 and 2016 calendar years.

Please see the process metadata and/or the report for more information.

**Liquid Fuel & Electricity Unit Corrections:**

Over 1800 exchanges in the USLCI were corrected to reflect the correct units for 22 liquid fuels and chemicals and 54 electricity products due to a non-universal database units error at flow exchanges (i.e., many volume units were in cubic meters needing adjustment to liters and many electricity exchanges were in MJ units needing adjustment to kWh). This database error occurred in Spring quarter 2019 and was detected Winter 2019. Partial corrections were made (to transport modules) for the last Mid-Quarter update and the rest corrected this Spring 2020 quarter. USLCI end-users should use the 2020 USLCI database version to adjust models accordingly.

The volume units error was causing artificial over-estimation of fuel requirements (by factor of 1000 L-to-m3 conversion) for some but not all of the exchanges for the following liquid chemicals and fuels:

-  Acetone, liquid
-  Butyl acetate, liquid
-  Disposal, liquid waste, unspecified to waste water treatment
-  Ethanol, denatured, corn stover, biochemical
-  Gasoline, used in personal vehicle
-  Isobutyl acetate, liquid
-  Naphtha, at regional storage
-  Treatment, electrocoating wastewater, unspecified treatment
-  Diesel, at refinery
-  Diesel, combusted in industrial boiler
-  Diesel, combusted in industrial equipment
-  Gasoline, at refinery
-  Gasoline, combusted in equipment
-  Gasoline, combusted in equipment, at pulp and paper mill (EXCL.)
-  Kerosene, at refinery
-  Liquefied petroleum gas, at refinery
-  Liquefied petroleum gas, combusted in industrial boiler
-  LPG, combusted in industrial boiler, at pulp and paper mill (EXCL.)
-  Natural gas, combusted in industrial equipment
-  Residual fuel oil, at refinery
-  Residual fuel oil, combusted in industrial boiler
-  RFO, combusted in industrial boiler, at pulp and paper mill (EXCL.)


The energy units error was causing under-estimation of energy requirements (by a factor of 3.6 MJ-to-kWh conversion) for electricity at many processes:

- Electricity from hydro
- Electricity, alumina refining regions
- Electricity, aluminum smelting and ingot casting regions
- Electricity, anthracite coal, at power plant
- Electricity, at bauxite mining regions
- Electricity, at bleached kraft market pulp mill
- Electricity, at coated freesheet mill
- Electricity, at coated mechanical paper mill
- Electricity, at cogen
- Electricity, at cogen, for natural gas turbine
- Electricity, at grid
- Electricity, at grid, BC
- Electricity, at grid, MB
- Electricity, at grid, NB
- Electricity, at grid, ON
- Electricity, at grid, QC
- Electricity, at unbleached kraft bag and sack paper mill
- Electricity, at uncoated freesheet mill
- Electricity, at uncoated mechanical paper mill
- Electricity, at wind power plant, unspecified
- Electricity, biomass, at power plant
- Electricity, biomass, gas, landfill, at power plant
- Electricity, biomass, gas, unspecified, at power plant
- Electricity, biomass, liquid, sludge, at power plant
- Electricity, biomass, solid, agriculture by-products, at power plant
- Electricity, biomass, solid, biogenic MSW, at power plant
- Electricity, biomass,liquid, unspecified, at power plant
- Electricity, biomass,solid, unspecified, at power plant
- Electricity, bituminous coal, at power plant
- Electricity, cogenerated, at plant
- Electricity, diesel, at power plant
- Electricity, fossil, unspecified, at power plant
- Electricity, from renewable source, unspecified
- Electricity, geothermal, unspecified
- Electricity, hydropower, at power plant, unspecified
- Electricity, hydropower, at run-of-river power plant
- Electricity, lignite coal, at power plant
- Electricity, low voltage, at grid
- Electricity, low voltage, at grid/CN U
- Electricity, MSW, non-biogenic, at power plant
- Electricity, natural gas, at power plant
- Electricity, nuclear, at power plant
- Electricity, other fuels, at power plant, unspecified
- Electricity, other fuels, unspecified, at power plant
- Electricity, other gases, unspecified, at power plant
- Electricity, petroleum coke, at power plant
- Electricity, petroleum, waste oil, at power plant
- Electricity, photovoltaic, unspecified
- Electricity, residual fuel oil, at power plant
- Electricity, solar, unspecified, at power plant
- Electricity, tire derived fuel, at power plant
- Electricity, waste oil, at power plant
- Electricity; onsite boiler; hardwood mill; average
- Electricity; onsite boiler; softwood mill; average

**Federal Elementary Flow List (FEDEFL)**

This release corrected some elementary flows according to the Federal Elementary Flow List (FEDEFL). Some water emissions to water flows were being erroneously used as input exchanges so these flows were converted to be 'resource' flows as intended.

Please note that there has been a release of [TRACI 2.1 LCIA Method](https://www.lcacommons.gov/lca-collaboration/US\_Environmental\_Protection\_Agency/TRACI) repo on the FLCAC server using the FEDEFL, enabling the use of the TRACI 2.1 method on USLCI compatible with the implementation of the FEDEFL.

The US EPA, the lead agency on the FEDEFL, worked with NREL to help map and convert the USLCI data to the FEDEFL. The USLCI is the first large Federal LCA Commons (FLCAC) dataset to use the FEDEFL. The FEDEFL will become a part of the core database structure across FLCAC repositories. The FEDEFL will provide greater standardization and interoperability for Federal LCA data and can also serve as a standard for elementary flows for a broader community.




For more information regarding any of these changes, contact the [USLCI Data Curator](mailto:Rebe.Feraldi@lac-group.com) or the [USLCI Administrator](mailto:lci@nrel.gov).

<br>
<br>
<br>


## 2019 Winter Quarter (December 31)


The USLCI quarterly update slated for December 31 occurred on January 1, 2020. Several improvements, reviesions, and deltions were implemented to the database available on the [NREL USLCI repo](https://www.lcacommons.gov/lca-collaboration/search/page=1&group=National_Renewable_Energy_Laboratory) of the [Federal LCA Commons Collaboration Server](https://www.lcacommons.gov/lca-collaboration/search) including:

  * The word "CUTOFF" has been removed from technospheric flows not having a producing process in the USLCI; however, all cutoff flows are categorized in the same Flows\Technosphere Flows\CUTOFF Flows folder and display within processes with this categorization, which helps identify provenance.
  *  Over 19,000 orphan flows have been identified and eliminated from the USLCI (i.e., those not linked to any exchanges)
  *  Updated PET data (and supply chain links) from NAPCOR/ACC are now available
  *  Several flows erroneously categorized as an 'elementary-type' flow have been corrected to display as technosphere-type' or 'waste-type' flows and categorized in the Flows\Technosphere Flows folder accordingly.
  *  A new folder with 'technosphere-type' flows only has been established for Ecosystem Services (e.g., land transformation flows)
  *  Several display errors from the PET resin supply chain have been corrected 
  *  Several outdated and duplicate flows have been eliminated and flow nomenclature improved
  
Please see the complete [Change Log](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release_info/change-log.md) for details.

Note, shortly there will be a version 2 of this 2019 Winter (Q4) release that will eliminate CORRIM data duplicates that now have updated versions available in the [USFS CORRIM Repository](https://www.lcacommons.gov/lca-collaboration/US_Forest_Service_Forest_Products_Lab/CORRIM) on the Federal LCA Commons. This mid-quarter version will also have a complete mapping of elementary flows to the newly developed [Federal Elementary Flow List](https://cfpub.epa.gov/si/si_public_record_Report.cfm?dirEntryId=347251&Lab=NRMRL), developed by the EPA.

Also, note that the Federal LCA Commons has a new [landing page](https://www.lcacommons.gov/) from which you may "Browse Repositories" if you want to explore other data becoming available from Federal LCA Commons member agencies.

Additionally, please see the [How to Publish in the USLCI](https://github.com/uslci-admin/uslci-content/blob/dev/docs/submission_handbook/02-how-to-publish-in-the-uslci.md) section in the USLCI Data Submission Guidelines and/or contact the contact the [USLCI Data Curator](mailto:Rebe.Feraldi@lac-group.com) if you have any data/metadata publishing goals for the March 31, 2020 Spring release date. We look forward to hearing from you soon.

Finally, please note that deleted datasets are always still available in an archive managed by NREL (wherein previous USLCI database versions are available at the [USLCI Downloads Page](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release_info/release-downloads.md).
<br>
<br>


## 2019 Fall Quarter (October 23)

Currently, the Federal LCA Commons Collaboration Server is experiencing a bug so downloading repositories from the server is on hold until the issue is addressed. In the meantime, NREL has updated the [USLCI Release Downloads](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release_info/release-downloads.md) page to include the current USLCI release version. The JSON-LD and ILCD file sizes are larger than ecoSpold2 so these links will re-direct you to a Dropbox page to download the zip files. If importing the files into openLCA, leave the files zipped and select from the openLCA importer tool.

For many users, the JSON-LD (zipped) formats will be the most useful since they are not subject to data/metadata loss when imported into [openLCA].  The other formats are subject to data loss in certain use cases. For example, using ILCD format of the USLCI will result in the loss of comments associated with individual exchanges. EcoSpold file formats only contain processes so flows, indicators, & background data are excluded.
<br>
<br>





## 2019 Fall Quarter (September 30)
The USLCI quarterly update slated for September 30 ocurred on October 3, 2019. Several improvements and additions were made to the database available on the [NREL USLCI repo](https://www.lcacommons.gov/lca-collaboration/search/page=1&group=National_Renewable_Energy_Laboratory) of the [Federal LCA Commons Collaboration Server](https://www.lcacommons.gov/lca-collaboration/search) including:

  * Technospheric flows (processes and products) have been re-categorized to be aligned with the NAICS folder structure being adapted by repos of the Federal LCA Commons
  *  The EPA Data Quality System is now integrated into the USLCI to be aligned with the system being adapted by the repos of the Federal LCA Commons (see the [relevant section in the USLCI Data Submission Guidelines](https://github.com/uslci-admin/uslci-content/blob/dev/docs/submission_handbook/04-resources/04-App-G.md#using-the-us-epa-data-quality-matrix-in-openlca) for details on how to use this system in openLCA)
  *  Updated PET data (and supply chain links) from NAPCOR/ACC are now available
  *  New electronic scanner data are available from Kodak-Alaris
  *  Agricultural, utility, and transport products have been decoupled from the geographic and temporal scope of their parent processes to eliminate duplicate flows and allow end-users to designate a default provider for products having more than one parent process in openLCA
  *  Several conversion factors have been inserted for natural gas and CO2 emissions corrected for diesel combustion
  *  Coal extraction data have been phased out as they are now superceded by those available in the [NETL Coal Repository](https://www.lcacommons.gov/lca-collaboration/search/page=1&group=National_Energy_Technology_Lab) on the Federal LCA Commons.
  *  Several outdated and duplicate flows have been eliminated and flow nomenclature improved
  
Please see the complete [Change Log](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release_info/change-log.md) for details.

The Federal LCA Commons has a new [landing page](https://www.lcacommons.gov/) from which you may "Browse Repositories" if you want to explore other data becoming available from Federal LCA Commons member agencies.

Additionally, please see the [How to Publish in the USLCI](https://github.com/uslci-admin/uslci-content/blob/dev/docs/submission_handbook/02-how-to-publish-in-the-uslci.md) section in the USLCI Data Submission Guidelines and/or contact the contact the [USLCI Data Curator](mailto:Rebe.Feraldi@lac-group.com) if you have any data/metadata publishing goals for the December 31, 2019 Winter release date. We look forward to hearing from you soon.

Finally, please note that deleted datasets are always still available in an archive managed by NREL (wherein previous USLCI database versions are available at the [USLCI Downloads Page](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release_info/release-downloads.md).
<br>
<br>


## 2019 Summer Quarter (June 30)
The USLCI quarterly update occurred on June 30, 2019. The most recent udate of the [USLCI Database](https://www.lcacommons.gov/lca-collaboration/search/page=1&group=National_Renewable_Energy_Laboratory) is now available on the [Federal LCA Commons Collaboration Server](https://www.lcacommons.gov/lca-collaboration/search), which contains multiple group repositories. For this update, there was a display correction for the hydrogen synthesis dataset, some corrections to the allocation settings for some wood manufacturing processes, and several deletions of old providers. Please see the complete [Change Log](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release_info/change-log.md) for details.

Additionally, please see the [How to Publish in the USLCI](https://github.com/uslci-admin/uslci-content/blob/dev/docs/submission_handbook/02-how-to-publish-in-the-uslci.md) in the USLCI Data Submission Guidelines and/or contact the contact the [USLCI Data Curator](mailto:Rebe.Feraldi@lac-group.com) if you have any data/metadata publishing goals for the September 30, Fall 2019 release date. We look forward to hearing from you soon.

NREL is publishing a coordination report to provide information about the US Federal Life Cycle Assessment Commons (FLCAC). The FLCAC is not only a public data source but also a repository for data developed under Energy Efficiency & Renewable Energy (EERE) programs. The FLCAC Commons Working Group is coordinating and focusing efforts to improve the standardization of data documentation, formatting, and nomenclature to ensure lossless data loading and accurate data representation in the repository server. The report introduces LCA within EERE programs, describes the current status of the FLCAC, and iterates opportunities for the FLCAC to support EERE goals and objectives. See the [full Coordination Report here](https://github.com/uslci-admin/uslci-content/blob/dev/docs/coordination_report/toc.md).

Finally a note of explanation on database deletions in updates on which we have received inquiries: Datasets deleted are always still available in an archive managed by NREL (previous USLCI database versions are available on the main Wiki's [USLCI Release Downloads](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release_info/release-downloads.md) page. However, when the [Change Logs](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release_info/change-log.md) indicate the dataset was an "outdated provider," this means that there is a newer (i.e., more updated) equivalent dataset available in the database from the same data compiler. An example for the last dataset was petroleum refining compiled by ERG--there were 2 petroleum refining datasets from the ERG but one was outdated and many users were unsure as to which one to select for linking in upstream processes. One of the main issues with this instance is that one was referred to as "crude oil refining" and the other as "petroleum refining"--however, they referred to the same process. This occurred because nomenclature standards continue to be improved as the USLCI strives to coordinate with other agencies in the multi-agency collaboration that is the Federal LCA Commons. NREL will continue to resolve these types of issues in the USLCI by including only the latest (i.e., most appropriate) datasets for performing LCAs. An exception is if you were performing a retrospective study and even then, some of the methodologies are updated from one provider to another. Please let me know if you have further questions regarding this issue or archived datasets. The same explanation applies to corrugated products--these datasets have been updated so the older ones are no longer intended for use but are still available in archived versions of the USLCI database.
<br>
<br>


## 2019 - Spring Quarter (March 31)
The USLCI quarterly update occurred on March 31, 2019. There were no new data or data updates so there is no change log. Please see the [How to Publish in the USLCI](https://github.com/uslci-admin/uslci-content/blob/dev/docs/submission_handbook/02-how-to-publish-in-the-uslci.md) in the USLCI Data Submission Guidelines and/or contact the contact the [USLCI Data Curator](mailto:Rebe.Feraldi@lac-group.com) if you have any data/metadata publishing goals for the June 30, Summer 2019 release date. We look forward to hearing from you soon.
<br>
<br>


## 2018 - Winter Quarter (December 21)
The USLCI quarterly update occurred on December 21, 2018 and contained no new data. The next update will occur March 31, 2019. Please see the [How to Publish in the USLCI](https://github.com/uslci-admin/uslci-content/blob/dev/docs/submission_handbook/02-how-to-publish-in-the-uslci.md) in the USLCI Data Submission Guidelines and/or contact the contact the [USLCI Data Curator](mailto:Rebe.Feraldi@lac-group.com) if you have any data/metadata publishing goals for the Spring 2019 release date. We look forward to hearing from you soon.
<br>
<br>





## [2018 - Fall Quarter (September 30)](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release_info/press-release/2018_q3.md)
The most recent udate of the [USLCI Database](https://www.lcacommons.gov/lca-collaboration/search/page=1&group=National_Renewable_Energy_Laboratory) is now available on the newly created [Federal LCA Commons Collaboration Server](https://www.lcacommons.gov/lca-collaboration/search) (_beta version_), which contains multiple group repositories.

<br>
<br>

---
# USLCI Database Citation

**NOTE: If you need to cite the USLCI Database, use the following format:**

_"U.S. Life Cycle Inventory Database." (RELEASE YEAR). National Renewable Energy Laboratory, RELEASE YEAR. Accessed _[Month Day, YEAR]_: [https://www.lcacommons.gov/nrel/search](https://www.lcacommons.gov/nrel/search)_

---
[Return to Top of Page](https://github.com/uslci-admin/uslci-content/blob/dev/docs/release_info/press-release.md#earth_americas-uslci-press-releases-newspaper)

[Return to USLCI Content Wiki](https://github.com/uslci-admin/uslci-content/wiki)

