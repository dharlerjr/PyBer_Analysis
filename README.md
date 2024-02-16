# PyBer_Analysis

## Overview of Analysis
In this challenge, we are analyzing ridesharing data for the Python-based ridesharing app company, Pyber. The CEO, V.Isualize, has tasked us with providing two deliverables: a table summary of the ridesharing dataset and a line chart of total fares by city type. With these deliverables, we will be able to draw profitable conclusions about that will drive decisions about the future of the company's services. 

## Results
By examining the PyBer Summary Dataframe, we see the following statistics:

- Rural cities have the fewest total rides, drivers and fares, while urban cities have the most total rides, drivers and fares
- Rural cities have the greatest average fare per ride and average fare per driver, while urban cities have the lowest average fare per ride and average fare per driver
- Suburban cities take 2nd place across the board  

![Ridesharing Summary](https://github.com/dharlerjr/PyBer_Analysis/blob/main/analysis/Fig8_City_Type_Summary.png)  

Furthermore, by examining the "Total Fare by City Type" line chart, we see that at any given point in time between Jan 2019 and Apr 2019, rural cities have the lowest total fare, urban cities have the greatest total fare, and yet again, suburban cities take 2nd place.  

![Total Fare by City Type](https://github.com/dharlerjr/PyBer_Analysis/blob/main/analysis/Fig9_PyBer_fare_summary.png)  

## Summary
Based on our results, here are three recommendations to address the disparities among city types:
1. Cut the number of drivers in urban cities. Referencing the Summary Dataframe, in urban cities, the total number of drivers outnumbered the total number of rides. Specifically, 800 drivers didn't fulfill a single ride during the given time frame. No other city type shares this same characteristic. 

2. If the workload gets too heavy, look to hire more drivers in rural cities. Opposite to our previous recommendation, drivers in rural cities completed almost two rides each. Furthermore, the average fare per ride is the greatest in rural cities; thus, as long as there is demand, rural drivers are the most efficient investment for PyBer.

3. Increase Fare prices in Urban cities. Urban cities have the lowest average fare per ride, yet more than half of the total rides occur in urban cities. While increasing prices may discourage customers from riding, PyBer would stand to signficantly increase its revenue.
