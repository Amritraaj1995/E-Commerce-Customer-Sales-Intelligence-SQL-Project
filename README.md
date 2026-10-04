# E-Commerce-Customer-Sales-Intelligence-SQL-Project
## Project Overview
This project analyzes **e-commerce customer, product, category, and sales data** using SQL to generate meaningful business insights.
The objective was to understand **revenue performance, customer behavior, product performance, category contribution, and sales trends** using real-world Data Analyst-style business questions.

## Business Objectives
- Identify top-performing products and categories
- Analyze customer revenue and purchasing behavior
- Identify repeat and high-value customers
- Calculate Average Order Value (AOV)
- Analyze customer contribution to overall revenue
- Analyze category-wise revenue contribution
- Identify top products within each category
- Analyze monthly revenue trends

## 🗂️ Dataset
The project uses three relational tables:

### customers
- customer_id
- customer_name

### products
- product_id
- product_name
- category
- price

### orders
- order_id
- customer_id
- product_id
- quantity
- order_date

## 🧠 SQL Concepts Used
- SELECT / WHERE
- GROUP BY / ORDER BY
- Aggregate Functions — SUM(), COUNT(), AVG()
- JOIN
- CASE
- HAVING
- #### CTEs
- ROW_NUMBER()
- RANK()
- #### Window Functions
- PARTITION BY
- SUM() OVER()
- #### Percentage calculations
- **Date functions using** TO_CHAR()

## 📊 Key Business Insights
- ### Total revenue: ₹3,74,400
- ### Top customer: Rahul — ₹82,000
- Rahul contributed approximately **21.9%** of overall revenue.
- **Electronics** generated ₹3,44,000, contributing approximately **91.88%** of total revenue.
- **Accessories** generated ₹30,400, contributing approximately **8.12%**.
- **Laptop** was the highest-revenue product with ₹1,65,000.
- The analysis also identified customers with significant revenue contribution and repeat-order behavior.

## 🔍 Key Analysis Performed
1. Product-wise revenue analysis
2.Product-wise units sold
3. Customer Average Order Value
4. Repeat customer analysis
5. Latest order identification
6. High-value customer classification
7. Top product within each category
8. Customer contribution to company revenue
9. Customer revenue percentage
10. Monthly revenue trend
11. Category revenue contribution
12. Category-wise top product analysis
13. Overall category revenue percentage
14. Customer contribution within category revenue

## 💡 Business Recommendation
The analysis shows that the business is **highly dependent on the Electronics category**, which contributes the majority of revenue.

The company could focus on:

- Increasing sales of Accessories
- Cross-selling Accessories to Electronics customers
- Reducing dependency on a small number of high-value customers
- Targeting repeat customers with personalized offers

## 🛠️ Tools
**Database:** Oracle SQL
**Environment:** Oracle APEX SQL Workshop
**Analysis:** SQL
