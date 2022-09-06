## Table of Contents
- [Description of Data](#Description-of-Data)
    - [Company Summary](#Company-Summary)
    - [Characteristics of Businesses](#Characteristics-of-Businesses)
    - [Characteristics of Business Owners](#Characteristics-of-Business_Owners)
    - [Technology Characteristics of Businesses](#Technology-Characteristics-of-Businesses)
- [Analysis and Visualizations](#Analysis-and-Visualizations)
    - [ETL](#ETL)
    - [Census_NoteBook.ipynb](Census_NoteBook.ipynb)
    - [Project Report](#Project-Report)
- [Secondary Files](#Secondary-Files)
    - [names-list.csv](#names-list.csv)
    - [nst-est2019-01.xlsx](#nst-est2019-01.xlsx)
- [Configuration](#Configuration)

## Description of Data
The Census Bureau’s 2018 Annual Business Survey data analyses economic and demographic characteristics for businesses and business owners, nationwide. On the national-level, the data offers demographic breakdown related to sex, race, ethnicity, and veteran status. On the state- and national-level, the data provides economic, industry, and other business related factors, specific to that dataset. It is important to note that the data is based off of respondent surveys and is not a complete representation of the nation or state.  

### Company Summarycompany-summary
The Company Summary dataset provides general data about businesses by economic and demographic characteristics. Provides data for employer businesses by sector, sex, ethnicity, race, veteran status, years in business, receipts size of firm, and employment size of firm for the U.S., states, and metro areas. Data for counties and economic places are available for 2018.

### Characteristics of Businesses
The Characteristics of Businesses dataset provides data about employer firms by demographic and economic characteristics, such as years in business and size of firm. The firms/businesses are further categorized by their industry. Provides data for respondent employer firms by sector, sex, ethnicity, race, veteran status, years in business, receipts size of firm, and employment size of firm for the U.S., states, and metro areas, including detailed business characteristics. Data for counties and economic places are available for 2018.

### Characteristics of Business Owners
The Characteristics of Business Owners dataset provides data about owners of employer firms by economic and demographic characteristics, such as sex and ethnicity. Provides data for owners of respondent employer firms by sector, sex, ethnicity, race, and veteran status for the U.S., states, and metro areas, including detailed owner characteristics. Data for counties and economic places are available for 2018.

### Technology Characteristics of Businesses
The Technology Characteristics of Businesses dataset provides data about businesses and their level of usage for different technology, such as artificial intelligence or specialized equipment. Provides data on technology use and production for Artificial Intelligence, Cloud-Based Computing, Specialized Software, Robotics, and Specialized Equipment technologies data at the U.S and State level for 2018.


## Analysis and Visualizations
### ETL
“ETL” is a Jupyter Notebook that details the ordered steps taken to clean, transform, and merge the data using pandas. The notebook uses an API key that’s being pulled from the config.py file to call the Census API data. The steps should be followed in order and variable names should remain consistent. It is important that the secondary documents and config.py file with the API key are in the same directory and named as is when working through the ETL and code.

### Census_NoteBook.ipynb
“Census_NoteBook.ipynb” is a Jupyter Notebook with all code used for the project analysis and visual creation using pandas, matplotlib, and seaborn. As noted in the ETL, it is important that the secondary documents are in the same directory and named as is when working through the code. This notebook has descriptions and comments for context along the way but please refer to “Project Report” for deeper insight.

### Project Report
“Project Report” is a word document of our formal technical report that explains our research and findings. The report cites our sources, lists our initial questions, the analysis process, and our conclusions. The visuals made in “Census_NoteBook.ipynb” are the focal point of our analysis and conclusion. 


## Secondary Files

### names-list.csv
“names-list.csv” is a csv file with each state’s full name and their abbreviation. This is used for the merge in the ETL.

### nst-est2019-01.xlsx
“nst-est2019-01.xlsx” is an excel file from the census bureau with state and region population from 2010 to 2019. This is used for the merge in the ETL.