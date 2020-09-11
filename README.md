# An Analysis of Kickstarter Campaign
---
## **Overview of Project**
### Purpose
The purpose of the project is to analyze the trend of kickstarter campaign outcome in relation to their launch date and funding goals. The theater parent category will be the primary focus of the study spanning from the year 2009 to 2017.
### Analysis and Challenges
#### *Analysis of Outcomes Based on Launch Date*
A new data set, year, is added to a new column created on the kickstarter tab in order to extract the year from the "Date Created Conversion" column. The next step is to create a pivot table that consist of the parent category and year as filter and date created and count of outcomes as results. Based on the results, there were a total of 1,369 kickstarter campaigns launched during the study period. The study outcome can be summarized in the table below.  
|   Results   | Count |
| ----------- | ----- | 
| Successful  |  839  |
| Failed      |  493  |
| Canceled    |  37   |
| Total       | 1397  |
#### *Theater Outcome vs. Launch Month Trend Chart*
A line chart is created to visualize the outcome categories by month

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/70525492/92652912-375b0080-f2b3-11ea-952a-5901e397599f.png)
---
#### *Analysis of Outcomes Based on Goals*
A second study was added to understand the outcomes of kickstarter campaign based on funding goal. A range of funding goal is created in a table format. Using the "CountIfs" function, the table conduct a count of number of successful, failed, and canceled campaign. The data is then use to calculate the percentage of each category. Once completed, a chart is plotted to visualize the trend of each category to the range of funding goals. This will allow us to analyze if the funding goal influence the success rate of kickstarter campaign. 
#### *Kickstarter Campaign Outcomes vs Funding Goal Range Chart*
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/70525492/92654413-65414480-f2b5-11ea-9e41-f915b27e588d.png)
---
#### *Challenges and Difficulties Encountered*
The main difficulty was trying to insert screenshots of the chart into Github readable code. Regression analysis, statistical analysis, 
