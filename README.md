
# Kickstarter-Analysis

## Overview of Project
### Purpose
The project is an analysis of Kickstarter projects. The purpose of this project is to determine how Kickstarter perform compared to their launch dates and funding goals. 

## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
Analysis of outcomes based on launch date consisted of creating a pivot table to breakout the outcomes for projects aggregated by launch months.  An analysis of the data for just theater projects shows that there was 1369 projects across all years(2009-2017), with a success rate of 61%(839) compared to failed rate of 36%(493) and cancelled of 3%(37).
Total theater projects by month peaked in May and then decreased through the remainder of the year with a small peak in month of Oct. The range of theater projects launched by month at peak of 166 in May and a low of 75 in Dec.  Successful theater projects followed the same trend throughout the year, with a peak of 111 in May and just 37 in Dec.  
Additional analysis in comparing outcomes for theater projects to the outcome of total projects shows that theater projects consisted of 34% of overall projects (4064 campaigns). Theater projects by far had the most projects of any other category. So, it is no surprise that in general theater and overall projects had similar trend. 
Overall projects peaked in July with 386 but May and June had 386 and 387 respectively.  Overall projects then decreased through the end of the year with an increase in Oct and Nov. Successful projects also peaked in May before declining through the end of the year with an increase in Oct and Nov. Hower theater projects showed to be more successful compared to total projects which was at 54%, while total failed projects were roughly the same at 38%.  Total projects were cancelled more often at 8%. 
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/62673123/123525714-a5788480-d687-11eb-83ba-ba5a4dc6ddcf.png)

### Analysis of Outcomes Based on Goals
Analysis of outcomes based on goals consisted of creating a table and chart to determine the outcomes based on groupings of goals into buckets. When analyzing the data we can see that 75% of successful projects were with goals under $9999.  35% of projects had goals between $1000 to $4999. This was followed by $5000 to $9999 consisting of 17% of projects. Percentage of projects declined as the goal increased for the most part, with expect of goals under $1000 as the third biggest at 11% and surprisingly projects with goals over $50000 were the fourth largest consisting of 11%of projects. Not surprisingly success rate was dependent on the size of goals, as projects with the smaller goals were most successful.  Success percentage decreased as goal increased for the most part but with an increase in $35000 to $39999 and $40000 to $44999 ranges, before dropping off again. 
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/62673123/123525735-ba551800-d687-11eb-9c1a-e418e32b9ab4.png)

### Challenges and Difficulties Encountered
The biggest challenges with this analysis was around the data.  Firstly, the launch date and deadline date were contained UNIX timestamp and needed to be converted to a readable format.  Secondly the category and subcategory were merged into one column and it was necessary to split the category and subcategory into separate columns to do appropriate analysis. Lastly the COUTNIF function was tedious to setup and use to calculate the outcomes based on the buckets of goals. Incorrectly applying the function would have resulted in inaccurate results. 

## Results
### Outcomes based on Launch Date
Results from this analysis show that Theater projects overall were 61% successful regardless of launch month, other than Dec the chance for success from a Theater project was greater than 50%. Additionally Theater projects had the best success rate in May and June of 67% and 65% respectively, this would indicate that launching a project in either of those months would present best opportunity for success. 

### Outcomes based on Goals
Results from this analysis clearly show that successful projects had smaller goals compared to larger goals.  75% of successful projects had goals under $9999, which consisted of 64% of total projects

### Limitations of this dataset

### Additional possible tables and/or graphs 
There are at least three additional tables or graphs that would be useful. It would be useful to break down the Outcomes Based on Goals graph by category specifically for Theater projects, since this was Louise's focus. It would give us better idea of what goals were successful for Theater projects.
 We have seen how individually launch date and goal may impact success, but not the relationship between launch and goal together impacts success of projects.  A second graph the includes both goals and launch date would be necessary.   
Lastly breaking down this graph by subcategory especially for Plays as this is Louise’s focus would give the best comparison to project for her play. 

