# Readme
This dataset was created for LIS 545: Data Curation I in the iSchool at the University of Washington in Winter Quarter 2022. The data set compares circulation data from four public library systems in the state of Washington based on city population size (100,000 – 249,000) in the 2019 fiscal year. The specific libraries compared were Tacoma Public Library, Everett Public Library, Spokane Public Library, and Yakima Valley Regional Library. The intended audience is researchers. This dataset is free available to the public.

The clean and compiled dataset is available in .csv format. The raw data have also been included, first as unstructured data from the IMLS.gov website generated in .pdf format in three files. Then, raw data were extracted from the PDFs as tables using Tablua version 1.2.1 and exported to .csv in three files. The three .csv files were manually compiled into one .csv file. Naming conventions for the variables in the dataset were chosen based on best practices as outlined by Library Carpentry (2016). No standardization of the data was required because all involved variables are on the same scale and have the same units. No variables have been duplicated and there are no null values. No further cleaning should be required for reuse.

## Table of Contents
- [Naming](#naming)
- [Data Dictionary](#datadictionary)
- [Metadata](#metadata)
- [Rights](#rights)
- [Contact](#contact)

## Naming
Naming for the files should be as follows:

      year_datasettype_Compare_Circ_librariesbeingcompared
      
Where: 

•	_year_ is the year of the data being reported

•	_datasettype_ indicates whether it is the raw data (i.e., Raw) or the normalized data (i.e., Clean)

•	_librariesbeingcompared_ is the combination of all included libraries (i.e., All) or two libraries being compared (e.g., WA0068_and_WA0051)

## Data Dictionary

| **Variable Label** | **Variable** | **Variable Type** | **Allowed Values** | **Definition** |
| --- | --- | --- | --- | --- |
| **Library** | Library name | String | Tacoma Public, Everett Public, Spokane Public, Yakima Valley Regional | Name of the library about which circulation data is being described. Each library is a public library in Washington State that serves a city with a population size ranging from 100,000 to 249,000 in 2019. |
| **Total_circ_transactions** | Total number of circulation transactions | Integer | N/A | The total number of circulation transactions for the specified public library system.  |
| **Physical_circ** | Number of physical material circulation transactions | Integer | N/A | The number of circulation transactions for the physical materials in the collection of the specified public library system. |
| **Electronic_circ** | Number of electronic material circulation transactions | Integer | N/A | The number of circulation transactions for the electronic materials in the collection of the specified public library system. |
| **Childrens_circ** | Number of children’s material circulation transactions | Integer | N/A | The number of circulation transactions for the children’s materials in the collection of the specified public library system. |
| **Childrens_as_percent_total** | Children’s material circulation transactions as a percent of total circulation | Integer | 0 - 100 | The percentage of circulation transactions for children’s materials as compared to the total number of circulation transactions for the specified public library system. |

## Metadata
Schema Used: Dublin Core

| **Attribute** | **Value** |
| --- | --- |
| accessRights | public |
| conformsTo | DCMIType |
| coverage | 2019 |
| created | 2022-03-05 |
| creator | Lyneea Kmail |
| date | 2022-03-06 |
| description | This dataset contains circulation data for four public libraries in cities of similar size in Washington state. It includes total transactions as well as data for physical, electronic, and children's material as reported during the 2019 fiscal year. The intended audience is researchers. This dataset was curated for LIS 545 at the University of Washington during the Winter Quarter of 2022. |
| format | csv |
| identifier | https://github.com/lkmail/compare_library_circulation_FY19/blob/main/2019_Clean_Compare_Circ_All.csv  |
| language | en-US |
| modified | 2022-03-07 |
| publisher | Lyneea Kmail |
| relation | https://github.com/lkmail/compare_library_circulation_FY19 |
| rights | https://creativecommons.org/publicdomain/zero/1.0/ |
| source | https://www.imls.gov/search-compare/ |
| subject | Library circulation analysis; Institute of Museum and Library Services (U.S.); Tacoma Public Library; Everett Public Library (Everett, Wash.); Spokane Public Library; Yakima Valley Regional Library |
| title | Comparing Circulation Data for 4 Washington State Public Libraries (2019) |
| type | Dataset |

## Rights

https://creativecommons.org/publicdomain/zero/1.0/

## Contact
Lyneea Kmail

lkmail@uw.edu
