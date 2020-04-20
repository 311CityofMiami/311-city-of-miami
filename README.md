# 311 City of Miami

This repository contains scripts for working with the City of Miami's 311
Response Data. You can acquire an up-to-date copy of the data [here](https://opendata.miamidade.gov/311/311-Service-Requests-Miami-Dade-County/dj6j-qg5t/data).

#Data folder includes the immediate data we used for the analysis. From the CENSUS https://www.census.gov/data/developers/guidance/api-user-guide.html we filtered only relevant data for the City of Miami, then transformed the data value to percentage by dividing each value with the maximum value of the attribute. From the Miami-Dade County data, we cleaned and transformed each data element so that it can fit to the clustering algorithm we implemented: we transformed service request types and their frequencies in each tract to a vector in order to represent the primary reasons for service requests in the tract. City of Miami data here is the formatted data after the normalization process.  
