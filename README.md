# Pyber_Analysis

# Overview

As a new employee of Pyber, a ride sharing service, I have been working on an analysis of various datasets related to the company's recent performance. Each ride that the company's drivers administer is tracked in a central database and, after merging datasets, we have access to the following datapoints:

- City in which the ride took place
- Type of city (urban, suburban or rural)
- Data and time of ride
- Total fare for the ride
- Number of Pyber drivers for each city

My colleague, Omar, and I have been working on a series of DataFrame summaries of the data, along with creating some charts and figures. For our final assignment, we were tasked with developing a final DataFrame of the data, organized by the type of city. For each of the three types (urban, suburban or rural) we will provide:

- Total number of rides 
- Number of drivers
- Total fares
- Average fare per ride
- Average fare per driver

After the DataFrame was complete, we were asked to create a line chart that displayed total fare by each city type over a four month timeframe. This will allow management to get a clear understanding about the relative amount of revenue produced by each of the city types when compared to each other and how these revenues might change over time.

# Results

When we look at the overview of the data summary, it is perhaps not surprising that the rural drivers did not contribute a significant portion to Pybers profits in 2019. Rural areas had less drivers, less rides and only accounted for around seven percent of the annual profit. However, the averaeges tell a different story. Rural areas had the highest average fare, translating to very high per average figures. 

![multiple line chart](https://github.com/brianbutler08/Pyber_Analysis/blob/main/analysis/PyBer_fare_summary.png)

Total ride revenue from suburban drivers was only half that of the urban drivers, but that total was gained with only one fifth of the drivers that were operating in urban areas. The average fare per suburban ride was almost as high as in the rural areas, but the average per suburban driver was significntly lower tha rural.

Clearly the major driver of Pyber revenue in 2019 were urban drivers. Even though their average fare per ride and driver were comparatively low, the number of rides, drivers and total fare revenue were significant.

Looking at the multiple line chart that displays data for the first four months of the year, we come to a similar conclusion. The total urban fares are consistently the highest, day-to-day and week-to-week, followed by the suburban and then the rural fares. There are regular peaks and valleys for each city type, particularly in urban areas, perhaps relating to changes in ridership during the weekends.

![Final DataFrame](https://github.com/brianbutler08/Pyber_Analysis/blob/main/analysis/Final%20DataFrame.png)

# Summary

Based on the results of this analysis, there are three recommendations to make, one for each city type.

1. In rural areas, there is potentially an opportunity to explore adding capacity and expanding the number of drivers that are available. The high average fare prices indicate that, with additional drivers, there could be significant amounts of money to be made. This will require some additional research, however, because adding more drivers than the market can suppot would cost Pyber in the long run. The high average trip fares suggest that the trips in rural areas are longer and providing more long rides could be profitable to the drivers and the company. I am suggesting two additional analyses to gain some clarity of the situation - looking at average ride length in rural areas and the number of rides that were requested by customers, but unable to be fulfilled by Pyber because of a lack of drivers.

2. The opposite approach may need to be taken with urban drivers. The data may suggest that there are too many drivers operating in urban areas. A total of just 1,625 rides from a whopping 2,405 drivers is not a good ratio. The average fare per driver is likely so low that it may not be sustainable in the long run. If drivers feel that their arrangement with Pyber is not beneficial enough, they could conceivable leave, leading to high turnover and experienced drivers heading to rival companies. It may be best to not bring on any new urban drivers and allow some to leave in order to restore some balance.

3. On the surface, the surburban market appears have a healthy balance of drivers to rides. However, I would recommend further analysis to answer some questions that could better help Pyber understand the market. How satisfied are the suburban drivers with their average earnings per ride? What is the impact of weekends/weekdays/time of day on ridership? Or the Summer? What are the generally distances of rides in the suburbs? What is the demographic profile of a typical suburban rider (and could we market directly to them in order to increase ridership)? Because the surburban ride share situation is less black and white, conducting some additional research could be enormously beneficial.
