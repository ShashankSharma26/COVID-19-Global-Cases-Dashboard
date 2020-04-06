# Dataset

The data source can be accessed from the JHU CSSE's github repository with the link shared below.

https://github.com/CSSEGISandData/COVID-19
 
 The files used in the dashboard are:
 * time_series_covid19_confirmed_global.csv for confirmed cases
 * time_series_covid19_deaths_global.csv for global deaths
 * time_series_covid19_recovered_global.csv for global deaths
 
 All the files contain data in a wide format with an allocated column for each date per country. Hence, data shaping is done using Tableau Prep Builder to tranfrom the data into a long format. The entire process is explained in depth in the Tableau files folder. 
 
