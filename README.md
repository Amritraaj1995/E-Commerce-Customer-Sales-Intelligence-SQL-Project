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
### Screenshot 1-Total_revenue
<img width="1304" height="592" alt="Total_revenue" src="https://github.com/user-attachments/assets/052a12b1-7e0d-4380-adf5-b6e6e6641365" />

-----
- ### Top customer: Rahul — ₹82,000
- Rahul contributed approximately **21.9%** of overall revenue.
  ### Screenshot 2-Customers_revenue
  <img width="1310" height="647" alt="Customers_revenue" src="https://github.com/user-attachments/assets/b1755d87-6c42-434a-a336-cd43fc9d44f0" />

-----
- **Electronics** generated ₹3,44,000, contributing approximately **91.88%** of total revenue.
- **Accessories** generated ₹30,400, contributing approximately **8.12%**.
  ### Screenshot 3-Category wise revenue
  <img width="1298" height="630" alt="Category wise revenue" src="https://github.com/user-attachments/assets/85aee057-6d0f-4633-9845-3b4db647c0a4" />

-----
- **Laptop** was the highest-revenue product with ₹1,65,000.
  ### Screenshot 4-HIGHEST REVENUE PRODUCT
  <img width="1303" height="635" alt="HIGHEST REVENUE PRODUCT" src="https://github.com/user-attachments/assets/90714531-561d-4968-90d1-416e5e4b50cb" />

-----
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
