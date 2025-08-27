Retail Sales Analysis - SQL Project

📋 Project Overview

This SQL project focuses on analyzing retail sales data to extract valuable business insights. The project includes data cleaning, exploration, and analysis of sales transactions to answer key business questions and identify trends.

🗃️ Database Schema

Table Name: retail_sales

Column	Type	Description

transactions_id	INT	Primary key, unique transaction identifier

sale_date	DATE	Date of the sale

sale_time	TIME	Time of the sale

customer_id	INT	Unique customer identifier

gender	VARCHAR(15)	Customer gender

age	INT	Customer age

category	VARCHAR(15)	Product category

quantiy	INT	Quantity purchased

price_per_unit	FLOAT	Price per unit

cogs	FLOAT	Cost of goods sold

total_sale	FLOAT	Total sale amount

🧹 Data Cleaning Process

The project includes comprehensive data cleaning:

Removal of records with NULL values in critical columns (age, gender, category, quantity, cogs, total_sale)

Verification of data completeness after cleaning

Initial data exploration to understand dataset characteristics

🔍 Key Analysis Performed

1. Basic Metrics

Total number of sales transactions

Count of unique customers

Product categories available

2. Business Questions Answered

Sales on specific dates (e.g., 2022-11-05)

High-quantity clothing sales in November 2022

Total sales by category

Average age of Beauty category customers

High-value transactions (>1000)

Transaction patterns by gender and category

Monthly sales performance and best-selling months

Top 5 customers by total spending

Unique customer count per category

Order distribution across daily shifts (Morning, Afternoon, Evening)

🛠️ SQL Features Used

Data Definition: CREATE TABLE, DROP TABLE

Data Manipulation: SELECT, WHERE, GROUP BY, ORDER BY

Aggregate Functions: COUNT, SUM, AVG, ROUND

Window Functions: RANK() OVER()

Date/Time Functions: EXTRACT(), TO_CHAR()

CTEs: WITH clauses for complex queries

Conditional Logic: CASE statements

Data Cleaning: NULL handling and data validation

📊 Insights Generated

Sales performance across different product categories

Customer demographic analysis

Temporal patterns in purchasing behavior

Identification of high-value customers

Seasonal/monthly sales trends

Shift-based order distribution analysis

🚀 How to Use

Execute the SQL script to create the retail_sales table

Load your retail sales data into the table

Run the individual query blocks to generate specific insights

Modify queries as needed for your specific analysis requirements

📈 Potential Business Applications

Inventory management optimization

Customer segmentation and targeting

Sales strategy development

Promotional campaign planning

Staff scheduling based on peak hours

Product category performance analysis


