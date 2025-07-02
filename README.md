# Customer-Bike-Purchase-Analysis-Excel

By Samah Mohammed 

This project is a data analysis of biker sales using Microsoft Excel by Alex the Analyst YouTube Channel.

## What’s inside?
- Cleaned raw data structured for analysis.
- Pivot tables to summarize sales by region, product, and time.
- An interactive dashboard with slicers and charts for insights.


## Questions(KPIs)
•	Who buys more bikes: married or single customers?
•	How do sales differ between men and women?
•	What is the average age of customers making purchases?
•	Is there a correlation between education level and bike purchases?
•	Which age group purchases the most bikes?


## 1. Data Cleaning
- First I separate the original data and coped the data into new sheet called working sheet in order to not miss with the original work 

## 1.1 removed any duplicates faced

![image](https://github.com/user-attachments/assets/e2538892-2797-455a-bb33-f98ca9729826)

## 1.2 Make the naming of data more Clear  
![image](https://github.com/user-attachments/assets/0cba7c14-899e-4bfa-85c6-ac1b872dbc18)

## 1.3 create new column if needed & use any rule needed to work it our

Here I created one called 'Age Brackets' column so we can have a categorize for the age 
Then I used the rule of IF Nested Statements so the ages are from 30 any lower are adolescent and from 31 and more are Middel age and from 55 and up are Old

![image](https://github.com/user-attachments/assets/0f21caa1-7290-4db4-ab37-ff130790d468)


## 2. Pivot Tables
In order to visualize the data I created pivot tables for : 

## 2.1 Avg Income Per Purchase Pivot table

Key Findings: 
•	Customers who purchased a bike have a higher average income ($57,963) than those who did not ($54,875).
•	This trend holds true for both genders, with males who purchased a bike showing the highest average income ($60,124).
Implications:
 Income is a strong predictor of bike purchase likelihood. Marketing efforts could be optimized by targeting higher-income segments.

![image](https://github.com/user-attachments/assets/fd488c85-dbc9-447a-bf21-2fa9dbc312ad)


## 2.2 Customer Commute pivot table

![image](https://github.com/user-attachments/assets/7ddaa1ca-30d8-4235-8286-2fb583ee741b)

Key Findings : 

The (0-1 Miles) has the highest number of bike purchases (200 'Yes' vs. 166 'No'), indicating a strong tendency for biking in very short commute distances.
For distance longer than 2-5 Miles (e.g., 5-10 Miles and More Than 10 Miles), the number of customers who did NOT purchase a bike outnumbers those who did, suggesting reduced utility for longer distances.

Implications: 
•	The "0-1 Miles" commute range is a primary target market for bike sales

## 2.3 Customer Age Brackets Pivot Table 
![image](https://github.com/user-attachments/assets/8cd5b6f7-269d-4e1f-b6e4-b0cb740191c6)

Key Findings:
Middle age bracket which are people from 31 and more represents the largest customer segment (726 total customers) and the highest number of bike purchases
While Adolescent which are 30 and lower customers have the lowest overall count (85) and the fewest bike purchases (30 'Yes' vs. 55 'No'). This segment shows a lower tendency for bike ownership within this dataset.

And for the Old age people who are 55 and above shows a significant number of purchases (85 'Yes' vs. 104 'No'), placing them between Adolescents and Middle Age in terms of purchase.

Implications: 
•	The "Middle age" is the primary target market for bike sales, suggesting marketing strategies should heavily focus on this group

## 3. Dashboard created by Using a Slicer

Inserted a slicer for Marital status, Region, Edication

![image](https://github.com/user-attachments/assets/05196948-5b1b-46d8-9557-421311fd5ce8)

Made it for all the pivot tables so it will be easier to analysis it 

![image](https://github.com/user-attachments/assets/eab1c753-7637-4010-8a0c-d66f0ae42fe0)

Some of the insights that I gained: 
Married people in Europe (both Male and Female ) tend to pursers a bike and have better income
Also married people who purchased pike are Middel age category and very low on Adolescent 
And again customer commute with 0-1 are most to purchase a pike 

![image](https://github.com/user-attachments/assets/f3061036-a730-47e5-959d-9493929c69bd)

Here females that are single less likely to buy bike and Females, those who did not purchase a bike ($36,136) have a higher average income than those who did ($29,070).

![image](https://github.com/user-attachments/assets/c0461e7c-6d8a-4d01-a598-ce4171f86e39)


Here we can see that Bachelors Edication, For Females with a Bachelor's degree, those who did NOT purchase a bike ($66,818 average income) have a higher average income than those who DID purchase ($61,625).
And for males the average incomes for purchasers ($59,326) and non-purchasers ($65,694) are also quite close
And even though Bachelors people have more salary they tend to not buy bikes

![image](https://github.com/user-attachments/assets/2aa4820b-2a14-4b9d-bb7c-4d6cb9893c4d)

On the other hand here the people who have Education on Partial High School although they have less average of income rather than the  Bachelors .($32,000) for females who pursed and ($58,000) for male , they tend to purchase more than Bachelors

## This is the Full Dashboard :

![image](https://github.com/user-attachments/assets/180ac65f-a3aa-49e5-964f-164f166cc148)


