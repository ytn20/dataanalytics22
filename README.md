# Kickstarting with Excel

## Overview of Project

### Purpose

The purpose of this assignment was to analyze campainge outcomes for Louise's play Fever. By analyzing different campaign outcomes based 
on their respective launch dates and fundraising goals we are able to uncover key findings that can help Louise for future campaigns. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

Fristly, I created the Years coloum in cell(U1) where I used the YEAR() function to get the exact year for each value in "Date Created Conversion" coloumn.
After getting the year values for each row I was able to create a Piviot Table to analyze the Theater campaign outcomes based on the launch dates.
By applying the right filters I was able to get the data for the number of successful, failed and canceled theater campaigns in each month of the year
and later create a chart to help visualize this data. 
 ![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/100486461/183517087-626fc4d3-a692-4cb2-b696-d3e85051b26f.png)
![Outcomes_Based_on_Launch_Date_Excel_1 3](https://user-images.githubusercontent.com/100486461/183517126-2be5ad3f-7c2f-496f-a37c-df64bbdbf42c.png)



### Analysis of Outcomes Based on Goals

In this Analysis I used the COUNTIFS() function to get the exact number of successful, failed, and canceled outcomes for 12 ranges and then created a chart to help visualize this data.
I used the COUNTIFS() function by selecting data from the Kickstarter worksheet for the "Outcome", "Goal" and "Subcatergory" columns. 
After getting the values for Number of Successful, Failed and Canceled outcomes I used the SUM() function to generate the sum for total projects for each years range.
With this data I was able to calculate the percentage for successful, failed, or canceled projects and create a chart to visualize this data.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/100486461/183517048-ecdd8e7d-6640-4d0e-8845-daee9241e8ef.png)

![Parent_Catergory_Outcome_Excel_1 3](https://user-images.githubusercontent.com/100486461/183517210-96227c27-ecaa-411e-a037-92a5ee73cd36.png)


### Challenges and Difficulties Encountered

Initially I had some difficulties creating the chart and getting the right values in the Outcomes Based on Launch Date section. 
I was getting different values for outcome and my chart did not match the one in the example shown in the Module 1 Challenge. 
After doing some research and reviewing my lesson notes I was able to fix this issue and get the right values and chart and successfully finish the project. 


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

Analyzing the Theater Outcomes based on Launch Date I was able to determine that there were mostly successful outcomes and
the least number of canceled outcomes. There was an average number of failed outcomes and each three of these outcome had some flucuations. 


- What can you conclude about the Outcomes based on Goals?

Analyzing the Theater Outcomes based on Goals I was able to determine that there were high percentage of failed outcomes and
the no number of canceled outcomes. There was an average number of successful outcomes and both of these outcome had some flucuations. 

- Limitations of the dataset and recommendation for future projects

A limitation in the dataset is the lack of data on the users. In order for the fundraiser to be successful, the team would need to understand their customers better to build a stronger target audience. Some future improvements could be including the user age and gender details in the dataset which can help us better understand the customer base. The team can create a pivot table and pivot chart that shows the campaign outcomes based on the customer ages. Are the campaigns directed towards younger audiences more successful than the campaigns directed towards older audiences?
