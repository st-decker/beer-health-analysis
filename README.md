# Beer and Health Analysis

## Description:

NSS capstone project analyzing how the number of breweries and nationwide health statistics correlate together.

## Objective:

 Analyze brewery data against health indicators. Brewery data comes from BreweryDB+IBk-s API and the data is based on a state and city locality. Health data comes from County Health Rankings and the data is based on a county level. Both data sets have supplementary data added in from the US Census. This data is a mapping of U.S. regions and divisions against states. To be able to create a table with the health indicators and breweries, we need a crosswalk. Every location is also mapped with an FIPS code, which is a US Census geographic tool used to help describe counties. 

## Questions:

 We want to see where breweries are located across the continental United States. Furthermore, we would like to extract what the area around a brewery looks like and, specifically, we are trying to find correlations/relationships between the number of breweries and various health data within the same locality. Health measures include adult smoking, adult obesity, median household income, etc. 

## Tools:

 The language used to complete this task was Python. To strengthen the visual aspect of the project, Seaborn, Folium, and Matplotlib were also utilized. 
 In order to gain access to BreweryDB's API data, a key, of course, is needed. However, this key must be purchased. They do have a small free sandbox environment to test on. The sandbox environment provides extremely limited data. Even the 200/day request limit of the paid version cuts out some data. 

## Data and supplementary resources:
 
- Simplemaps: used to gather FIPS codes across counties
- BreweryDB: Brewery data
- US Census: Regional/Division mapping
- County Health Rankings: County level health data

## Notebooks:

- beer-analysis: mapping of breweries across the Us
- beer-import: Code to bring in information from BreweryDB
- dry-wet: can be ignored. Primary idea for mapping which counties are dry and wet across the us
- health-analysis: code to clean county health info
- merging: most of the analysis resides here. It both merges and goes through the analysis

