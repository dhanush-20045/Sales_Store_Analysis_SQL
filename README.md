# Retail Sales Analysis – SQL Project


## Project Overview

This SQL-based retail sales project explores transactional purchase data to uncover patterns in customer behavior, product performance, and operational trends. The analysis transforms raw sales data into actionable insights that can drive decisions in marketing, inventory management, and customer relationship strategies.


## Project Dataset

The dataset contains retail transaction details with the following attributes:


1) **Customer Information**: Customer ID, name, age, gender  


2) **Product Information**: Product ID, name, category  


3) **Transaction Metrics**: Quantity, price, status (delivered, cancelled, returned)  


4) **Temporal Data**: Purchase date, time of purchase  


5) **Operational Attributes**: Payment mode


## Key Observations

1) Duplicate records and missing values were identified and cleaned.  


2) Gender and payment mode fields contained inconsistent values.  


3) Customer-level and product-level patterns emerged clearly after transformation.


## Use Case

Analyze purchasing patterns, product demand, cancellation trends, and customer segmentation to optimize retail sales strategy.


## Business Case Study: Retail Sales Optimization

This project analyzes retail sales data to uncover actionable insights that can support multiple business functions. The dataset captures individual transactions including customer demographics, product details, purchase timing, and payment preferences.


## Key Focus Areas

1) Identify top-selling and most-cancelled products  


2) Analyze revenue contribution by product category and customer  


3) Discover purchase behavior by time of day and age group  


4) Calculate return/cancellation rates  


5) Measure Customer Lifetime Value (CLTV)  


6) Track monthly sales trends  


7) Evaluate payment mode preferences


## Potential Business Applications

1) **Customer Targeting** – Identify top-spending customers and loyal buyers  


2) **Inventory Planning** – Prioritize in-demand products and categories  


3) **Operational Staffing** – Plan resource allocation based on peak purchase times  


4) **Product Strategy** – Improve low-rated or high-return product lines  


5) **Marketing Optimization** – Personalize offers by age group or location  


6) **Checkout Optimization** – Streamline the most-used payment modes


## Technical Approach


### The project applies key SQL techniques including:


1) Data import and transformation via `BULK INSERT`  


2) Duplicate handling using `ROW_NUMBER()` and CTEs  


3) Column renaming and standardization (`sp_rename`, `UPDATE`)  


4) Handling null and missing values using dynamic SQL and filtering  


5) Time-based aggregation using `DATEPART`, `FORMAT`  


6) Grouping and segmentation using `CASE`, `GROUP BY`  


7) Revenue and performance calculations via aggregation functions


## Analysis Focus Areas


1) **Product Insights**:  
   - Top-selling products  
   - Frequently cancelled items  
   - Revenue by category  


2) **Customer Insights**:  
   - Age-wise contribution  
   - High-value customers (CLTV)  


3) **Time-Based Trends**:  
   - Peak purchase hours  
   - Monthly sales trend  


4) **Operational Metrics**:  
   - Preferred payment modes  
   - Cancellation/return percentages  


## Business Insights Generated


1) Evening is the peak time for customer purchases  


2) Products like Milk and Rice are top-selling, while Butter faces frequent cancellations  


3) Customers aged 26–35 are the highest spenders  


4) November and December see the highest sales volume  


5) Credit Cards are the most preferred payment mode  


6) Top customers exhibit high revenue and repeat purchases, highlighting potential for loyalty campaigns  


7) Certain product categories have high return rates and may need quality review


## Technical Environment


- **Primary Database**: Microsoft SQL Server  


- **Development Tool**: SQL Server Management Studio (SSMS)  


- **Query Language**: T-SQL  


- **Import Method**: BULK INSERT  


- **Analysis Output**: Cleaned datasets and query results (can be integrated into Excel or Power BI)


## Implementation Notes

The project follows a structured approach beginning with raw data import and cleaning, followed by comprehensive SQL querying to extract business intelligence. Each step builds modular outputs that can easily be visualized using external tools like Excel or Power BI.


All logic, filtering, and transformations were implemented using SQL for reproducibility and performance, making this solution scalable and ready for automation or dashboard integration.
