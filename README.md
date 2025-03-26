# Car Sales Analysis

## Table of Contents
- [Project Overview](#project-overview)

### Project Overview
This data analysis project aims to provide insights into car sales performance over the past year. By analyzing key sales metrics, customer preferences, and regional trends, we seek to identify patterns, optimize sales strategies, and support data-driven decision-making to enhance overall dealership performance.

### Data Sources
Sales Data: The primary dataset used for this analysis is the "carsales_data.csv" file, which contains detailed information about each car sold.


### Tools
- PowerBI - Data Cleaning, Data Analysis, Creating reports

### Data Cleaning/Preparation
In the initial data preparation phase, the following tasks were performed:
1. Data loading and inspection.
2. Data cleaning and formatting.

### Exploratory Data Analysis
EDA involved exploring the sales data to answer key questions, such as:
- How are the total sales performance?
- How has the average selling price changed over time?
- How many cars have been sold, and what are the trends (body style, color, and region)?
- Which dealer regions and companies are driving or lagging in sales?
 
### Data Analysis
Include some interesting code/features worked with
‘’’sql
SELECT * FROM table1
WHERE cond = 2;

### Results/Findings
The analysis results are summarized as follows:
1. The company's sales have been steadily increasing over the past year, with a noticeable peak during the holiday season.
2. Product Category A is the best-performing category in terms of sales and revenue.
3. Customer segments with high lifetime value (LTV) should be targeted for marketing efforts.

### Recommendations
Based on the analysis, we recommend the following actions:
- Invest in marketing and promotions during peak sales seasons to maximize revenue.
- Focus on expanding and promoting products in Category A.
- Implement a customer segmentation strategy to target high-LTV customers effectively.

### Limitations
I had to remove all zero values from budget and revenue columns because they would have affected the accuracy of my conclusions from the analysis. There are still a few outliers even after the omissions but even then we can still see that there is a positive correlation between both budget and number of votes with revenue
