# An Analysis of Kickstarter Campaigns
## **Overview**
Performed data analysis on several thousand crowd-funding projects to uncover any hidden trends. Utilized the data set provided, including: 
- Goals
- Amounts Pledged
- Outcomes
- Subcategories
- Launched Dates
### **Purpose**
To develop a deeper understanding of the data in order to help Louise with her crowd-funding campaign. Created various visualizations including *line charts* and *box plots* to determine how the outcome was affected by the launch date and by the goal amount for each campaign, wether successful, failed, or canceled. Applied statistical analysis to discover and document the measures of central tendancy of goals vs. pledged amounts.
 ## **Analysis and Challenges**
 ### **Analysis of Outcomes Based on Launch Date**
 I concluded that based on the information from 1,369 total theater campaigns in the data set, the launch date appeared to have a significant impact on whether or not the campaign was successful or failed. 
 1. The months of May and June had the highest number of successful campaigns, at 111 and 100. The months of November and December had the lowest, at 54 and 37. It appears late Spring/Early Summer is the best time to launch a campaign. There could be various reasons for this, such as poor weather and attendees schedules. 
 2. The highest rate of canceled campaings was in January. This could also likely be due to weather and attendees schedules around the holiday season.
 
 ![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/106620821/174503195-0951b979-1ba7-4716-a782-046b2118f97a.png)
 
 ### **Analysis of Outcomes Based on Goals**
 The goal amounts ranged from less than *$1,000* to *$50,000* or more, and were categorized in increments of *$5,000*. The majority of goals were in the *$0-$10,000* range. It appears there is a negative correlation between the goal amount and a successful outcome. 
 1. 88% of those with a goal of *$50,000* or more failed, while only 24% in the lowest range of *$0-$1,000* failed. One could conclude that the goal amount was too high and therefore it was too unrealistic to reach a successful outcome.
 2. The majority of successful outcomes had a goal amount in the range of *$0-$10,000*. Perhaps starting with a smaller, more acheivable goal in mind led to a more successful outcome.
 
 ![Outcomes_vs_Goals](https://user-images.githubusercontent.com/106620821/174503801-73a181b0-6e40-4e3e-80b5-a386b6c885f6.png)
 
 ### **Challenges and Difficulties Encountered**
 The challenges I encountered with this data set were as follows:
 1. There were outliers in the data set when exploring the goal amounts. There were very few in the *$40,000* and above range, so this could have possibly skewed the data.
 2. The data was from campaigns from many different countries, making it hard to establish a baseline or control group.
 3. There is a wide variety of information to consider in this data set, all of which can have a potential impact on analysis, making it difficult to determine which variables, whether presented together or alone, were affecting the outcome.
## **Results**
To conclude, there are a wide variety of factors to consider when analyzing the Kickstarter Campaign data set. There are many variables that may affect whether the campaign was successful or failed, including the launch date, goal amount, country, and subcategory. There is evidence to suggest the best time to launch a campaign would be late Spring/early Summer. Additionally, campaigns with exceedingly high goal amounts appear to be less successful while those with more reasonable goal amounts appear to have higher success rates. Further analysis would be required for a more definitive conclusion. Perhaps creating a bar chart comparing the goal vs. pledged amount would allow for more insight. Additionally, an analysis of which category had the best outcome in each country could further help Louise decide which route to take for her campaign.
