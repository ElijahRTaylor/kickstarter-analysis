# Kickstarting Analysis With Excel
## Overview of Project
### Purpose
In order to help Louise gain a better insight on how different kickstarter campaigns performed in relation to their launch date and their campaign goals, we decided to perform an analysis on data from various theather kickstarter campaigns.  We want to see if and how campaign start dates and campaign goal amounts affect the outcomes of theather campaign results.

## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
In order to conduct the analysis, we first wanted to analyze the relationship between kickstarter campaign performance relative to their launch dates.  We did this first by creating a pivot table to display the count of the outcomes of all of the theather kickstarter campaigns (successful, canceled, failed).  Once we created the pivot table to display the pertinent data, we then created a line graph that showed the amount of successful, canceled, and failed campaigns next to each other.  

The chart below shows how frequent the different theather kickstarter outcomes occured throughout the 12 months in the year.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/87248687/137567561-95c20c5f-878b-4fd0-8837-ae0dcf8322a7.png)
Based on the line chart, we can see that most of the theather kickstarters were successful in the months of May, June, and July.  Most of the failed theather campaigns appear to also be during May through July.  In comparison to the failed kickstarter campaigns, the successful campaigns have been much more successful than the failed ones during May through August.  After August, the amount of successful campaigns do not vary too much from the amount of failed campaigns.  The amount of canceled campaigns are very minimal in comparison to the amount of successful and failed campaigns.  It does not have alot of significant rises and drops throughout the year.

### Analysis of Outcomes Based on Goals

Another thing that we wanted to analyze was the relationship between play kickstarter campaigns and their goal amounts.  We wanted to see whether campaigns for these plays generally succeeded or failed due to their campaign goal amount.  In order to properly analyze, we created 12 separate dollar amount ranges and calculated the number of successful, failed, and canceled projects based on those ranges.  Once we calculated the total amount of projects in each range, we then calculated the percentage of each outcome for each range.  


The chart below shows the percentage of successful campaigns against failed and canceled campaigns in each range.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/87248687/137568286-98e58d76-5792-4896-8483-16cab522145c.png)

From looking on this chart, the first thing we can see is that there were no canceled campaigns.  This means that the percentage of successful and failed campaigns for each range should add up to 100%.  Because of this, the line representing the percentage of successful campaigns is a reflection of the line representing the failed campaigns.  We can see that percentage of successful campaigns with goals from the ranges of <1000-19999 appear to drop as the goal amount increases from range to range.  It appears to go back up again between the ranges of 35000-44999, but then it sharply declines after that. 

### Challenges and Difficulities Encountered 
It was extremely important for us to ensure that we had the launch dates in the proper axis so that the line graph could clearly display the count of outcomes vs the launch month.  Before having the proper fields for the pivot chart completed, my line chart was not being clearly displayed.

For the analysis of the outcomes based on goals, one of the challenges I ran into initially was forgetting to format the cells to represent percentage amounts.  Before I did this, my line chart was displaying the data as decimals rather than percentages.

## Results

-Based on the Outcomes based on Launch Data analysis, we can conclude that most theather kickstarter campaigns were successful during the months of May, June, and July.  We can also conclude that during December, the amount of successful theather campaigns was almost around the same amount of failed theather campaigns.

-Based on the Outcomes based on Goals analysis, we can conclude that kickstarter campaigns for the plays tended to fail more often as the goal amount grew larger and larger.  

-One of the limitations in this data set is that we do not have a large sample size of instances of kickstarter campaigns having goals of more than 15000.   Another limitation of the dataset is that it is not specifc to one specific country.  Therefore, we are dealing with different currencies that may not have the same value as the other currencies it is being analyzed with.

-For the outcomes based on goals analysis, we could have also used a pie chart for each goal range.  Since we were dealing with percentages, it would have been a good graphical representation tool to show how many of the campaigns in those ranges were successful vs. failed campaigns.  Another chart we could have used was the 100% stacked columns.  This could provide a visual representation of the percentage of kickstarter campaigns that were failed or successful for each goal range.

