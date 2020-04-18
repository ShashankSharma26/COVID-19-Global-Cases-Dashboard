# Data Shaping using Tableau Prep Builder

Tableau Prep Builder was used to clean, pivot and join the three data sources for confirmed, recovered and deaths.  The entire flow of transforming the data is shown below.

![](../images/Data%20Cleaning%20Flow.png)

The main purpose of the above transformation is to convert the data from a wide format to a long format with a cumulative sum of cases for each country for each date. The transformed dataset is saved in a hyper format which is a Tableau's in-memory data engine technology to optimize data ingestion. This hyper file is uploaded to Tableau desktop to analyse the data and design the dashboard. 


