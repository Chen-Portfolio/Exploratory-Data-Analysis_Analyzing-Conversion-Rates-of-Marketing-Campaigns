# Exploratory-Data-Analysis_Analyzing-Conversion-Rates-of-Marketing-Campaigns
## Table of Content
- [Project Overview](#projectoverview)
- [Data Description](#datadescription)
- [Technical Overview](#technicaloverview)
- [Results](#results)

***

<a id='projectoverview'></a>
## Project Overview

In this project, A bank who has run extensive marketing campaigns trying to capture new customers kept tracking on how many times they've contacted a person and they collected various data regarding the customers in contact and the marketing campaign as well as provided some social and economic context attributes. This analysis aims to evaluate whether or not their marketing campaign is successful.

This project is mainly divided into nine steps as below:

1. `Getting a Summary of the Dataframe` in this part, baisc information and statistical description about the dataset was examined in order to see how customers in various propertites were converted as well as the data type of the column 'y'(converted) was changed from 'yes' or 'no' to '0' or '1'.

2. `Examining Correlation of the Variables` in this part, a correlation maxtrix was plotted in order to examine visually the relationship strong or weak of each variable with the variable "converted".

3. `Calculating the Conversion Rate` in this part, the conversion rate of the whole dataset was calculated as 11.3%.

4. `Calculating the Conversion Rate per Each Campaign` in this part, the conversion rate of each campaign was calculated, and the result is the top three campaigns showed the highest conversion rates as above 10% and as the number of campaigns(number of contacts) increased, the conversions rate went down.

5. `Calculating and Plotting Conversion Rate by Age` in this part, firstly customers in different ages were divided into various age groups, then a bar chart with each bar representing the age group and the corresponding conversion rate was plotting. The result is the easiest converted groups was the oldest ones above age 65, then the youngest one between 17 to 25, the middle part from 25 to 65 were relatively hard to capture compared to the other two age group.

6. `Calculating and Plotting Conversion Rate by Education` in this part, two pie charts were plotted to represent the conerversions and non-conversions for all education levels. The results is people with university degree tend to convert more while with basic education level converted less.

7. `Exploring and Plotting Conversion Rate by Job ` in this part, a horizontal bar chart was plotted to examine the conversion rate by each job, and the result is "student" and "retired" are the most easiest converted roles.

8. `Exploring and Plotting Conversion Rate by Marital Status` in this part, a bar chart was plotted to explore the conversion rate by each marital status "married", "divorced", "single", and "unknown"; and the the result is the people being "unknown"(maybe in a relationship) and single are more easily converted compared to married and divorced groups of people.
