# PyBer_Analysis

## Overview

As a data analyst for PyBer, a ride sharing app company, an exlporatory analysis was performed on the app's data to visualize the relationships between the city's number of drivers, number of riders, its total fares by city and type of area (urban, suburban, or rural). The purpose of this analysis was to create a summary dataframe of the ride-sharing data by city type and to visualize the total weekly fares for each city type as a multiple-line graph.

## Resources

Data sources: city_data.csv; ride_data.csv

Software: Python 3.7.6, Jupyter Notebooks

## PyBer Results

![img_1](https://github.com/jmasurovsky/PyBer_Analysis/blob/master/Analysis/PyBer_Summary_df.png)

Table 1. *PyBer Summary Datatable*

 - Urban areas had the greatest number of total rides with 1625 rides, while suburban areas had a total of 625 rides, and rural areas had a total number of 125 rides, the least number of rides.
 
 - Urban areas had the greatest number of total drivers around with 2405 drivers, while suburban areas had a total of 490 drivers, and rural areas had a total of 78 drivers.
 
 - The highest total fare was in urban areas with $39,854.38, suburban areas had a total fare of $19,356.33, and rural areas had a total fare of $4,327.93

 - Rural areas had the highest average fare per ride of $34.62 per ride, suburban areas saw $30.97 per ride, and urban areas saw $24.53 per ride.
 
 - Rural areas had the highest average fare per driver of $55.49 per driver, suburban areas saw $39.50 per driver, and urban areas saw $16.57 per driver.
 
Total rides, total drivers, and total fares saw a similar pattern of increasing numbers from rural, being smallest, to urban, being largest. Although, the inverse occurs with average fare per ride and per driver, rural areas had the highest numbers, while urban areas had the smallest. 

 - Total fares by city type line chart show that urban areas have the highest total fares on a weekly basis, while suburban sees less and rural areas see the least weekly (Figure 1). 

![img_2](https://github.com/jmasurovsky/PyBer_Analysis/blob/master/Analysis/PyBer_fare_summary.png)

Figure 1. *Total Fare by City Type*


## PyBer Summary

Some disparities in the results can be described by the distance in trips in rural areas are much greater than in suburban and in urban areas, in that both see shorter trips. This can explain the increase in fare per ride in rural areas, while being the lowest total fares as compared to in urban areas. Another disparity that could explain the spike in data, as seen in Figure 1, from a week before March due to the weather changing seasons, from Winter to Spring, thus increasing temperatures. Tdherefore, more people would be likely to travel outside moreoften, thus taking a greater number of trips. The ratio of total drivers to total rides is greater in urban areas than suburban and rural areas and could be explained by a larger population living urban areas.



