# PyBer_Analysis

## Overview of the Analysis

PyBer has collected a lot of data on the different cities it offers its ride share.  Each ride is collected and stored within the ride_data.csv and each city collects data and stored in the city_data.csv.  We were asked to combine this data to one DataFrame to find the total ries, total drivers, total fares, average fare per ride and average fare per driver all broken down by the different types of cities (urban, suburban and rural).  We will then look further in to the data to see how these different city types compare to each other and make recommendations.


## The Results

When the data was combined, we calculated a total of 2,375 total rides, split among Rural (125 rides), Suburban (625 rides) and Urban(1,625 rides).  There were a total of 2973 drivers, with 78 in Rural, 490 in Suburban and 2,405 in Urban.  The Rural type has the smallest rides, drivers, and fares; however, they had the highest average fare per ride and highest average fare per driver.  This is probably due to people in the rural areas traveling farther to get places than people in urban settings.  The Suburban was in the middle for total fares, but had the second highest average fare per ride and average fare per driver.  Even though Urban had the largest total fares (almost twice that of Suburban), it had the smallest average fare per ride and average fare per driver.  Again, this is probably due to people not needing to travel as far in a city (urban) setting.  
![table picture](ride_sharing_summary_table.png)

As we break down the total fares by city type, we cna start to see trends in rides from January 1, 2019 through April 29, 2019.  All three city types have a peak in fare at the end of February and then drop at the beginning of March, with rural and urban having a second spike around the beginning of April.  Urban has the most variation in their fares during January through April, with Rural being the most constant during that time.  Rural's fares start and end around the same price, while Suburban increases total fares about $500 during this time and Urban increases about $200 in total fares.  

![total fare by city type](https://github.com/JulieHock/PyBer_Analysis/blob/main/Analysis/PyBer_fare_summary.png)

## Summary

Although the Rural fares may have cost more on average, they did not generate as much money as the rides in the Urban and Suburban types.  There was only a $10 difference between average fare per ride between Urban and Rural, wihc means that Urban will still be more profitable.  Again, this is probably due to the large distance between places in the rural setting, that most people probably have their own ride to get places, where in the rural setting, people may not want a car or have a need for their own personal car.  Rural is also a much steadier fare, not much of a change in fare between January and April.  
