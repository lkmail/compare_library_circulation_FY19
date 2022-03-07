# Readme
This dataset was created for LIS 545: Data Curation I in the iSchool at the University of Washington in Winter Quarter 2022. The data set compares circulation data from four public library systems in the state of Washington based on city population size (100,000 – 249,000) in the 2019 fiscal year. The specific libraries compared were Tacoma Public Library, Everett Public Library, Spokane Public Library, and Yakima Valley Regional Library. The intended audience is researchers. This dataset is free available to the public.

The clean and compiled dataset is available in .csv format. The raw data have also been included, first as unstructured data from the IMLS.gov website generated in .pdf format in three files. Then, raw data were extracted from the PDFs as tables using Tablua version 1.2.1 and exported to .csv in three files. The three .csv files were manually compiled into one .csv file. Naming conventions for the variables in the dataset were chosen based on best practices as outlined by Library Carpentry (2016). No standardization of the data was required because all involved variables are on the same scale and have the same units. No variables have been duplicated and there are no null values. No further cleaning should be required for reuse.

## Table of Contents
- [Naming](#naming)
- [Data Dictionary](#datadictionary)
- [Metadata](#metadata)
- [Security](#security)
- [Contact](#contact)

## Naming
Naming for the files should be as follows:

      year_datasettype_Compare_Circ_librariesbeingcompared
      
Where: 

•	year is the year of the data being reported

•	datasettype indicates whether it is the raw data (i.e., Raw) or the normalized data (i.e., Clean)

•	librariesbeingcompared is the combination of all included libraries (i.e., All) or two libraries being compared (e.g., WA0068 and WA 0051)
