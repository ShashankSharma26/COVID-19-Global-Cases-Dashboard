# Data Shaping using Tableau Prep Builder

Tableau Prep Builder was used to clean, pivot and join the three data sources for confirmed, recovered and deaths.  The entire flow of transforming the data is shown below.

![](images/Data%20Cleaning%20Flow.png)

The main puprose of the above transformation is to convert the data from a wide format to a long format with a cumulative sum of cases for each country for each date.  The transformed dataset is saved in a hyper format which is a Tableau's in-memory data engined technology to optinize data ingestion. 


# Dashboard using Tableau Desktop

The purpose and features of each visualisation in the dashboard is explained below:

## 1. 'View data for' Radiobutton

![](images/radiobutton.png)

Purpose: Controls the type of data (Confirmed Cases, deaths, active, recovery) visualised on the main page of the dashboard.

Feature: Being a radiobutton, only one selection is possible at a time which allows an in depth analysis for each type of case.

## 2. List of Countries

![](images/Country%20list.png)

Purpose: Displays the total cases till date in a descending order for each country. 'Total' shows the cumulative global cases.

Features: 
* Click to view country data: Clicking on any country in the list updates the data for that particular country on all the visualisations in the dashboard. 
* Switch back to global data: Cicking on 'Total' switches back the dashboard to the default state displaying gloabl data.

## 3. Interactive Map












