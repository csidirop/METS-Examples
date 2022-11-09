# METS-Examples
Collection of various METS-XML files from Institutions and Libraries (most german) for testing and development purposes.

## METS-XML
More aboute METS-XML: [Wiki](https://en.wikipedia.org/wiki/Metadata_Encoding_and_Transmission_Standard) and [loc](http://www.loc.gov/standards/mets/)

## Folder Structure
The folder structure is derived from the [URNs](https://en.wikipedia.org/wiki/Uniform_Resource_Name) of the respective institutions.

```
├─noURN
│ └─── ...
└─URN
  └─nbn
    └─de
      ├───0220
      │   └───gd
      │       │   GEI
      │       │
      │       ├───4064618
      │       │     │---metslink.url
      │       │     └---GEI-PPN647735415.xml
      │       │
      │       └───4302722
      │             │---metslink.url
      │             └---GEI-PPN647735415.xml
      │
      ├───bsz
      │   ├───14
      │   │   └───db
      │   │       │   SLUB
      │   │       │
      │   │       ├───id2635668113
      │   │       │   │---metslink.url
      │   │       │   └---SLUB-id2635668113.xml
      │   │       │
      │   │       ├───id3126487665
      │   │       │   │---metslink.url
      │   │       │   └---SLUB-id3126487665xml
      │   │       │
      │   │       └───id5125208791
      │   │           │---metslink.url
      │   │           └---SLUB-id5125208791.xml
      │   │
      │   ├───16
      │   │   └───diglit
      │   │       │   UB Heidelberg
      │   │       │
      │   │       ├───25289
      │   │       │   │---metslink.url
      │   │       │   └---UBHD-rueger1928.xml
      │   │       │
      │   │       ├───263077
      │   │       │   │---metslink.url
      │   │       │   └---UBHDkordenbusch1773.xml
      │   │       │
      │   │       └───62245
      │   │           │---metslink.url
      │   │           └---UBHD-lehm204.xml
      │   │
      │   ├───180
      │   │   └───digosi
      │   │       │   UBMA
      │   │       │
      │   │       ├───27
      │   │       │   │---metslink.url
      │   │       │   └---UBMA-59087.xml
      │   │       │
      │   │       └───30
      │   │           │---metslink.url
      │   │           └---UBMA-59088.xml
      │   │
      │   ├───21
      │   │   └───dt
      │   │       │   UBTÜ
      │   │       │
      │   │       ├───12014
      │   │       │   │---metslink.url
      │   │       │   └---UBTÜ-DkXI312_1.xml
      │   │       │
      │   │       ├───12079
      │   │       │   │---metslink.url
      │   │       │   └---UBTÜ-Eg14_fol_1.xml
      │   │       │
      │   │       ├───125273
      │   │       │   │---metslink.url
      │   │       │   └---UBTÜ-Bi211_fol-4_1.xml
      │   │       │
      │   │       ├───18290
      │   │       │   │---metslink.url
      │   │       │   └---UBTÜ-KeXXI21_1.xml
      │   │       │
      │   │       ├───19779
      │   │       │   │---metslink.url
      │   │       │   └---UBTÜ-Bd231_qt_2_1.xml
      │   │       │
      │   │       └───7969
      │   │           │---metslink.url
      │   │           └---UBTÜ-FoXXVIII9_qt_1.xml
      │   │
      │   └───31
      │       │   BLB-Karlsruhe
      │       │
      │       ├───103372
      │       │   │---BLB-4807107.xml
      │       │   └---metslink.url
      │       │
      │       ├───127413
      │       │   │---BLB-5654690.xml
      │       │   └---metslink.url
      │       │
      │       ├───1289
      │       │   │---BLB-19642.xml
      │       │   └---metslink.url
      │       │
      │       └───91552
      │           │---BLB-4314364.xml
      │           └---metslink.url
      │
      ├───bvb
      │   ├───12
      │   │   │   BSB
      │   │   │
      │   │   ├───bsb00001981
      │   │   │   └───0
      │   │   │       │---logbsb00001981.xml
      │   │   │       └---metslink.url
      │   │   │
      │   │   ├───bsb00053618
      │   │   │   └───3
      │   │   │       │---logbsb00053618.xml
      │   │   │       └---metslink.url
      │   │   │
      │   │   ├───bsb00107766
      │   │   │   └───4
      │   │   │       │---logbsb00107766.xml
      │   │   │       └---metslink.url
      │   │   │
      │   │   └───bsb00130104
      │   │       └───1
      │   │           │---logbsb00130104.xml
      │   │           └---metslink.url
      │   │
      │   ├───384
      │   │   │   UBA
      │   │   │
      │   │   ├───susba000004
      │   │   │   └───9
      │   │   │       │---metslink.url
      │   │   │       └---UBA-susba000004.xml
      │   │   │
      │   │   └───uba003384
      │   │       └───1
      │   │           │---metslink.url
      │   │           └---UBA-uba003384.xml
      │   │
      │   └───824
      │       └───cod
      │           │   UB Eichstätt-Ingonstadt
      │           │
      │           ├───sm
      │           │   └───1194
      │           │       └───1
      │           │            │---metslink.url
      │           │            └---UBEI-1194.xml
      │           │
      │           └───st
      │               └───56
      │                   └───2
      │                       │---metslink.url
      │                       └---UBEI-56.xml
      │
      └───gbv
          ├───3
          │   └───1
          │       │   gei-ULB
          │       │
          │       └───322827
          │           │---metslink.url
          │           └---ULB-PPN816659915.xml
          │
          └───601
              │   digishelf
              │
              ├───653
              │    │---DS-54962810x4.xml
              │    └---metslink.url
              │
              ├───88641
              │    │---DS-846778912.xml
              │    └---metslink.url
              │
              ├───90962
              │    │---DS-846805723.xml
              │    └---metslink.url
              │
              ├───93944
              │    │---DS-bsz443371393.xml
              │    └---metslink.url
              │
              └───94548
                   │---DS-bsz435423223.xml
                   └---metslink.url
```