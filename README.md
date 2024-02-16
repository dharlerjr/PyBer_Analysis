# PyBer_Analysis

## Overview of Analysis
In this challenge, we are analyzing ridesharing data for the Python-based ridesharing app company, Pyber. The CEO, V.Isualize, has tasked us with providing two deliverables: a table summary of the ridesharing dataset and a line chart of total fares by city type. With these deliverables, we will be able to draw profitable conclusions about that will drive decisions about the future of the company's services. 

## Results
By examining the PyBer Summary Dataframe, we see the following statistics:

- Rural cities have the fewest Total Rides, Drivers and Fares, while Urban cities have the most Total Rides, Drivers and Fares
- Rural cities have the greatest Average Fare per Ride and Average Fare per Driver, while Urban cities have the lowest Average Fare per Ride and Average Fare per Driver
- Suburban cities take 2nd place across the whole board  

![Ridesharing Summary](https://github.com/dharlerjr/PyBer_Analysis/blob/main/analysis/Fig8_City_Type_Summary.png)  

Furthermore, by examining the "Total Fare by City Type" line chart, we see that at any given point in time between Jan 2019 and Apr 2019, Rural cities have the lowest Total Fare, while Urban cities have the greatest total fare, and yet again, Suburban cities take 2nd place.  

![Total Fare by City Type](https://github.com/dharlerjr/PyBer_Analysis/blob/main/analysis/Fig9_PyBer_fare_summary.png)  

## Summary
1. Cut the number of drivers in Urban cities. Referencing the Summary Dataframe, in Urban cities, the Total number of Drivers outnumbered the Total number of Rides. Specifically, 800 drivers didn't even fulfill a single ride during the given time frame. No other city type shares this same characteristic. 

2. If the workload gets too heavy, look to hire more drivers in Rural cities. Opposite to our previous recommendation, Drivers in Rural cities completed almost 2 rides each, and let's note that each ride likely covers larger distances since we're in Rural Areas, and the Average Fare per Ride is the largest amongst our three groups.

3. Increase Fare prices in Urban cities. Urban cities have the lowest Average Fare per Ride, 
most likely because the rides cover smaller distances compared to Suburban and Rural cities. 
