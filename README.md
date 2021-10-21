# PyBer Analysis

***Version 1.0.0***

---

## Overview of Pyber Analysis
#### Pyber is a company that offer rides in different cities, I was hired to develop an analysis on the fares mainly by type of city. I was given with two main .csv files which they had the bike rides by city and the fare by ride id.

The main goal was to merge those two sets of data and develop an analysis with the following requests.

1. Ride summary DataFrame with the columns of total rides, drivers, fares and the fare averages by ride and driver
2. A Pivot Table with the split of fares by type and with a date index filtered for the months of Jan-Apr of 2019
3. A line chart with the output of the pivot table.

## Analysis results:
#### Here I'll list the results of the analysis for each request:

- Ride summary DataFrame with the columns of total rides, drivers, fares and the fare averages by ride and driver.
  -  In the following image we can see the output of merging both files and grouping by type of city the rides and drivers. What we can see here is that even that Urban type of city has more than 13 times the rides has less fare by ride and almost 4 times less fare by driver
  
  <img src="https://github.com/SeRoGaTa/PyBer_Analysis/blob/main/images/ride_summary_df.png" width="800">
  
- A Pivot Table with the split of fares by type and with a date index filtered for the months of Jan-Apr of 2019.
  -  As we can see in the image below, using the Pivot table summarizing the fares by week and divide it by type of city, we can remove the NaNs of all the rows and is a better way to see the data in a clear way.

  <img src="https://github.com/SeRoGaTa/PyBer_Analysis/blob/main/images/ride_fares_summary_df.png" width="300">

- A line chart with the output of the pivot table.
  -  And lastly on this line chart we can see better how is the behavior of the data, we can easily compare between the city types and also between the dates in a simpler matter, mostly we can see here the same behavior for all type of cities and you can start seeing some trendings.

  <img src="https://github.com/SeRoGaTa/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png" width="900">
  
## Summary
#### In summary, this simple analysis helped us see the data in an easy way like grouped tables, pivot queries and line charts, with all these request I can give you 3 mayor insights of the data so you can take quicker and better desitions in the future.
  - Ovbiosly we can see that the urban rides have more overall output, but on the summary we can see that in average, they had less fare by ride and also the drivers spent less than other types of city. This means you can implement strategies like carpools or take two users per ride so you can increase the output with the same amount of vehicles without needing to increase the tariffs
  - Other insight I have is that you have less rides and drivers in the rural type of city but you have good outcome of it, you can implement tariff reduction so you can increase the rides.
  - And lastly, on the chart shown before, you can see mostly the same behavior for all the city types but rural and suburban types are more stady so you can implement different strategies on those places and you will have a more certain output rather than implement in the urban type which is a bit more caotic and you can missunderstand the output of the strategies.
  - As a bonus, you can see an increase in the trend of the suburban type of cities so, it's better to focus on this type of cities to grown the busines.

#### You can locate the complete analysis code on the following link [PyBer_Challenge](https://github.com/SeRoGaTa/PyBer_Analysis/blob/main/PyBer_Challenge.ipynb) and all image used in the following folders [Images](https://github.com/SeRoGaTa/PyBer_Analysis/tree/main/images) [Analysis](https://github.com/SeRoGaTa/PyBer_Analysis/tree/main/analysis)

#### If you want to give a look to the data sets, see this folder [Resources](https://github.com/SeRoGaTa/PyBer_Analysis/tree/main/Resources)

