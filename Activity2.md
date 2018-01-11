Activity 2 - Seaspan Scheduling Visualization
=============================================

The design for this problem requires visualization of the sailing schedules showing the average load of each vessel. There should be options to toggle one or many of the 3 different routes which can be overlayed to show the vessels load/availability that span different routes and also options for changing the time period that is used to calculate the average load. 

We will assume there is recent and accurate load data available dating back several months or years.

## What

Data:

* Vessels: These are **items**.
* Schedule: This is the **item** made up of routes and sailing times.
* Routes: These are **categorical attributes** of a schedule.
* Departure and arrival (sailing) times: These are **cyclic** and **quantitative ordered attributes** of the schedule.
* Load for each sailing: **quantitative, sequential ordered attributes** of a vessel.

## Why

*Action: 
To Analyze -> consume -> discover
    - Tool will be presenting data to discover patterns and correlations between average load on route schedules. And the  

*Target:
To **correlate** many **attributes**
    - The user needs to derive a correlation between sailings and average load in order to adapt the schedule.
    
## How

