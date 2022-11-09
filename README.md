# PyBer Analysis
## Overview of the analysis:
- The purpose of this analysis is to summarize the ride-sharing data by aggregating the data into “Total Rides”, “Total Drivers”, “Total Fares”, “Average Fare per Ride” and “Average Fare per Driver” for each city type.  City types consist of “Rural”, “Suburban”, and “Urban” cities.  This will help give us a clearer understanding of how the cost of fares compares for each city type.
- To finalize the analysis, a line chart will show the weekly total fares by city type.  This will help visualize the sum total of “weekly fares”  that can be compared to the “average fares” in the first summary.

## Results:
As one would expect, the total number of rides and drivers is higher in the “Urban” city type compared to the Suburban and Rural city types.   We can also see that the “Total Fares” is also the highest for “Urban” cities, but the “Average Fare per Ride” and “Average Fare per Driver” are the lowest for this city type.  

The Lowest “Average Fare per Ride” in “Urban” areas and the highest “Average Fare per Ride” in “Rural” areas shows a ~$10.00 discrepancy with $24.53 and $34.62 respectively however, there is a $38.92 discrepancy between the lowest “Average Fare per Driver” for “Urban” cities and the lowest “Average Fare per Driver” in “Rural” Cities.

![This is an image](/analysis/summary.JPG)

The $10.00 difference between the “Average Fare per Ride” in “Urban” cities and “Rural” cities may be due to the difference in the total number of rides with “Urban” cities with 1,625 rides and “Rural” cities with just 125 rides.  The “Average Fare per Ride” may decrease for “Rural” cities over time as the number of “Total Rides” increases. This seems to be consistent with “Suburban” cities that have an “Average Fare per Ride” at $30.97 with 625 “Total Rides”.

For “Urban” cities, the number of “Total Drivers” of 2405 far exceeds the number of “Total Rides” of 1625 which is about 1.5 times more drivers than rides while “Rural” and “Suburban” areas have less drivers than rides at a ratio of 0.64 and 0.78 respectively. The higher number of drivers compared to the number of rides suggests that "inactive" drivers are not being reported.  

Additionally, for “Urban” cities, the “Average Fare per Driver” is less than the “Average Fare per Ride” which is not the case for “Rural” and “Suburban” cities. The low “Average Fare per Driver” in "Urban" cities could be, in part, due to high competition between drivers which drives the rates down and the higher fares for drivers in "Rural" cities due to less competion.  The number of drivers being higher than the number of rides in "Urban" cities is impossible unless drivers are teaming up for rides, which is unlikely, or there a number of inactive drivers which is skewing  the fare averages per driver.

The “Total Fare by City Type” chart shows the discrepancy of weekly fares.  We can see that the weekly fares are the highest for “Urban” cites despite having the lowest fare averages for rides and drivers.  This is most certainly due to the total number of rides where the more rides there are, the more money you make.  We can also see that each “City Type” has fairly consistent weekly fares where “Rural” types stay under $500.00,  “Suburban” types are between $750 and $1400 approximately and “Urban” types are between $1700 and $2500.  

![This is an image](/analysis/PyBer_fare_summary.png)

## Summary:
After my analysis, my reccomendations are as follow:

1.	Account for “inactive” drivers which may be skewing the average fare for drivers.
2.	Decrease the number of drivers in Urban cities to be more proportional to the number of rides. 
3.	Increase the number of drivers in Rural cities which should increase competition which will lower the average fare per ride and which may increase the number of rides since lower rates will appeal to more customers.

