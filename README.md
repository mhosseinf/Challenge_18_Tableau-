# Challenge_18_Tableau-
I compiled the information from the Citi Bike Trip History Logs, encompassing the Citi Bike data for New York City during the periods of January to March 2023 and July to September 2023. A portion of each month was combined and concatenated, resulting in a larger file comprising 960,320 rows. here are the two unexpected Phenomenon that I found out. there were more than two but I only explained two mentioned below:

##1. Unexpected Phenomenon: Shift in User Type Proportions

Observation:
There is a noticeable shift in user type proportions over time, with unexpected changes in the proportions of short-term customers and annual subscribers. The proportions increase from January to March, decrease from March to July, and shift again from July to September.

User Type Proportions Analysis:

January to March:
Increase in short-term customers.
March to July:
Decrease in short-term customers.
July to September:
Decrease in short-term customers and increase in annual subscribers.
Hypothesis:
External factors such as changes in subscription plans, pricing structures, or marketing strategies may be influencing these shifts in user type proportions.

Investigation Steps:

Review External Factors:

Investigate changes in subscription plans, pricing structures, or marketing strategies during the identified periods.
Check for any promotional events or campaigns that might have influenced user sign-up patterns.
User Feedback Analysis:

Review customer feedback or surveys during these periods.
Analyze social media channels or customer support data for indications of user reactions to changes.
Collaborate with the Marketing Team:

Collaborate with the marketing team to gain insights into any targeted efforts or campaigns that might have contributed to the observed changes.
2. Deeper Analysis: Understanding Variances in Average Trip Duration

Observation:
There is a significant difference in average trip duration between casual and member users. Casual users exhibit an average trip duration of 1642.97 seconds, almost double the average trip duration of members at 782.83 seconds.

Trip Duration Analysis:

Casual Users:

Average Trip Duration: 1642.97 seconds.
Member Users:

Average Trip Duration: 782.83 seconds.

Hypothesis:
The substantial disparity in average trip duration may indicate distinct usage patterns, with casual users opting for longer rides, possibly for leisure or exploration.



Temporal Analysis:
To examine the data to identify distinct peak hours during the summer and winter months and Highlight specific times of the day when the difference in average trip duration between casual and member users is most pronounced, two line charts provided that illustrate while the majority of trips occur around 17:00, trips with the longest durations predominantly take place during the midnight hours.

Geospatial Analysis:
Examine the geographical distribution of trip durations to identify if certain locations are more popular among casual users for longer rides.
Visualisation Enhancement:

Create Box Plots:
A box plot was generated to show the distribution of trip durations for casual and member users and no out layer exists.

Conclusion:
Combining these analyses provides a holistic understanding of user behaviour. The unexpected shifts in user type proportions may be linked to external factors, while the variance in average trip duration underscores the need to tailor services for different user preferences.


##Unexpected Phenomenon: Spatial Discrepancy in Starting and Ending Stations
Observation:
An unexpected phenomenon is observed in the geographical distribution of starting and ending stations for bike journeys. While certain stations appear frequently in the top 10 for both starting and ending trips, there is a noticeable discrepancy in station popularity.

Spatial Analysis:

Top 10 Starting Stations:

8 Ave & W 16 St- 7250 trips
Broadway & E 21 St-5458 trips
Central Park S & 6 Ave- 4576 trips
W 4 St & 7 Ave S-4455 trips
1 Ave & E 16 St-4305 trips
Lafayette St & Jersey St-4094 trips
West St & Chambers St-4023 trips
Ave A & E 14 St-4022 trips
Allen St & Stanton St-3824 trips
6 Ave & W 33 St-3764 trips

Top 10 Ending Stations:
W 21 St & 6 Ave-8685 trips
W 31 St & 7 Ave-5700 trips
W 20 St & 10 Ave-5634 trips
8 Ave & W 33 St- 4617 trips
North Moore St & Greenwich St-4300 trips
W 25 St & 6 Ave-4082 trips
E 16 St & 5 Ave-3705 trips
6 Ave & W 34 St-3522 trips
Norfolk St & Broome St-3494 trips
11 Ave & W 41 St- 3412 trips
Bottom 10 Starting Stations:
Several stations with only one trip recorded, including Baldwin at Montgomery, Washington St, Hudson St & 4 St, Adams St & 12 St, Adams St & 11 St, City Hall, Communipaw & Berry Lane, Dey St, 9 St HBLR - Jackson St & 8 St, and 8 St & Washington St.

Bottom 10 Ending Stations:
Similar to the starting stations, the bottom 10 for ending trips include stations with only one recorded trip, such as 99 St & 50 Ave, Oakland Ave, 76 St & 45 Ave, South Waterfront Walkway - Sinatra Dr & 1 St, Journal Square, Bergen Ave & Stegman St, Newport Pkwy, York St & Marin Blvd, 2 St & Park Ave, and Hilltop.

Hypothesis:
The unexpected spatial variation in station popularity may be influenced by factors such as infrastructure development, neighbourhood preferences, or promotional campaigns targeted at specific areas.

Investigation Steps:

Neighbourhood Demographics:
Examine the demographics of neighbourhoods surrounding popular and less-used stations to identify patterns or preferences.

Infrastructure Development:
Investigate if there were recent developments or changes in infrastructure, such as the addition of bike lanes, around the popular stations.

Promotional Campaigns:
Collaborate with the marketing team to understand if there were targeted promotional campaigns in certain areas that might have influenced station popularity.

Conclusion:
The unexpected spatial phenomenon in station popularity highlights the need for a localized approach to bike-sharing services. Understanding the dynamics of station preferences can help optimize bike distribution and improve overall user experience.



Link to map:
https://public.tableau.com/views/Citibike_17008719717660/DynamicmapfromJantoSept23?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link

Dashboard 1:to Analyse shift in user type proportions
https://public.tableau.com/views/Citibike_17008719717660/ShiftinUserTypeProportions?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link

Dashboard 2:Spatial Discrepancy in Starting and Ending Journeys Stations

https://public.tableau.com/views/Citibike_17008719717660/SpatialDiscrepancyinStartingandEndingStations?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link


Story:Spatial Discrepancy in Bike Starting and Ending Stations

https://public.tableau.com/views/Citibike_17008719717660/SpatialDiscrepancyinBikeStartingandEndingStations?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link
