# PyBer_Analysis

## Overview of Analysis

The CEO, V. Isualize, of PyBer, a ride sharing company has asked for help to analyze ride data for the time period of January 1, 2019 through April 28, 2019 in order to gain insights that can be used to guide business decisions.  Data on the type of city, number of rides, number of drivers, and fares have been provided to complete the analysis. 

## Results

Two files were provided; one of city data and one of ride data.  AFter merging the two files into a single dataframe I was able to calculate the total number of rides by city type, the total number of drivers by city type, the total fares by city type, the average fare by city type, and the average fare per drive by city type.  The results are presented in this table. 


|          |   Total Rides |   Total Drivers |   Total Fares |   Average Fare per Ride |   Average Fare per Driver |
|:---------|--------------:|----------------:|--------------:|------------------------:|--------------------------:|
| Rural    |        125    |           78    |     $4,327.93 |                  $34.62 |                    $55.49 |
| Suburban |        625    |          490    |    $19,356.33 |                  $30.97 |                    $39.50 |
| Urban    |       1625    |         2405    |    $39,854.38 |                  $24.53 |                    $16.57 |

As can be seen from the chart the total rides are higher in urban city types than in rural.  Total fares are higher as well in urban city types.  But, we also observe that the number of drivers in urban city types actually exceeds the number of rides taken and average fare per driver is considerably lower in urban cities than in suburban or rural cities.  Average fare per ride and average fare per driver is lowest in urban cities and highest in rural cities and this may be related to distance travelled though we don't have data on that.  

![PyBer Fare Summmary](https://github.com/hal1277/PyBer_Analysis_2/blob/250bcff8a31492dca81c09daf8209839f3294b0c/Analysis/PyBer_fare_summary.png)
https://github.com/hal1277/PyBer_Analysis_2/blob/250bcff8a31492dca81c09daf8209839f3294b0c/Analysis/PyBer_fare_summary.png


The chart summarizing total fares by city type over the time period January 1, 2019 to April 28, 2019 also shows that rural cities contribute less to total fares than urban or suburban cities.  Both urban and suburban cities showed a growth in fares from January to end of April.  All three city types showed a spike in the latter half of February.  In urban cities there was considerable variation week to week from the third week of February through to end of March.  

## Summary

The data analysis highlights some disparities between the different city types and action may need to be taken to address these.

1. The average fare per ride in rural cities is quite high especailly versus the urban city type.  This may be part of the reason that the number of rides is quite low.  I recommend exploring a program for users to combine their trip with another user looking to travel a simlilar path at a similar time so that costs can be reduced for each user.  Rural users may be finding the costs prohibitive which may be limiting growth in these areas.  

2. There are a lot of urban drivers versus suburban and rural drivers and the average fare per driver is quite low versus the other city types.  I recommend a vetting process for drivers and a cap on the number of drivers relative to the number of trips being booked.  This would increase the amount each driver can make.  This would also offer an opportunity for quality assurance by being more selective and incentivizing good drivers by making it easier for them to get more trips and earn more.  

3. All three cities saw a spike in the third week of February. And, urban cities had volatility through the month of March as well.  A plan should be developed for predicting spikes related to events/occcasions and addressing driver availability to manage the increased demand.  Further analysis should be done to understand why there was such volatility in the urban March data.  Given the large number of users in this group it's unexpected to see the numbers swing so much.  
