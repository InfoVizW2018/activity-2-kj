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

A schedule view with day of the week on the x axis and time of day on the y axis. Sailings would be represented by a block in the calendar colored with one of the 3 colors used in the example schedule: pink for Tillbury-Nanaimo, green for Surry-Duke Pt. and yellow for Tillbury-Swartz Bay. The colored bar (sailing) is then filled partially (or fully) representing the load. Interactive tools (toggles or buttons) would filter the visualization according to vessel, route and time span used for calculating the average load for that sailing.

This representation allows the viewer to discover correlated data and filter to the desired items and attribute in order to successfully discover overlaps and construct a new schedule. Manual control over the schedule has not been addressed fully, but with the information available, a edit feature could be added for the user to add and remove sailings and be able to visualize how they would fit into the current live schedule. 
