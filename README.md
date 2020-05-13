# MIT-COVID19-DATATHON
This repository contains our data analysis to answer the research question - How do various community locations, types of businesses, and types of events vary in terms of COVID-19 transmission risk?

# Research Questions Addressed
* Which businesses are super-spreaders? 
* How do these super-spreader businesses differ in visits, length of visits, and/or density in hot-spot states vs. non-hot-spot states?

# Datasets
* [John Hopkins University Dataset for COVID 19](https://github.com/CSSEGISandData/COVID-19) - (For Confirmed, cases and Deaths) 
* [SafeGraph](https://www.safegraph.com/covid-19-data-consortium) - (To get Foot Traffic in businesses across industries)
* [NAICS](https://www.naics.com/search/) - (to map business codes to businesses and industries)

# Requirements 
[Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/)

# Exploratory Analysis 
* Analsysis in Big Query - [Public Datasts on BigQuery](https://cloud.google.com/bigquery/public-data) - covid19_e

` SELECT * 
  FROM bigquery-public-data.covid19_ecdc.covid_19_geographic_distribution_worldwide
    where ( date >= '2020-01-01')`
    
 
![COVID 19 cases worldwide](https://github.com/manvimadan12/MIT-COVID19-DATATHON/blob/master/Screenshot%20from%202020-05-12%2018-44-20.png)
    
    

# Results


# References
* https://www.nytimes.com/interactive/2020/05/06/opinion/coronavirus-us-reopen.html


# Team 

## Core Team
* Ashley O'Donoghue ( Project Manager )  
* Whitney P
* Manvi Madan
* Michael Boals
* Tenzin
* Dr Garba Moussa

## Mentors
* Alok Thakkar
* Frank DeFalco
