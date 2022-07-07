# Kickstarting with Excel

## Overview of Project
Utilize Excel skills to analyze Kickstarter data and determine theater outcomes based on their launch dates and money goals.

### Purpose

The purpose of this analysis is to determine how different campaigns performed in relation to their launch dates and funding goals given that Louise’s theater play achieved its fundraising goal relatively quickly after launch. Using the provided Kickstarter dataset, theater campaign outcomes based on the play's launch dates and funding goals will be visualized and analyzed.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

The chart below visualizes the number of successful, failed, and canceled theater projects based on the month of the year they launched. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/108038989/177430634-7a190267-4f3c-4cdc-98d4-90f8b4f37672.png)

### Analysis of Outcomes Based on Goals

The chart below visualizes the percentage of successful, failed, and canceled plays based on their funding goal dollar-amount ranges.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/108038989/177430618-a8a7dc45-0745-4e80-b9cc-a9c1ab77d3e5.png)

### Challenges and Difficulties Encountered

There were no challenges or difficulties encountered durign this analysis. Some potential challenges or difficulties that could have been encountered in the first deliverable is not correctly populating the filters, columns, and rows in the theater outcomes pivot table. A challenge or difficulty is the second deliverable is not correctly using the COUNTSIF() function when populating the number of successful, failed, and canceled columns from the Kickstarter data. 

## Results

From the Outcomes based on Launch Date chart, May is the month that launched the most successful Kickstarter theater campaigns. In contrast, the months of May, June, July, August, and October all had a similar amount of failed launched campaigns. A similar amount of projects were canceled throughput the year, except in October, which also shows a spike in the number of successful and failed projects from the precvious month of September. 

From the Outcomes based on Goals, the highest percentage of successful plays (76%) had goal amount ranges less than $1000. The highest percentage of failed plays (100%) had a goal amount range of $45,0000 to $49,999. The goal amount range of $15,000 to $19,999 had an equal percentage of succesful and failed plays (50%). 

The limitations of this dataset is that it is not all inclusive. Although we have data on theater plays for 21 countries, not all contries are represented in this dataset. The years of the data span from 2009 to 2017, and although we can use this to predict future trends, there is no information on current costs if we are trying to launch a play this decade.  

Some other possible tables and/or graphs that we could create are stacked bar graphs to determine the total successful, failed, and canceled theater plays in different countries to see in which country a new play will have a higher chance of success. A further option is a line graph to demonstarte the trends of total successful, failed, and canceled theater plays in specific countries throughout the years.
