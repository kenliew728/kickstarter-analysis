# An Analysis of Kickstarter Campaign
---
## **Overview of Project**
### Purpose
The purpose of the project is to analyze the trend of kickstarter campaign outcome relative to the launch date and funding goals. The theater as parent category and plays as subcategory will be the primary focus of the study spanning from the year 2009 to 2017.
### Analysis and Challenges
#### *Analysis of Outcomes Based on Launch Date*
A new data set, year, is added to the new column created on the kickstarter tab in order to extract the year from the "Date Created Conversion" column. The next step is to create a pivot table that consist of the parent category and year as filter and date created and count of outcomes as results. Based on the results, there were a total of 1,369 kickstarter campaigns launched during the study period. The study outcome can be summarized in the table below.  
|   Results   | Count |
| ----------- | ----- | 
| Successful  |  839  |
| Failed      |  493  |
| Canceled    |  37   |
| Total       | 1369  |
#### *Theater Outcome vs. Launch Month Trend Chart*
A line chart is plotted to visualize the trend of funding goals relative the the month where the kickstarter is launched. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/70525492/92652912-375b0080-f2b3-11ea-952a-5901e397599f.png)
---
#### *Analysis of Outcomes Based on Goals*
A second study was added to understand the outcomes of kickstarter campaign based on funding goal. To begin the study, a table was created with columns to hold the data for range of funding goals, number of successful, failed, and canceled campaign, total projects, percentage of successful, failed, and canceled campaign. Using the "CountIfs" function, each column was reference to the kickstarter worksheet to extract the data. Once all the data is populated, a line chart is plotted to visualize the trend of funding goal range relative to the campaign outcomes. The line chart allow us to draw further conclusion on whethe the range of funding goals influence the outcome of the campaign. 
#### *Kickstarter Campaign Outcomes vs Funding Goal Range Chart*
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/70525492/92654413-65414480-f2b5-11ea-9e41-f915b27e588d.png)
---
#### *Challenges and Difficulties Encountered*
The report compilation was not without its challenges. It was not easy to figure out on how to insert screen shot into a Github readme content. I was able to research through Google on some of the method used to insert screen shot. The one I picked was to drag my PNG file into the Github's issues tab and copy and paste the link created into Github's readme content. The end results were satisfactory. The next challenge was to create the right header and table format. I was able to learn the basic wrtting and formatting syntax through the link provided on the module and was able to try different syntaxes in this kickstarter report.
## Results
#### *Theater Outcomes relative to Launch Date*
The following conclusions can be made about the Theater Outcomes based on Launch date
1. The kickstarter campaign had the best outcome during summer starting in the month of May
   - Summer is typically a vacation season and more people are willing to attend plays in theater.
2. A downward trend was observed from peak month of May and gradually got worse in December
   - In constrast to summer, fall to early winter is typically a slower season due to the fact that most people are at work or kids are at school.
#### *Outcome based on Goals*
The following conclusion can be made on the outcomes based on goals
1. The number of successful outcomes is higher if the funding goals is less than $1000, which represents 75.8% success rate. It is followed closely by the funding goals between $1000 and $4999, which has a success rate of 72.7%. 
## Conclusions
The kickstarter campaign outcomes based on launch date and goals have provided a visual conclusion that it is advisable to launch a campaign in May with a funding goal of less than $1000 to achieve a higher success rate. However, we cannot be certain that whether the two variables are sufficient to launch a kickstarter campaign. Here are the additional analyses that can be used to draw aditional conclusion.
1. Include count of outcomes based on the funding goals and total days to reach goal (less or equals to 30 days). This will allow us understand if target can be met within 30 days if funding goal is low. If the analysis shows it takes more than 30 days to achieve the lower funding goal, launching a campaign with lower funding goals may not be a best option. Here are the example:
![Additional Analysis](https://user-images.githubusercontent.com/70525492/93038460-a9607c00-f60a-11ea-9828-10e02f824dd4.png)
2. A line chart is plotted based on the table above. In this example, the chart is showing campaign funding has a higher success rate of achieving its goal within 30 days if the funding goal is lower, with the exeption of funding goals betwwen $35000 to $39999 range. 
![Additional Chart Analysis](https://user-images.githubusercontent.com/70525492/93038648-2b50a500-f60b-11ea-9fee-fdab8e14973d.png)
3. Additional statistical analysis may be needed in order to draw a stronger conclusion on the outcomes of kickstarter campaign. Nevertheless, the goal of this study is to optimize variables needed in order to achieve the best outcome. 
