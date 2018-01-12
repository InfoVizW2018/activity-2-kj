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

## Design Study Methodology
* **Learn**:
Absorb the current information visualization literature, best practices, and guidelines from academia and industry.
* **Winnow**:
Establish a broad range of meeting with SEASPAN to identify the most promising collaborations. The actual users of the tool, the ferry schedule managers, would be met with.to start. During the initial meetings, time commitment, data availability, and problem definition would be discussed.
* **Cast**: 
Front-line analyst would be the domain expert end user and the gate keeper would be the stakeholders. Other additional roles should be considered such as Connectors, Translators, and Co-authors.
* **Discover**:
Characterize the problem and develop requirements for the tools through abstraction. This would involve using the contextual inquiries observation method where we would observe the user working in the real world with the existing tools and interrupt to ask questions.
* **Design**:
After reaching a shared understanding of a problem with the domain expert, begin designing a visualization solution.
* **Implement**:
Create a prototype through rapid software prototyping.
* **Deploy**:
Deploy the tool and gather feedback from the user in real world. This will determine whether the domain experts were helped by the new solution.
* **Reflec**t:
Reflect on how the design study relates to the current visualization literature. Could this design study add something to the previously proposed visualization design guidelines?
* **Write**:
Clearly lay out the design study in a paper. Follow a logical thread of the design journey.

## Design Study Pitfalls
* PF-2: Insufficient knowledge of vis literature. 
Since we are just beginning to dive into information visualization and design, we do not have a full understanding of the current visualization literature.
* PF4: No real data available.
 Data given initially was in a table showing the ferry schedules and routes. We were missing load information for the vessels which is a pitfall as we would require some historical or current load level data to meet the requirements. 
* PF-11 : No rapport with collaborators.
 To avoid this pitfall, we would need to put a genuine effort to build rapport with the collaborators.
* PF-5: Insufficient time available from potential collaborators.
 We would need to ensure the potential collaborators and us as the visualization researchers can commit significant time to for the research activities.
