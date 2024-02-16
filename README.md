# PyBer_Analysis

## Overview of Analysis
In this challenge, V. Isualize tasks Omar and I with creating a summary of the dataset that will help us compare and contrast PyBer Ride data by City Type. With this summary, we will hopefully be able to draw profitable conclusions that will give the decision-makers in the company the ability to make educated decisions about the future of the company's services. 

## Results
By examining the PyBer Summary Dataframe, we see the following statistics:

- Rural cities have the fewest Total Rides, Drivers and Fares, while Urban cities have the most Total Rides, Drivers and Fares
- Rural cities have the greatest Average Fare per Ride and Average Fare per Driver, while Urban cities have the lowest Average Fare per Ride and Average Fare per Driver
- Suburban cities take 2nd place across the whole board

Furthermore, by examining the "Total Fare by City Type" line chart, we see that at any given point in time between Jan 2019 and Apr 2019, Rural cities have the lowest Total Fare, while Urban cities have the greatest total fare, and yet again, Suburban cities take 2nd place. 

- [PyBer Fare Summary](analysis/PyBer_fare_summary.png)

## Summary
1. Cut the number of drivers in Urban cities. Referencing the Summary Dataframe, in Urban cities, the Total number of Drivers outnumbered the Total number of Rides. Specifically, 800 drivers didn't even fulfill a single ride during the given time frame. No other city type shares this same characteristic. 

2. If the workload gets too heavy, look to hire more drivers in Rural cities. Opposite to our previous recommendation, Drivers in Rural cities completed almost 2 rides each, and let's note that each ride likely covers larger distances since we're in Rural Areas, and the Average Fare per Ride is the largest amongst our three groups.
 
3. Increase Fare prices in Urban cities. Urban cities have the lowest Average Fare per Ride, 
most likely because the rides cover smaller distances compared to Suburban and Rural cities. 
