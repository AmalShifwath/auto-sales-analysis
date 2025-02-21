# Auto Sales Analysis

The purpose of the project is to:
1. Analyze Sales Performance:
o Uncover patterns and trends in historical sales data.
o Assess the impact of deal sizes and other factors on sales revenue.

2. Develop Predictive Insights:
o Build a linear regression model to predict future sales based on key features (QUANTITYORDERED, PRICEEACH).
o Enable data-driven forecasting for inventory management and revenue planning.

3. Provide Decision Support:
o Deliver insights to stakeholders through a predictive dataset exported for Power BI, facilitating visualization and strategic decision-making.


## Intended KPIs
Key Performance Indicators (KPIs) include:

1. Total Sales:
o Overall revenue across transactions.
o Aggregated by time periods (e.g., yearly, monthly).

2. Average Sales per Order:
o Mean revenue per transaction to gauge order profitability.

3. Sales by Deal Size:
o Comparing revenue contributions across deal sizes (Small, Medium, Large).

4. Sales Trends:
o Identifying seasonal or yearly variations in sales patterns.

5. Predictive Accuracy:
o Model evaluation metrics like R-squared and Mean Squared Error (MSE) to assess the quality of the regression model.

## Dataset Summary
The dataset contains 2,747 records of automobile sales data, detailing transaction-level information such as:
  
  - Order details: ORDERNUMBER, ORDERDATE, QUANTITYORDERED, and PRICEEACH.
  
  - Financial metrics: SALES (target variable), MSRP.
  
  - Categorical details: DEALSIZE, STATUS, PRODUCTLINE, and customer information (CITY, COUNTRY, etc.).
  
  - Date and Time: ORDERDATE, enabling time-based analysis.

The dataset provides a comprehensive view of sales transactions, allowing analysis of sales patterns, customer behaviors, and other factors impacting performance.
