# citibike Project

Tableau Analysis: [Go to Tableau Public](https://public.tableau.com/app/profile/eylem.yildirim/viz/citybikeproject_17400059229000/Story1?publish=yes)

<br>
For my analysis of Citi Bike data, I selected data from November 2024, December 2024, and January 2025. The goal of this project was to create a report that could assist city officials in publicizing and enhancing the Citi Bike program.
</br>

## Data Pre-Processing
- Data was collected from citybike public website: https://citibikenyc.com/system-data
- Jupyter Lab was used to gather the data from downloaded zip files. 
- Duplicates and null values we removed before exporting the output file to use in our analysis in Tableau. 
- Tableau was used to ignore some null values on the Dashboard charts and analysis
- Created multiple calculated fields to do help analyze different things such as 'Part of Week', 'Week Day', 'Number of Rides', 'Top 10 Rank by Rides', and more.

## Technologies Used: 
Tableau Desktop, Jupyter Lab, Python

## CityBike Map & Summary Stats
Dashboard control: 'Start Station Name'
Select station names to see the change on the Dashboard.
Dashboard control: 'Select Month'
Choose the month to see the change on Dashboard. 
Dashboard control: 'Total Rides by Station'
Select the number of rides segmented per station to see the stations that match the selected number on the map.
Dashboard control: 'Member Status'
Select the member status and see the update on the map.
Analysis
- November recorded the highest number of rides, while January had the fewest over the past three months. The decline in December and January aligns with colder weather conditions compared to November.
- Casual riders' average trip duration was 65% longer than that of members, likely due to tourists and visitors taking their time for sightseeing.

## Station ID Analysis
Dashboard control: 'Select Month'
Analysis
- The most preferred starting station for members over the past three months was Station ID 6140.05, located at W 21st St & 6th Ave.
- Six of the top starting locations for casual riders were clustered around Central Park, indicating a strong preference for scenic routes.
- Station ID 4953.08 at Front St & Pine St had the lowest number of rides, both as a starting and ending point. Management may consider further investigation into this location, as trends show that the least-used stations vary by month.

## Day of Week Analysis
Dashboard control: 'Select Month'
Analysis
- Ride activity peaked between 3 PM and 9 PM on weekdays, followed by 6 AM to 9 AM, aligning with work commute patterns. On weekends, peak hours shifted to 12 PM to 6 PM, reflecting tourist and visitor preferences.
- Friday, Saturday, and Sunday were the most popular days for casual riders, which aligns with increased tourist activity and locals taking advantage of pleasant weather.
- Casual riders took the longest trips on Saturdays and the shortest on Thursdays. The same trend applied to ride volume, with Saturday having the most rides and Thursday the fewest over the past three months.
- Members recorded the longest trip durations on Tuesdays and the shortest on Sundays. However, ride volume followed a slightly different pattern, with Thursday and Tuesday having the most rides, while Sunday had the least.

## Resources and Support
- ASU Bootcamp class activities
- ChatGPT
    Help with the LOD calculations, and fixes
- Linkedin Learning
