# Kickstarting with Excel

## Overview of Project

### Purpose
This analysis was done to visualize the relationship between the outcomes of the fundraising campaigns and the campaign’s launch date and goal. This analysis was completed in Excel, using pivot tables and charts to make interpretations. The results can be used to draw conclusions based on the presented relationship and make comparisons or predictions for current and future campaigns.   

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The first part of the analysis done was to compare the outcomes based on launch date. This was done by first creating a pivot table and then grouping the data by month to display the success rate for all the years combined by month. 
![Theater_Outcomes_vs_Launch_Date](https://user-images.githubusercontent.com/104689576/167052522-f7d57450-1116-4388-bf0e-b0bf9e9ffeac.png)

![Theater_Outcomes_vs_Launch_Date](https://github.com/erwilhite/kickstarter-analysis/tree/main/Resources/Theater_Outcomes_vs_Launch_Date.png)

### Analysis of Outcomes Based on Goals
The second part of the analysis consisted of binning the data by goal amount and then counting each outcome per bin. The outcomes were then summed to find the total projects and calculate the percentage of each category by goal range. This table was then plotted by displaying the goal on the x-axis and percentage of each outcome on the y-axis.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/104689576/167052624-84955d46-e484-4a26-8cc6-7b7748ab8bf0.png)

![Outcomes_vs_Goals](https://github.com/erwilhite/kickstarter-analysis/tree/main/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
There were not many challenges encountered in performing this data analysis. Potential problems that could occur could be not having the right filters set, referencing incorrect cells, or having the format incorrect on numbers. One challenge with respect to the data set was understanding the context of the values and how they relate to each other. Not having the ability to clarify certain parameters made it a little more challenging to make interpretations, as well as assure the integrity of the data. 

## Results

When looking at the graph for Theater Outcomes by Launch Date, it can be determined that May and June had the most successful launched campaigns. It should be noted though, that May and June had the highest number of total campaigns launched as well. The total failures were consistently lower than the total successes each month, and the failure rates also deviated less from month to month. December showed the lowest number of total campaigns launched, was the least successful month, and had the smallest gap between failures and successes.

From this graph, it can be concluded that May and June are the most popular times of the year to launch campaigns and that December is the least popular time to launch a campaign. From just this analysis alone, it would appear there is a higher likelihood of having a successful outcome if a campaign is launched in May or June, however there are many factors that are not considered in this analysis that could be influencing this impression. One factor could be that there were more campaigns launched in May and June that had more attainable goals, which would make them have a much higher chance at success. There are many more factors (that could have a bigger influence) than the launch date, that could impact the success of a campaign. These could include attainability of goal, state of the economy when the campaign was launched, the duration of the campaign, and efforts of the campaign team.  

When looking at this data with respect to the outcome based on goal, it can be concluded that the most successful range for a campaign goal is $1000-$4999, however the same considerations with respect to outside factors applies to this interpretation as well. This graph can be a bit misleading with using percentages though, as the total number of projects decreases as the goal increases, so it is a much larger data set in the beginning and decreases as the graph moves towards the higher goal ranges. In particular, the bin that has a 100% failure rate only has one data point in it. This visualization might be better represented with stacked columns to display the total amount of outcomes in each range. 
