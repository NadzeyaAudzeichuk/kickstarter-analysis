# Kickstarting with Excel

## Overview of Project

The project is about analyzing crowdfunding data to help Louise who wants to start a crowdfunding campaign to fund her play Fever. She is estimating a budget of over $10,000

We will explore several thousand crowdfunding projects using Excel to organize, sort, and analyze crowdfunding data to determine whether launch dates and funding goals affect the success of Louise's campaign.

### Purpose

This data analysis aims to help Louise set her crowdfunding campaign to mirror other successful ones.

## Analysis and Challenges

We will look at how different campaigns make out in relation to their launch date and fundraising goals.

### Analysis of Outcomes Based on Launch Date

Constructing a pivot table of campaign outcomes, based on which month of the year it was started, we can see all of the campaigns that fell into one of the three outcome categories - successful, failed, and canceled. Because we are interested in a particular category, we filtered the outcomes for the Theater category. For a visual representation of the trend, we constructed a line chart.
! [Theater_Outcomes_vs_Launch](https://github.com/NadzeyaAudzeichuk/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

To analyze campaign outcomes based on funding goals, we created dollar-amount ranges with a step of 5,000 to group projects based on their goal amount. Using the COUTIFS() function and calculating respective percentages, we populated the number of successful, failed, and canceled projects for the Theater Plays category. To get a visual representation of the data, we constructed another line chart.
! [Outcomes_vs_Goals](https://github.com/NadzeyaAudzeichuk/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

Regarding this dataset, we did not encounter any challenges. Data is clean, and organized, data types match in all fields, no missing data, which is not always the case.  

## Results

- Campaign Outcomes Based on Launch Date

Data from the analysis shows that 839 out of 1,369 projects, which is two-thirds of the total in the Theater category, are successful. When failed and canceled campaigns stay relatively consistent throughout the year, there is a spike of successful ones coming for May, gradually going back to the average by August. The data shows that overall, Louise's project idea is in a generally successful category. In addition, there is a greater chance for Louise's campaign to become a successful one if she starts her campaign from May through July.

- Campaign Outcomes Based on Funding Goals

These results allow us to determine most successful Kickstarter campaigns have their fundrasing goals in the range below $5,000. What Louise is asking falls in the range where a chance of becoming a successful campaign is 55%.    

This data set has some limitations such as it is not up to date. The last information was collected in 2017. A lot of changes could happen over these past 6 years in trends of theatrical performances. Size-wise, 4,115 instances are considered a small dataset. Thus, increasing size and adding more recent data can improve decisions making.

Making decisions based on an analysis of the launch date and fundraising goal aspects is a limited approach. Looking at other information presented in the data would probably help Louise make her fundraising campaign successful. 
Examining different categories and analyzing how successful the theatrical category is compared to others (technologies, games, journalism) by creating a pivot table and bar graphs with related data. Calculating descriptive statistics and comparing fundraising goals over pledged funds for successful and failed campaigns. A particular, setting successful and failed campaigns in two separate tables and performing statistical analysis over planned amounts Kickstarters wanted to raise to actual amounts they pledged. Presumably would expand the hidden trends of the data.
