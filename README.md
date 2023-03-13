# (Ford GoBike System Data - Exploration)
## by (Aristide FOTSO)


## Dataset

**DATASET**: Ford GoBike System Data
* This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.

**DATA WRANGLING STEPS**:
* Extract rows where 'member_birth_year' and 'member_gender' columns are not null
* Convert 'start_time', 'end_time' columns into datetime
* Convert 'member_birth_year', 'start_station_id', 'end_station_id' columns into integer
* Delete 'start_station_id', 'end_station_id' columns because they are not necessary
* Melt the start_time, end_time, 'start_station_name', 'end_station_name', 'start_station_latitude', 'end_station_latitude', 'start_station_longitude', 'end_station_longitude' columns to step, time, station_name, station_latitude, station_longitude columns
* Calculate duration between start_time and end_time



## Summary of Findings

> users in the old and midlife age groups spend more time on trip than other age groups
> users in the old and midlife age groups spend made more trips than other age groups
> trips are most often made on Tuesdays and Thursdays, between 07:00 am and 09:00 am, and between 03:00 pm and 05:00 pm
> Distribution of each of following properties: AgeGroup, member_gender, user_type,  trip duration
> the majority of users are subscribers, and belong to the midlife and old age groups
> users in the old and midlife age groups spend made more trips than other age groups, on Tuesdays and Thursdays, between 08:00 am and 10:00 am, and between 04:00 pm and 06:00 pm


## Key Insights for Presentation

> Relationship between number of trips, hours of day, days of week, age group, user type
> Relationship between trip duration, age group, gender user
