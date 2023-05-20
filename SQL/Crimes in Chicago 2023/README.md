# Crimes in Chicago (January 2023 - May 2023)

This repository contains a data analysis project focused on crimes in Chicago during the period of January 2023 to May 2023. The project aims to provide insights and answers to various questions using the available data.

## Files

- `Crimes_-_2023.csv`: This CSV file contains the crime data that will be used for the analysis.
- `Census_Data_-_Selected_socioeconomic_indicators_in_Chicago__2008___2012.csv`: This CSV file contains the socioeconomic data related to Chicago, which will be used in conjunction with the crime data.
- `chicago_crimes.db`: This database file contains the structured data used for analysis.
- `Crimes in Chicago.ipynb`: This Jupyter notebook documents the data analysis process for crimes in Chicago.
- `Data Wrangling.ipynb`: This Jupyter notebook documents the data wrangling process for crimes in Chicago.

## Questions

The data analysis project aims to answer several questions, including but not limited to:
1. Find the total number of crimes recorded in the CRIME table.
2. List community areas with per capita income less than 11000.
3. List all case numbers for crimes involving minors?(children are not considered minors for the purposes of crime analysis)
4. List all kidnapping crimes involving a child?
5. What kind of crimes were recorded at schools?
6. List the average safety score for all types of schools.
7. List 5 community areas with highest % of households below poverty line.
8. Which community area(number) is most crime prone?
9. Use a sub-query to find the name of the community area with the highest hardship index.
10. Use a sub-query to determine the Community Area Name with most number of crimes?

## Tools Used

The data analysis project primarily utilizes SQL for data querying and analysis. Additionally, Python, specifically the Pandas library, is used for data cleaning, CSV parsing, and SQL data insertion.