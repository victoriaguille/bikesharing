# Bike Sharing Analysis

## Overview
####
A tenative bike-sharing program has been proprosed to investors and stakeholders for the city of Des Moines based off of the success of a similar bike-sharing program in New York City. In order to provide a credible and feasible business plan, the stakeholders have requested a break down of the bike share data in New York City. Before beginning the process of creating helpful imagery, the CSV file containing the bike share data is accessed using Python code, Pandas, and Jupyter Notebook. With these different tools, the CSV file is placed into a dataframe, the trip duration field converted to the appropriate datetime type, and then saved to a new CSV file. With the corrected data, several useful graphs and visualizations are then created using Tableau Public to fulfill the requests of the potential investors. 

## Results
####
Below are the results and visualizations created from the statistical analysis of the New York City Citibike sharing program that provides support to the business proposal. 
- Of the specific user types, the largest group are the subscribers with roughly over 1.9 million individuals in the month of August. 
- When breaking down the users by gender, the male customers greatly outweigh female or unidentified users.
![user image](link) ![gender pie](link)
####
- Moving onto the actual usage of the bikes, it was found that the first hour of a bike trip for most users had the highest activity.
- If the data was broken down by gender, it was found that those who did not identify themselves were usually one time customers who all used the bike for thirty minutes before quickly declining.
![first trip](link) ![gender trip](link)
####
- With the knowledge of how long an average bike trip for most users takes, the data was broken down by user type, gender, and weekday to understand what day of the week these trips were occurring. The most activate population of users with these speicifications were subscribing male users. 
![user weekday](link)
####
- Further breaking down the weekday data by hours, the most popular hours of use are Monday through Friday, 7:00 a.m. to 9:00 a.m. and Monday through Friday, 5:00 p.m. to 7:00 p.m.
- Of the weekday data by hours, the most popular day and time in total was Thursday from 5:00 p.mm to 7:00 p.m. with the peak amount of riders out during that time frame being 44,905 users.
![generic heatmap](link)
####
- Much like the rest of the statistical analysis, men were the largest group of users for the bike share program during the typical rush hours outlined above. 
![gender heatmap](link)

## Summary
### Suggestions for Business Planning
####
success in nyc is seen with male subscribers. des moines can follow this path of pushing for male subscribers in order to achieve similar success. would be a good idea to station these bikes around populated work and home destinations to match the commute data being seen in nyc. also some proof that younger individuals are going longer distances on bikes. all important factors that could benefit des moines planning.
### Suggestions for Future Analysis
####
have data on male vs female, but not age. know that men are the primary users, so breaking down weekday trips by age rather than gender could tell you who to market for (explain which graph type to use). continuing on the focus of age groups, could create a pie chart for birth years rather than by gender. both of these factors could provide the bike share company insight into their potential market for further success.
