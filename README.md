# Kickstarter Campaign Analysis
Performing analysis on kickstarter data to uncover trends

## Overview
This project intends to look at trends of crowdfunding data to see if there are any characteristics that make these campaigns successful. It is intended to help Louise, who wants to start a crowdfunding campaign for a play called "Fever." In this project, we anaylyze many various aspects of the campaign data: campaign money goal, money pledged and funded, category of the campaign, data created and ended, whether or not campaign was a success, etc.. 

### Analysis and Results 
For our analysis we looked at the outcomes vs goals for the campaign to see how successful they were. The goal refers to the amount of money and they wanted for their campaign. From the chart, we can see that percentage of successful campaigns have an inverse relationship with percentage of failed campaigns, and canceled is at 0. This is obviously expected, if there are no canceled campaigns either success will be a fail or a success. The campaigns with the lowest success rate and highest failure rate are from 25000 to 29000 and 35000 to 39999 with 0% success rate and 100% failure rate. The highest success rate was the campaign with the least money as a goal, with 0 to 1000 having a nearly 80% success rate, so we can conclude that the lower the money goal the higher the success rate, but not definitively. This is because other areas like 200000 to 24999 are successful too. 
![Outcomes vs Goals!](https://github.com/adarisi7/kickstarter-analysis/blob/main/Kickstarter%20Analysis/Outcomes_vs_Goals.png)

From our analysis for the Theater Outcomes we analyzed by month to see which time throughout the year is the most successful. We can clearly see that May and June have the highest success rate, and November and December have the lowest success rate. January has the most plays canceled. From this data we can see that around summer, the success for plays goes up because more people are free. Also, maybe because of snow days, and bad weather, there could be a low success rate in winter. 

![Theater Outcomes Based on Launch Date!](https://github.com/adarisi7/kickstarter-analysis/blob/main/Kickstarter%20Analysis/Theater_Outcomes_vs_Launch.png)


One problem I ran into for this project was the pivot tables, but I found that my subcatqegory and parent category was wrong, so I was able to fix that. Some limitations on the line graphs is that when you have more values on the x axis, it might be harder to find the value of one. For this I recommend using bar charts since they are more precise, and stemplots could also work if they are numbers. 
