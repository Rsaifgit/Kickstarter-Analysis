# Kickstarting with Excel

## Overview of Project 
The objective of this project is to analyze the performance of different campaigns of Louise’s play Fever based on their launch dates and funding goals. 

## Analysis and Challenges
Analysis overview:
Overall analysis covers 2 critical points as following: 
o	Campaign performance based on launch dates: 
    a.	1st of all some data management has been executed to make the overall data set ready for analysis such as: 
        i.	Segregating categories into parent & sub-category from 1 single column to 2 different columns
        ii.	Actual launch/end dates identified converting numbers to dates with a formula. 
        iii.	Year function used to derive only the Year of launch dates for easy analysis. 
        The screenshot of this execution is provided below: 

    b.	After data set arrangements, a pivot table in a separate worksheet has been created to identify the no. of successful/failed/canceled campaigns in each 12 months of all the years. The Years have been grouped in months to pinpoint the exact numbers. 
    c.	After the pivot table is been created, a monthly chart of no. of successful/failed/canceled campaigns has been plotted to pinpoint in which months the performance is better or worse.    

    A screenshot of this analysis provided below:

o	Campaign performance based on funding goals: 

    a.	The funding goals from the main worksheet is been grouped into 12 different ranges starting from less than 1000 to 50,000 or more. 
    b.	For each of this goal ranges, no. of successful, failed & canceled campaigns have been identified from Sub-category “Plays” with the help of COUNTIFS function in excel. 
    c.	After this Total no. of campaigns/projects have been counted in each goal range along with the percentage of successful/failed/canceled projects in each goal range. 
    d.	Then a line chart has been formed to pinpoint on the success/failure/cancellation rates in each goal range. 
    
    Screenshot of above analysis provided below: 

### Analysis of Outcomes Based on Launch Date
    o	May-Jul months of each year experienced the most number of successful theaters maybe because for the summer season when people  
        want to go out and enjoy. 

    o	On the other hand, Dec to March months experienced the most number of failed or cancelled theaters may be because of the same
        weather seasonality (winter period) when people tend to stay at home more. 

    o	Oct is a unique month for all the years when none of the theaters got canceled, it’s either successful or failed.  

    Key conclusion/recommendation will be to focus more on summer seasons for theater launches and minimize number of theaters further in the winter or Dec-Feb period.  


### Analysis of Outcomes Based on Goals

    o	There are about 1,047 Plays in total out of which majority is successful (66% in total). 

    o	About 94% of the total projects are within the range of less than 1000 to 19,999 funding goals and average success rate of those
        projects is about 62%. 

    o	4% of the total projects are within the range of 20,000 to 44,499 funding goals with an average success rate of 45%. 

    o	Rest 2% of the projects are in the range of 45,000 to 50,000 or more funding goals which mostly failed. 

    Key conclusion/recommendation will be to focus on increasing number of projects in the range of less than 1,000 to within 15,000 funding goals ranges to have the higher probability of success rate based on historical trends.

### Challenges and Difficulties Encountered

    **Key challenges faced:**

    •	Took some extra time to learn couple of new things online such as: converting certain number to a specific date, segregating parent/sub-category from single column and grouping the Years into months in the pivot table.

    •	It took a lot of time to find exact number of successful/canceled/failed projects in 12 funding goal ranges simple because of the time taken to change the formulas in each cell. There might be a shortcut to do that. 
    
    **Limitations of data set:**

    o	Information like staff pick, backers count, spotlight is useful and kind of unnecessary for the overall objective of the analysis and it actually makes the data set too cluttered. 

    o	Some additional information such as, Duration of the Plays, Genre of the plays (thoughtful, motivational, comedy, romantic,
        horror etc), target audience could have been more useful in pinpointing the performances and where to focus on.  

### Opportunity for further analysis

    o	The rate of pledged amount vs. the funding goal in different goals ranges is a good analysis to have a deeper focus on value
        adding projects. 

    o	A yearly chart of no. of successful theaters will provide a good indication to understand the audience’s appeal of theaters over
        the years. 

    o	A pie chart of successful campaigns based on different countries could be useful to understand country wise performance.
        Moreover, country wise funding goal level analysis will also help to understand which country to focus on with which funding goals. 

    o	Measures of central tendency by country will be useful to easily compare the goals/pledges for failed and successful campaigns
        alike and identify any trends there. 