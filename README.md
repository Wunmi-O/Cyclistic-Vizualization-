# About the Cyclistic
In 2016, Cyclistic launched a successful bike-share offering. Since then, the program has grown to a fleet of 5,824 bicycles that are geotracked and locked into a network of 692 stations across Chicago. The bikes can be unlocked from one station and returned to any other station in the system anytime. Until now, Cyclistic’s marketing strategy relied on building general awareness and appealing to broad consumer segments. One approach that helped make these things possible was the flexibility of its pricing plans: single-ride passes, full-day passes, and annual memberships. Customers who purchase single-ride or full-day passes are referred to as casual riders. Customers who purchase annual memberships subscriptions are Cyclistic members.

## Scenario
You are a junior data analyst working in the marketing analyst team at Cyclistic, a bike-share company in Chicago. The director of marketing believes the company’s future success depends on maximizing the number of annual memberships. Therefore, your team wants to understand how casual riders and annual members use Cyclistic bikes differently. 

## About the Dataset
Dataset contained 11-month historical data containing columns like ride_id, rideable_type, started_at, ended_at, start_station_name, end_station_name, member_casual etc. Find <b><ins>[Dataset](https://www.kaggle.com/datasets/adewunmiolowu/cyclistic-bike-share?select=capstone2_1dayandless.csv)<b><ins><b>


## Cleaning and Transformation
First, cleaning and transformation had to be done on SQL. In order to present a workable dataset, I dealt with the following:
1. Null values
2. Duplicate rows
3. Outliers
The cleaned dataset was later imported into PowerBI for transformation. 
1. Breakdown of timestamp into Day, Month, Quarter, Year, Period of day
2. Calculate trip duration for each rides taken
3. Sort column 'Day' to follow its regular chronological order

## Vizualization 
In order to understand the usage pattern of casual customers and how they differ from members, it was first important to understand the split in the number of rides taken by each customer type during the period under review. Then, a further deep dive was done to understand the split across bike types and customer types over four(4) quarters. Moving forward, I analysed the number of rides taken by each customer type per day and how this is spread across the various bike types. Finally, it was important to understand the time factor- what is the average time duration spent by each customer type and what bike type are they spending their time mostly on?
Find <b><ins>[Interactive viz](https://app.powerbi.com/links/Wue5NMQXe3?ctid=ad42a34b-c7c7-4982-9dd1-d2875b8a8521&pbi_source=linkShare)<ins><b>
