# Kickstarting with Excel

## Overview of Project

Our freind Louise wants to start a crowd funding campaign to help fund her play. Using previous Kickstarter data we will help determine if specific factors contribute to the success.

In This project We're deep diving into kickstarter campaign data in excel to devise an analysis on trends in the data. Using Excel we've transformed and displayed the data into charts we can use to analyze and draw conclusions from. In this analysis we can observe the success and failure outcome based on launch date. We can also observe the outcomes based on their monetary goal.

Data Source: (https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-online/module_1/data-1-1-3-StarterBook.xlsx)

### Purpose

The purpose of this project is visualize theater campaign outcomes to analyze. We'll use outcomes based on their launch date and funding goals to make our analysis. 

## Analysis and Challenges

We performed this analysis by manipulating and filtering the data to create Pivot tables and charts. We used the [=COUNTIF](https://support.microsoft.com/en-us/office/countif-function-e0de10c6-f885-4e71-abb4-1f464816df34) function, [Pivot Tables](https://support.microsoft.com/en-us/office/create-a-pivottable-to-analyze-worksheet-data-a9a84538-bfe9-40a9-a8e9-f99134456576) and a few more functions to help generate the data we want for our visualization.

A challenge I had during this project properly working with pivot tables. I didn't have much experience with them before this project. After some Googling and trial and error, I feel like I have a much better understanding of them after working on this project. 

### Analysis of Outcomes Based on Launch Date

![Outcomes Based on Launch Date Chart](/Resources/Theater_Outcomes_vs_Launch.png)

Analyzing this chart we can see the Outcomes of Theater kickstarters based on their launch date. 

-Theater Kickstarters had a much higher success rate in the month of May/June.
-December has the lowest success outcome. Almost equal to the count of failed outcomes in December.

### Analysis of Outcomes Based on Goals

![Outcomes vs Goals Chart](/Resources/Outcomes_vs_Goals.png)

Analyzing this chart we can see the Outcomes based on the goal of the Kickstarters.

-As the goal increases The percentage failed line starts to ascend until around $29,000.
-The highest success rate is Kickstarters with a goal $1,000 or less.

## Results

-The best time to launch a Kickstarter for Theater would be Late spring into early summer (May to July). 
-November to January have the least successful success outcomes and should be avoided if tryin to Launch a kickstarter.

-The most successful kickstarters are below $4,999.
-The Success and failure percentages flip at $35,000 to $44,999.

## Limitations on this dataset

- Providing reason why the campaigns failed. There are many other factors that could change the outcome that are not provided. 
- Were the kickstarters marketed and / or promoted? How did each Kickstarter reach their audience if at all?


## Other tables and graphs we could create

- We could filter the charts down to the subcategory "plays" to get a more accurate data set to visualize. 
