# 📊 E-Commerce Sales Analysis Using Google BigQuery

## 📌 Project Overview

This project focuses on analyzing e-commerce sales data using **Google Cloud BigQuery**. An e-commerce company receives approximately 1,000 orders daily. The objective is to analyze sales performance, identify top-performing products, understand customer purchasing behavior, and generate monthly sales reports.

This project demonstrates practical SQL skills and data analysis techniques used in Junior Data Engineering.

## 🎯 Project Objectives

- Identify duplicate orders and clean the dataset.
- Calculate total and net revenue.
- Identify the top 3 products in each region.
- Find inactive customers.
- Identify customers purchasing continuously for 3 months.
- Generate Customer Lifetime Value (CLV) reports.
- Analyze monthly sales performance.
- Filter products based on unit price and purchase month.
- Identify customers purchasing the same product multiple times.
- Generate product-wise monthly sales reports.

## 🛠️ Technologies Used

- **Google Cloud Platform (GCP)**
- **Google BigQuery**
- **SQL**
- **Google Cloud Console**

## 📂 Dataset Structure

The e-commerce dataset contains the following columns:

| Column Name | Description |
|---|---|
| order_id | Unique order identifier |
| customer_id | Customer identifier |
| order_date | Date of purchase |
| product_id | Product identifier |
| product | Product name |
| quantity | Number of items purchased |
| unit_price | Price per item |
| region | Customer region |
| status | Order status |

## 📊 Tasks Performed

### Task 1: Remove Duplicate Orders
Identified and removed duplicate order records using SQL.

### Task 2: Calculate Net Revenue
Calculated net revenue using quantity and unit price while considering completed orders.

### Task 3: Top 3 Products in Each Region
Used SQL window functions and ranking techniques to identify the top 3 products in each region.

### Task 4: Identify Inactive Customers
Analyzed customer purchase history to identify customers who have not purchased recently.

### Task 5: Customers Purchasing Continuously for 3 Months
Identified customers who made purchases continuously across three months.

### Task 6: Customer Lifetime Value (CLV)
Generated customer-level reports based on total orders, total quantity, lifetime value, and first and last purchase dates.

### Task 7: Monthly Sales Analysis
Calculated monthly revenue and order counts to understand sales performance.

### Task 8: Products with Unit Price Below ₹10,000
Filtered products with unit prices below ₹10,000 for a particular month.

### Task 9: Repeat Purchase Analysis
Identified customers who purchased a particular product multiple times within six months.

### Task 10: Product-Wise Monthly Sales Report
Generated reports containing:
- Product name
- Total quantity sold
- Total orders
- Total sales revenue

## 📈 Key Learning Outcomes

- Hands-on experience with Google BigQuery.
- Writing SQL queries for real-world business scenarios.
- Data cleaning and duplicate removal.
- Aggregate functions such as SUM(), COUNT(), and MAX().
- Filtering and grouping using WHERE, GROUP BY, and HAVING.
- Using window functions and ranking techniques.
- Customer behavior and sales analysis.
- Generating business intelligence reports.

## 🚀 Conclusion

This project helped me gain practical experience in Google BigQuery and SQL-based data analysis. I learned how to transform raw e-commerce order data into meaningful business insights that support sales analysis, customer segmentation, and business decision-making.

## 👨‍💻 Author

**Gorlamandala Nanda Sai**

- 🎓 B.Tech – Artificial Intelligence & Machine Learning
- 💻 Aspiring Junior Data Engineer
- ☁️ Interests: AWS, GCP, SQL, Python, ETL Pipelines and Data Engineering

[GitHub Profile](https://github.com/Nandasai2004)
