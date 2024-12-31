:arrow_double_down:  USLCI Release Downloads
==================
[Return to USLCI Content Wiki](https://github.com/uslci-admin/uslci-content/wiki)

This page contains dowloads for the [US Life Cycle Inventory Database (USLCI)](https://www.nrel.gov/lci/) release downloads in various data formats. It is intended to support the USLCI data submission process. The USLCI is updated quarterly based on the [U.S. Federal Government Fiscal Calendar](https://www.senate.gov/reference/glossary_term/fiscal_year.htm).

:tv: :sound: <br>

For video guidance on accessing, navigating, versioning, using, and submitting data to the USLCI Database (and more), please see the [USLCI Quick Help Video Series](https://www.youtube.com/playlist?list=PLmIn8Hncs7bFUOyXZNGXwG4LtdoTfLz6Q) on NREL's Learning YouTube channel.
<br> 
:tv: :sound:

<br><br>

:arrow_double_down:  USLCI Versions - Files Table
==================


[Table 1](release-downloads.md#table-1-uslci-release-downloads) below also contains download links for current and past USLCI quarter release versions in four data formats and associated libraries: 
* JSON-LD
* openLCA .zolca
* ecoSpold2
* ILCD
* Library

For many users, the JSON-LD (zipped) formats will be the most useful since they are subject to little or no metadata loss when imported into [openLCA].  The other formats are subject to data loss in certain use cases. For example, using ILCD format of the USLCI will result in the loss of comments associated with individual exchanges. EcoSpold file formats only contain processes so flows, indicators, & background data are excluded. Details on the file formats supported in openLCA are in the [openLCA Version 1.10 User Manual](http://www.openlca.org/wp-content/uploads/2020/02/openLCA_1.10_User-Manual.pdf).

Downloads are available starting with USLCI release FY17.Q4.02 and include the current quarter release available on the Federal LCA Commons Collaboration Server. The [FLCAC wide versioning system](https://flcac-admin.github.io/FLCAC-docs/versioning) was implemented October, 2024. Each USLCI quarterly release will be reflected as a MINOR change.

Select the desired format type: 
* Since 2019.Q3, the JSON-LD and ILCD files are larger in size and you will be re-directed to a Box link to download
* For all others, select _"View Raw"_ to download the file on the subsequent GitHub screen
* For ecoSpold2, only "Processes" export from openLCA so the file size is smaller


<br>

#### Table 1. USLCI release downloads   

| Release Version | openLCA version | openLCA | JSON-LD | ecoSpold2 | ILCD | Library |  
|:---:|:---:|:---:|:---:|:---:|:--:|:--:|   
| 1.2024-12.0* | v2.4.0 |[zolca](https://github.com/FLCAC-admin/uslci-content/blob/dev/downloads/uslci_fy24_q4_01_olca2_4_0_elci_lib.zolca)| [JSON-LD](https://github.com/FLCAC-admin/uslci-content/blob/dev/downloads/uslci_fy24_q4_01_olca2_4_0_elci_lib_json_ld.zip)| [ecoSpold2] | [ILCD] | [eLCI](https://github.com/FLCAC-admin/uslci-content/blob/dev/downloads/elci_6_2024%20for%20uslci_2024_final_library_format.zip)
| 1.2024-10.0* | v2.3.0 |[zolca](https://github.com/FLCAC-admin/uslci-content/blob/dev/downloads/uslci_fy24_q3_01_olca2_3_0_elci_lib.zolca)| [JSON-LD](https://github.com/FLCAC-admin/uslci-content/blob/dev/downloads/uslci_fy24_q3_01_olca2_3_0_elci_lib_json_ld.zip)| [ecoSpold2] | [ILCD] | [eLCI](https://github.com/FLCAC-admin/uslci-content/blob/dev/downloads/elci_6_2024%20for%20uslci_2024_final_library_format.zip)
| FY24.Q2.01 | v2.2.0 |[zolca](https://github.com/FLCAC-admin/uslci-content/blob/dev/downloads/uslci_fy24_q2_01_olca2_2_0_elci_lib.zolca)| [JSON-LD](https://github.com/FLCAC-admin/uslci-content/blob/dev/downloads/uslci_fy24_q2_01_olca2_2_0_elci_lib_json_ld.zip)| [ecoSpold2] | [ILCD] | [eLCI](https://github.com/FLCAC-admin/uslci-content/blob/dev/downloads/elci_6_2024%20for%20uslci_2024_final_library_format.zip)
| FY24.Q1.01 | v2.1.1 |[zolca](https://github.com/FDC-admin/uslci-content/blob/dev/downloads/uslci_fy24_q1_01_olca2_1_1.zolca)| [JSON-LD](https://github.com/FDC-admin/uslci-content/blob/dev/downloads/uslci_fy24_q1_01_olca2_1_1_json_ld.zip)| [ecoSpold2] | [ILCD] 
| FY23.Q2.01 | v2.0.0 |[zolca](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy23_q4_01_olca2_0_3.zolca)| [JSON-LD](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy23_q4_01_olca2_0_3_json_ld.zip)| [ecoSpold2] | [ILCD] 
| FY23.Q2.01 | v2.0.0 |[zolca](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy23_q2_01_olca2_0_0.zolca)| [JSON-LD](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy23_q2_01_olca2_0_0_json_ld.zip)| [ecoSpold2] | [ILCD] 
| FY23.Q1.02 | v1.10.3 |[zolca](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy23_q1_02_olca1_10_3.zolca)| [JSON-LD](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy23_q1_02_olca1_10_3_json_ld.zip)| [ecoSpold2] | [ILCD] 
| FY23.Q1.01 | v1.10.3 |[zolca](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy23_q1_01_olca1_10_3.zolca)| [JSON-LD](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy23_q1_01_olca1_10_3_json_ld.zip)| [ecoSpold2] | [ILCD] 
| FY22.Q4.02 | v1.10.3 |[zolca](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy22_q4_02_olca1_10_3.zolca)| [JSON-LD](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy22_q4_02_olca1_10_3_json_ld.zip)| [ecoSpold2] | [ILCD] 
| FY22.Q4.01 | v1.10.3 |[zolca](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy22_q4_01_olca1_10_3.zolca)| [JSON-LD](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy22_q4_01_olca1_10_3_json_ld.zip)| [ecoSpold2] | [ILCD] 
| FY22.Q3.01 | v1.10.3 |[zolca](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy22_q3_01_olca1_10_0.zolca)| [JSON-LD]| [ecoSpold2] | [ILCD] 
| FY22.Q2.01 | v1.10.3 |[zolca](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy22_q2_01_olca_10_3_.zolca) | [JSON-LD] | [ecoSpold2] | [ILCD] |
| FY21.Q3.01 | v1.10.3 |[zolca](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy21_q3_01_olca_10_3_.zolca) | [JSON-LD](https://app.box.com/s/8rv697xd6gqehat1o8mv4t09xce34dzw) | [ecoSpold2](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy21_q3_01_olca_10_3_ecospold2.zip) | [ILCD](https://app.box.com/s/iisvem9o9l8k8198h311z8whpf0uu8cl) |
| FY21.Q1.01 | v1.10.3 |[zolca](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy21_q1_01_olca1_10_3.zolca) | [JSON-LD](https://app.box.com/s/9afxvz4jvqsz0kcq7c5gc7nvsoh4nzqd) | [ecoSpold2](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy21_q1_01_olca1_10_3_ecospold2.zip) | [ILCD](https://app.box.com/s/cvsotaydea52xpavtt40aykf7b9zl13q) |
| FY20.Q4.01 | v1.10.3 |[zolca](https://app.box.com/s/o6aw25fvzlxcpmfkh7ec8fllvzvzj8sz) | [JSON-LD](https://app.box.com/s/eq0mivu40bqzioilszw9q30htzrnufuy) | [ecoSpold2](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy20_q4_01_olca1_10_3_ecospold.zip) | [ILCD](https://app.box.com/s/n8ermjf92g7i0vi52y3dnkt6celrhy5l) |
| FY20.Q3.02 | v1.10.3 |[zolca](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy20_q3_02_olca1_10_3_zolca.zolca) | [JSON-LD](https://app.box.com/s/r63m6xjojahb4cezr58wtft9bjnnkmrm) | [ecoSpold2](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy20_q3_02_olca1_10_3_ecospold.zip) | [ILCD](https://app.box.com/s/170ywdiq8gafivw3429srnc8q8ay0xt2) |
| FY20.Q3.01 | v1.10.3 |[zolca](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy20_q3_01_olca1_10_3_zolca.zolca) | [JSON-LD](https://app.box.com/s/kzucre7sik2yt8urgatg4e0mlib4tbcv) | [ecoSpold2](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy20_q3_01_olca1_10_3_ecospold.zip) | [ILCD](https://app.box.com/s/zulcmvp9g6ftlivoe6yns1cgiclur34m) |
| FY20.Q2.01 | v1.10.1 | [zolca](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy20_q2_01_olca1_10_3.zolca) | [JSON-LD](https://app.box.com/s/ohqsukgivevlzi49dx2duh1dob5l58gh) | [ecoSpold2](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy20_q2_01_olca1_10_3_ecospold2.zip) | [ILCD](https://app.box.com/s/layz422j1z3wzpwgzflxjq4vpam9qbze) |
| FY20.Q1.01 | v1.10.1 | [zolca](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy20_q1_olca1_1_0.zolca) | [JSON-LD](https://app.box.com/s/1qjqhc7y2rwyvjmo7wu53a4nodjdn7lj) | [ecoSpold2](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy20_q1_olca1_1_0_ecospold2.zip) | [ILCD](https://app.box.com/s/s2gd2733z3dio5b8unsatgkiyg5pb1l0) |
| FY19.Q4.02 | v1.10.1 | [zolca](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy19_q4_02_olca1_10_0_zolca.zolca) | [JSON-LD](https://app.box.com/s/ugq6r4lp4votmzdrex6xokgxfdfgdyqf) | [ecoSpold2](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy19_q4_02_olca1_10_0_ecospold2.zip) | [ILCD](https://app.box.com/s/4f0fcoquczxu9pll2o1gj4brm7377w5z) |
| FY19.Q4.01 | v1.10.0 | no .zolca files this quarter | [JSON-LD](https://app.box.com/s/ljzo0ns7gnowemteroki11ubjaulh5st) | [ecoSpold2](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy19_q4_olca1_10_0_ecospold.zip.zip) |[ILCD](https://app.box.com/s/tlseuabs9130jgjrfoiickp3tu606pzq) |
| FY19.Q3.01 | v1.9.0 | no .zolca files this quarter | [JSON-LD](https://app.box.com/s/lv8mzuyyr33r11cmxfdt9k887w7h0sat) | [ecoSpold2](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy19_q3_01_olca1_9_0_ecospold.zip.zip) | [ILCD](https://app.box.com/s/6pc5cha9wv3zb9lye1y6up5sk06ooxmx) |
| FY19.Q2.01 | v1.8.0 |no .zolca files this quarter | [JSON-LD](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy19_q2_01_olca1_8_0_json_ld.zip.zip) | [ecoSpold2](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy19_q2_01_olca1_8_0_ecospold2.zip.zip) | [ILCD](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslcy_fy19_q2_01_olca1_8_0_ilcd.zip.zip) |
| FY18.Q3.01 | v1.7.2 | .zolca files discontinued 10/2018 |  [JSON-LD](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy18_q3_01_olca1_7_2_json_ld.zip) | [ecoSpold2](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy18_q1_01_olca1_7_0_ecospold2.zip) | [ILCD](https://github.com/uslci-admin/uslci-content/blob/dev/downloads/uslci_fy17_q4_02_olca1_5_0_ilcd.zip) |  
| FY18.Q2.01 | v1.7.2 | [openLCA](https://github.com/uslci-admin/uslci-content/tree/dev/downloads/uslci_fy18_q1_01_olca1_7_0.zolca) |  [JSON-LD](https://github.com/uslci-admin/uslci-content/tree/dev/downloads/uslci_fy18_q1_01_olca1_7_0_json_ld.zip) | [ecoSpold2](https://github.com/uslci-admin/uslci-content/tree/dev/downloads/uslci_fy18_q1_01_olca1_7_0_ecospold2.zip) | [ILCD](https://github.com/uslci-admin/uslci-content/tree/dev/downloads/uslci_fy18_q1_01_olca1_7_0_ilcd.zip) |  
| FY18.Q1.01 | v1.5.0 | [openLCA](https://github.com/uslci-admin/uslci-content/tree/dev/downloads/uslci_fy18_q1_01_olca1_5_0.zolca) |  [JSON-LD](https://github.com/uslci-admin/uslci-content/tree/dev/downloads/uslci_fy18_q1_01_olca1_5_0_json_ld.zip) | [ecoSpold2](https://github.com/uslci-admin/uslci-content/tree/dev/downloads/uslci_fy18_q1_01_olca1_5_ecospold2.zip) | [ILCD](https://github.com/uslci-admin/uslci-content/tree/dev/downloads/uslci_fy18_q1_01_olca1_5_0_ilcd.zip) |   
| FY17.Q4.02 | v1.5.0 | [openLCA](https://github.com/uslci-admin/uslci-content/tree/dev/downloads/uslci_fy17_q4_02_olca1_5_0.zolca) | -- | [ecoSpold2](https://github.com/uslci-admin/uslci-content/tree/dev/downloads/uslci_fy17_q4_02_olca1_5_0_ecospold2.zip) | [ILCD](https://github.com/uslci-admin/uslci-content/tree/dev/downloads/uslci_fy17_q4_02_olca1_5_0_ilcd.zip) |  

<br>
* The [FLCAC wide versioning system](https://flcac-admin.github.io/FLCAC-docs/versioning) was implemented October, 2024. Each USLCI quarterly release will be reflected as a MINOR change.
<br><br><br>

---
### USLCI Database Citation

**NOTE: If you need to cite the USLCI Database, use the following format:**

_"U.S. Life Cycle Inventory Database." (RELEASE YEAR). National Renewable Energy Laboratory, RELEASE YEAR_QUARTER_VERSION. Accessed _[Month Day, YEAR]_: [https://www.lcacommons.gov/nrel/search](https://www.lcacommons.gov/nrel/search)_

---
<br>
<br>


[Return to USLCI Content Wiki](https://github.com/uslci-admin/uslci-content/wiki)


[openlca]: http://www.openlca.org/download/
