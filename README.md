# PyBer_Analysis
## Overview
I have created a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, I have created a multiple-line graph that shows the total weekly fares for each city type. This report summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

## Purpose
Analyze two separate datasets - ride_data( containing location, date and fare for each ride) and city_data (containing city,drivers,city type). Provide tables and charts to show how the data differs between city types. 

## Resources
  - Jupyter Notebook
  - Python 3.7.6
  - Dependencies
      - Python Pandas library
      - Python Numpy library
      - Python MatPlotLib library
  - Raw data
      - city_data.csv
      - ride_data.csv

## Requirements

1. Create a summary DataFrame of the ride-sharing data by city type. 
2. Using Pandas and Matplotlib, create a multiple-line graph that shows the total weekly fares for each city type.
3. Create a chart reflecting how the data differs by city type.

## Results
<p>

As shown in the DataFrame,
- Urban locations have a greater number of rides but Average Fare per ride is less than Rural locations.
- In Urban locations, the total fares are higher than Suburban and Rural locations.
- In Urban locations, the Average Fare per driver is less as compared to Rural locations.

![image](https://user-images.githubusercontent.com/95661802/150664990-f8f5b48d-8063-44a6-814d-6fdb17e1c5ed.png)

  
In the Multiple line chart,
 - This chart reflects "Total fare by city type" within the timeframe of January 2019 to April 2019.
 - PyBer has more total fares and profits in urban cities than in suburban and rural cities.
 - All city types experienced a decrease in total fares in the latter part of February until March 1. 

![image](https://user-images.githubusercontent.com/95661802/150665171-bf521677-4112-4e31-9210-c716928cb90e.png)


## Summary

- Consider adjusting (decreasing) rates to encourage more rural rides. 
- Increase rates in urban cities to offset decreased rates in rural cities.
- More investigation is required to determine what may have caused the drop in rides across all city types in late February. 
