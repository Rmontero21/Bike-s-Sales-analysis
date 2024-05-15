# Toman's Bike Sales Analysis

### Project Overview and Objetives
---

This data analysis project aims to provide insights into the sales performance of Bike renting company over the past 2 years.  

- Sales Analysis: Analyze sales data to identify, seasonal trends, and customer buying behaviors to understand if it's possible to increase the prices the next year.
- Customer Segmentation: Segment customers based on demographics.
- Inventory Optimization: Optimize inventory levels by forecasting demand, identifying slow-moving products, and ensuring optimal stock levels to meet customer demand
- Performance Monitoring: Monitor key performance indicators (KPIs) such as sales revenue, and profitability trends, hourly and Seasonal revenue to track business performance and identify areas for improvement.



### Data Sources

The datasets that I used for this analysis are the "bike_share_yr_0.csv" and "bike_share_yr_1.csv" files each of them represents the sales made in 2021 and 2022, containing detailed information about each sale made by the company, aditional, I have the "cost_table.csv" which contains the prices and COGS (Cost of goods sold).

### Tools

- Excel - Data Cleaning
- SQL Server - Create the database / Data Analysis
- PowerBI - Connect PowerBI to the Database / Data Visualization


### Data Cleaning/Preparation

In the initial data preparation phase, we performed the following tasks:
1. Data loading and inspection.
2. Handling missing values.
3. Data cleaning and formatting.

### Exploratory Data Analysis

The EDA involved exploring the sales data to answer key questions, such as:

- What is the overall Revenue?
- Which are the profitability trends?
- What are the peak sales periods?

### Data Analysis

Include some interesting code/features worked with

```sql
SELECT * FROM table1
WHERE cond = 2;
```

### Results/Findings

The analysis results are summarized as follows:
1. The company's sales have been steadily increasing over the past year, with a noticeable peak between March and October 2022.
2. There's a peak of users during the evening around the 17:00 and 18:00 hours.
3. Casual customers represents only the 18.83% of the total user.
4. Total revenue in 2021 is 4.96M with a profitability of 3.42M.
5. Total revenue in 2022 is 10.23M with a profitability of 7.03M.

### Recommendations

Based on the analysis, we recommend the following actions:
- Conservative increase might be prudent to avoid hitting a price ceiling where demand starts to drop. An increase of 10-15% could test the market's response without risking a significant loss of customers.
- If the price was $4.99, a 10% increase would set the new price at $5.49, and 15% increase would be $5.74

Strategy:

- Market Analysis: Market research to understand custumer satisfaction, potential competitive changes, and the overall economic enviroment.
- Segmented Pricing Strategy: Consider different prices for casual vs registered users.
