# Kickstarteranalysis

Performing analysis on Kickstarter data to uncover trends.

## Overview of Project

Louise is a play writer and she wants to start a crowd funding campaign to fund her play Fever.  Before she gets started, she wants to know how different campaigns fared in relation to their launch dates and funding goals.  With this knowledge, she is hoping it will help plan her campaign and make it successful.

### Purpose

In order to achieve Louise's goal in making the crowd funding campaign successful, for her play Fever.  I built two visualizations in Excel to assist Louise's business decisions.  The first visualization is a chart showing outcomes based on launch date and the other a chart showing outcomes based on goals. 

## Analysis and Challenges

Before I started my analysis, I first had to make changes to the dataset.  The launch date needed to be converted from a Unix timestamp to an actual date. Once that was done I created a column for the launch dates for all the plays nationally within the United States and other countries around the world.  Next I developed a pivot table showing the number of successful, failed, and canceled play outcomes per month. After that was completed I created a line graph to help Louise visualize the best time for her to start crowd funding.  Lastly, I created a line graph to show Louise the impact that goals have on crowd funding success. This was difficult because I had to extract the number of successful, failed, and canceled plays based on where the fell within 12 goal fund ranges.      

### Analysis of Outcomes Based on Launch Date

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/80642682/116016704-7e5ff100-a60b-11eb-8772-670ec7ca3f7a.png)

The first conclusion based off of the Theater Outcomes Launch Date graph, the best month for crowd funding is late April early May.  The second conclusion is that during the month of December there are less successful crowd funding campaigns.


### Analysis of Outcomes Based on Goals

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/80642682/116016730-946db180-a60b-11eb-8d50-7c1c2405d1ce.png)

Based off of the Outcomes Based on Goal funding graph, the percentage of successful goal crowd funding is higher when it is less than 1,000 and between 35,000 to 44,999 dollars.  Otherwise, if the crowd funding goal is anywhere between 45,000 to 49,999 the crowd funding campaign will most likely fail. 

## Results

- What are some limitations of this dataset?

A limitation of the dataset is the lack of demographic information it contains.  It would be in Louise's best interest in knowing the popularity of Fever with regards to who it may attract.  Also, the dataset is too broad in that its taking multiple countries into account with different cultures.  In my opinion the data should be more focused in on a specific location within a country.

- What are some other possible tables and/or graphs that we could create?

We could create a line graph comparing crowd funding deadlines and outcome success.  Another graph that can be created is a graph that compares subcategories to outcomes.  This can be helpful to Louise, if she wants to expand platforms.
