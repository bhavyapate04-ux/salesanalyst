# 🛒 Zepto Sales & Inventory Analysis Using SQL

![SQL](https://img.shields.io/badge/SQL-Database-blue)
![Data Analysis](https://img.shields.io/badge/Project-Data%20Analysis-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview

This project focuses on analyzing Zepto's product, pricing, discount, and inventory data using SQL.

The main objective is to extract meaningful business insights from product and inventory records through SQL queries. The project includes database creation, data exploration, data cleaning, and business-oriented analysis.

It helps understand product availability, discount strategies, category-wise revenue, pricing patterns, and inventory distribution.

## 🎯 Project Objectives

- Analyze product and inventory information.
- Identify products with the highest discounts.
- Compare MRP and discounted selling prices.
- Analyze in-stock and out-of-stock products.
- Calculate estimated revenue across product categories.
- Identify high-value products.
- Understand inventory weight distribution.
- Generate insights to support business decisions.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| SQL | Database querying and analysis |
| PostgreSQL | Database management |
| CSV | Dataset storage |
| GitHub | Project version control |

## 📂 Project Structure

```text
salesanalyst/
│
├── PROJECT (SQL).sql
│   └── SQL queries for data analysis
│
├── zepto.csv
│   └── Product and inventory dataset
│
└── README.md
    └── Project documentation
```

## 📊 Project Workflow

### 1. Database Creation
- Created the Zepto database table.
- Defined appropriate column names and data types.
- Used a primary key to identify products.

### 2. Data Exploration
- Counted total records.
- Retrieved sample product records.
- Identified missing values.
- Explored unique product categories.
- Compared in-stock and out-of-stock products.
- Identified duplicate product names.

### 3. Data Cleaning
- Identified products with zero prices.
- Removed invalid MRP records.
- Converted prices from paise to rupees.
- Prepared data for further analysis.

### 4. Business Analysis

The project answers important business questions using SQL.

| No. | Business Question | SQL Concepts |
|---|---|---|
| 1 | Find the top 10 best-value products based on discounts. | ORDER BY, LIMIT |
| 2 | Identify high-MRP products that are out of stock. | WHERE, AND |
| 3 | Calculate estimated revenue for each category. | SUM(), GROUP BY |
| 4 | Find products with MRP above ₹500 and discounts below 10%. | WHERE |
| 5 | Identify the top 5 categories with the highest average discount. | AVG(), GROUP BY |
| 6 | Calculate price per gram for products weighing at least 100g. | ROUND(), ORDER BY |
| 7 | Classify products into Low, Medium, and Bulk weight categories. | CASE WHEN |
| 8 | Calculate total inventory weight per category. | SUM(), GROUP BY |

## 🧠 SQL Concepts Practiced

- CREATE TABLE
- DROP TABLE
- SELECT
- DISTINCT
- WHERE
- ORDER BY
- GROUP BY
- HAVING
- LIMIT
- COUNT()
- SUM()
- AVG()
- ROUND()
- CASE WHEN
- UPDATE
- DELETE
- Primary Key
- Data Cleaning

## 📈 Key Analytical Areas

**Product Analysis**
- Product category distribution.
- Duplicate product identification.
- Best-value product identification.

**Pricing Analysis**
- MRP and discounted selling price comparison.
- Discount percentage analysis.
- Price per gram calculation.

**Inventory Analysis**
- Stock availability.
- Out-of-stock product identification.
- Category-wise inventory weight.

**Revenue Analysis**
- Estimated revenue by category.
- Product-level pricing analysis.
- Category-wise discount comparison.

## 💡 Business Value

This project demonstrates how SQL can help businesses:

- Understand inventory availability.
- Evaluate discount strategies.
- Identify pricing opportunities.
- Analyze category-wise revenue.
