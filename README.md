# Walmart Sales Data Analysis - SQL Project

## Overview
This project focuses on analysing Walmart's sales data to identify top-performing branches and products, explore sales patterns across various products, and understand customer behaviour. The goal is to improve sales strategies. The dataset used in this analysis comes from the Kaggle Walmart Sales Forecasting Competition.

## Project Goals
The primary objective of this project is to extract insights from Walmart's sales data, examining the key factors that affect sales across different branches and customer segments.

## Dataset Overview
The data for this project is sourced from the Kaggle Walmart Sales Forecasting Competition. It includes sales transactions from three Walmart branches located in Mandalay, Yangon, and Naypyitaw. The dataset consists of 17 columns and 1000 rows

## Key Areas of Analysis
### 1. Product Analysis
•	Investigate different product lines to identify the top performers.
•	Highlight potential areas for improvement in underperforming product lines.

 ### 2. Sales Analysis
•	Study sales trends to understand the effectiveness of current sales strategies.
•	Recommend adjustments based on sales data to enhance business performance.

### 3. Customer Analysis
•	Segment customers based on their buying behaviour and trends.
•	Assess the profitability of various customer segments.

## Approach
### 1. Data Wrangling
1.	Analyse the dataset to detect and handle any missing values.
2.	Create the necessary database tables and import the dataset.
3.	Ensure that no NULL values exist in the data by enforcing the `NOT NULL` constraint during table creation.

### 2. Adding Key Columns
   Introduce new columns to generate insights from the existing data:
1.	Time of the day: Classify transactions into Morning, Afternoon, and Evening to determine when sales peak.
2.	Day of the week: Extract the day of the week (e.g., Mon, Tue) to analyse branch activity based on weekdays.
3.	Month Name: Extract the month of the year to identify which months have the highest sales and profits.

### 3.  Exploratory Data Analysis (EDA) 
   - Perform in-depth data exploration to answer specific business questions and objectives.

## Business Questions to Address

### General Questions
1.	How many cities are represented in the dataset?
2.	Where is each Walmart branch located?

 ### Product Analysis
1.	How many distinct product lines exist in the dataset?
2.	What is the most popular payment method?
3.	Which product line generates the highest sales?
4.	Which month saw the highest total revenue?
5.	Which product line incurred the highest VAT?
6.	Which branch performs above average in product sales?
7.	What is the gender-based distribution of product purchases?
8.	What is the average customer rating for each product line?

 ### Sales Analysis
1.	How do sales vary by time of day and day of the week?
2.	Which customer type contributes the most revenue?
3.	Which city has the highest VAT percentage?
4.	Which customer type pays the most VAT?

 ### Customer Analysis
1.	What are the unique customer types in the dataset?
2.	What is the most frequent customer type?
3.	What is the distribution of customer gender across branches?
4.	During which time of day do customers leave the most ratings?
5.	Which days of the week have the best average ratings per branch?

## Conclusion
By analysing Walmart's sales data, we can gain valuable insights into product performance, customer behaviour, and sales trends. These insights will help optimize sales strategies and enhance business outcomes for Walmart branches.
 
