Problem Statement :-

This project combines customer sales and churn datasets to analyze sales performance, customer purchasing behavior, and churn patterns. The objective is to help businesses identify high-value customers, monitor sales trends, and understand factors that may contribute to customer churn.

Businesses often maintain sales and customer information in separate systems. Without integrating these datasets, it becomes difficult to answer important business questions such as:

- Who are the highest revenue-generating customers?
- Which products contribute the most to revenue?
- Which regions perform better in terms of sales?
- What is the customer churn rate?
- Are low-tenure customers more likely to churn?
- How can the business improve customer retention and sales performance?

This project addresses these questions by combining sales and churn data into a single analytical dataset.

Dataset :-

#Sales Dataset
- Date
- Customer ID
- Product
- Quantity
- Price
- Region

#Customer Churn Dataset
- Customer ID
- Tenure
- Monthly Charges
- Total Charges
- Churn Status

Tools Used :-

Python (Pandas) — Data cleaning and analysis
Matplotlib — Data visualization
PostgreSQL / PgAdmin — SQL querying and data extraction

Steps Performed :-

#Data Preparation
- Imported sales and customer churn datasets
- Checked dataset information & Validated missing values
- Converted Date column into datetime format
- Renamed Customer_ID column for consistency
- Merged both datasets using CustomerID

#Feature Engineering
Created additional business metrics:
- Revenue = Quantity × Price
- Month extracted from Date
- Average Monthly Spend

#Exploratory Data Analysis
Performed analysis on:
- Total Revenue
- Revenue by Customer
- Average Order Value
- Total Orders
- Monthly Revenue Trend
- Best Selling Products
- Revenue by Region
- Customer Churn Rate

#Data Visualization
Created visualizations for:
- Monthly Revenue Trend
- Revenue by Region
- Top Selling Products
- Customer Churn Distribution

#Pivot Table Analysis
Generated a pivot table to compare Revenue by:
- Region
- Product

Key Insights :- 

After analyzing the given data of the sales these are the insights, 
- Identified customers generating the highest revenue.
- Determined the best-selling products based on quantity sold.
- Compared revenue contribution across different regions.
- Calculated overall customer churn rate.
- Observed that customers with lower tenure are more likely to churn.
- Measured average order value and customer purchase behavior.

Recommendations :-
- Develop retention strategies for high-value customers.
- Promote top-performing products to maximize revenue.
- Investigate low-performing regions and implement targeted marketing campaigns.
- Focus on onboarding and engaging new customers to reduce churn.
- Monitor monthly revenue trends to improve inventory and sales planning.
