# Bike Sharing Analysis
[link to dashboard](https://public.tableau.com/shared/SRCMQN4W3?:display_count=n&:origin=viz_share_link "Link to Tableau Story")

## Overview
####
A tenative bike-sharing program has been proprosed to investors and stakeholders for the city of Des Moines based off of the success of a similar bike-sharing program in New York City. In order to provide a credible and feasible business plan, the stakeholders have requested a break down of the bike share data in New York City. Before beginning the process of creating helpful imagery, the CSV file containing the bike share data is accessed using Python code, Pandas, and Jupyter Notebook. With these different tools, the CSV file is placed into a dataframe, the trip duration field converted to the appropriate datetime type, and then saved to a new CSV file. With the corrected data, several useful graphs and visualizations are then created using Tableau Public to fulfill the requests of the potential investors. 

## Results
####
Below are the results and visualizations created from the statistical analysis of the New York City Citibike sharing program that provides support to the business proposal. 
- Of the specific user types, the largest group are the subscribers with roughly over 1.9 million individuals in the month of August. 
- When breaking down the users by gender, the male customers greatly outweigh female or unidentified users.
####
![usertypes](https://github.com/victoriaguille/bikesharing/blob/main/images/usertypes.png) ![genderuser](https://github.com/victoriaguille/bikesharing/blob/main/images/genderuser.png)
####
- Moving onto the actual usage of the bikes, it was found that the first hour of a bike trip for most users had the highest activity.
- If the data was broken down by gender, it was found that those who did not identify themselves were usually one time customers who all used the bike for thirty minutes before quickly declining.
####
![firsthourtrip](https://github.com/victoriaguille/bikesharing/blob/main/images/firsthourtrip.png) 
####
![genderfirsthourtrip](https://github.com/victoriaguille/bikesharing/blob/main/images/genderfirsthourtrip.PNG)
####
- With the knowledge of how long an average bike trip for most users takes, the data was broken down by user type, gender, and weekday to understand what day of the week these trips were occurring. The most activate population of users with these speicifications were subscribing male users. 
####
![userweekday](https://github.com/victoriaguille/bikesharing/blob/main/images/userweekday.PNG)
####
- Further breaking down the weekday data by hours, the most popular hours of use are Monday through Friday, 7:00 a.m. to 9:00 a.m. and Monday through Friday, 5:00 p.m. to 7:00 p.m.
- Of the weekday data by hours, the most popular day and time in total was Thursday from 5:00 p.m. to 7:00 p.m. with the peak amount of riders out during that time frame being 44,905 users.
####
![genericheatmap](https://github.com/victoriaguille/bikesharing/blob/main/images/genericheatmap.PNG)
####
- Much like the rest of the statistical analysis, men were the largest group of users for the bike share program during the typical rush hours outlined above. 
####
![genderheatmap](https://github.com/victoriaguille/bikesharing/blob/main/images/genderheatmap.PNG)

## Summary
### Suggestions for Business Planning
####
It can be quite difficult to move a successful business or program to a new area when perhaps the two locations are not identical. New York City and Des Moines, being two different cities in different portions of the country, are rather different. However, establishing a bike share program in Des Moines based off of New York City Citibike data can be successful when looking at the right factors. This potential program could see equal success in Des Moines by paying attention to the users and bike data that are currently displayed in this report. In New York City, the male subscribers of the Citibike share program greatly outnumber any other type of customer. Des Moines can follow this path of pushing for male subscribers in order to achieve similar success. Keeping the male audience in mind, this new bike share venture would have the potential for rapid growth if the bikes are placed in stations or locations that are heavily populated by work and home destinations to match the commute data being seen in New York City. Another group the Des Moines program could market to would be the younger cyclists in the city as New York City saw increases in duration of bike rides as the age of the user declined. All of these stand out statistics would benefit the Des Moines team's business planning.

### Suggestions for Future Analysis
####
With the current statistical analysis requested by the stakeholders of this proposal, there is only clear patterns in the data based on gender, but not age. It is obvious throughout the multitude of visualizations that men are the primary users, however, Des Moines might not have a large male cyclist community. This would mean the team would need to look at other factors such as the age groups of cyclists. Breaking down the weekday trips seen above by age rather than gender could give the analysists and planners a clearer picture of who would be the target audience for future marketing. This could easily be done in the user type by weekday heatmap by replacing the gender column with the birth year field. Continuing on the focus of age groups, a new pie chart for birth years rather than by gender could be created to give a clear understanding of the ages of the user base. Both of these future analysis suggestions could provide the Des Moines bike share team with insight into their potential market for further success.

