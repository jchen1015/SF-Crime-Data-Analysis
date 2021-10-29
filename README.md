# San-Francisco-Crime-Data-Analysis

In this San Francisco crime data analysis from 2013 to 2018, I generated insight from data in San Francisco Police website which including category, date, districts, and location to help us identify the specific place in Seattle by using Spark, Spark SQL, and Pandas. In the process of data visualization, I used python package Matplotlib and Seaborn. In this project, I realized that the speed of loading dataset and data manipulation using Spark is much faster than using Python Pandas.  

In this notebook, I use Spark SQL an python for big data online analytical processing (OLAP) on San Francisco crime data. Data is from https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-Historical-2003/tmnf-yvry.  

## Steps of OLAP
- Count the number of crimes for different category and visulize the result
- Analyze the number of crime in each month from 2003 to 2017 (the data does not cover whole year of 2018)
- Travel Suggestions with respect to the hour in certian day
- Count the number of crimes for different district and apply spatial distribtion with longitude and latitude information to visualize the result

## Discover in SF Crime Dataset

Based on what I discover in this dataset, 
- The most crime category is larceny/theft which is more than 478 thousand.  
- The most dangarous district in SF is the Southern district.   
- Accounting to the spatial distribution, we see that most of the crimes are at the north eastern part of SF and now this area has expanded a bit toward the weat and south part of SF.  
- With the time series distribution, it shows the number of crimes do not decrease in these years. 

## Suggestions for Travelers. 
- If you would like to travel SF, I would suggest that you visit in February which has the least crime of the year, also do not visit the north eastern part of SF to reduce the incidence of criminals.   
- If you plan to visit downtown commerical area, I suggest you to visit at the morning instead of afternoon since criminal rate is lower in morning than afternoon.  
