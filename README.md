# 🏍️ Motorcycle Parts Sales Analysis | SQL

## 📌 Project Overview

This project focuses on analyzing wholesale motorcycle parts sales data using SQL.

The objective is to evaluate net revenue across different product categories, months, and warehouses to support data-driven business decisions.

The project was completed as part of DataCamp's **Analyzing Motorcycle Part Sales** project.

## 🎯 Project Objectives

- Analyze wholesale sales performance.
- Calculate net revenue by product category.
- Compare monthly sales performance.
- Evaluate revenue across different warehouses.
- Identify high-performing product categories.

## 🛠️ Tools & Technologies

- SQL
- PostgreSQL
- DataCamp DataLab

**SQL Techniques:**
- SELECT and WHERE
- GROUP BY
- SUM()
- ROUND()
- TO_CHAR()
- ORDER BY

## 📊 Dataset Description

The dataset contains motorcycle parts sales transactions from June to August 2021.

Key variables include:

| Column | Description |
|---|---|
| product_line | Product category |
| date | Transaction date |
| warehouse | Warehouse location |
| client_type | Retail or Wholesale |
| total | Total transaction amount |
| payment_fee | Payment processing fee |
| payment | Payment method |

## 🔍 Data Analysis Process

### 1. Data Exploration

Explored the sales dataset to understand its structure, available variables, and transaction records.

### 2. Data Filtering

Filtered the dataset to include only wholesale transactions.

### 3. Revenue Calculation

Calculated net revenue according to the DataCamp project requirements by subtracting the sum of payment fees from total sales.

### 4. Revenue Aggregation

Grouped sales by product category, month, and warehouse to compare revenue performance.

### 5. Results Organization

Sorted the results by product category, month, and net revenue in descending order within each product-month group.

## 📈 Key Findings

The analysis highlighted differences in wholesale revenue across product categories and warehouse locations.

Based on the aggregated results:

- **Frame & Body** generated the highest total wholesale revenue.
- **Suspension & Traction** was the second-highest revenue-generating category.
- Revenue varied across warehouses and months.
- The Central warehouse generated the highest Braking System revenue in June.

These findings demonstrate how SQL can support sales performance monitoring and business reporting.

## 📁 Project Files

- `notebook.ipynb` — SQL queries and analysis workflow.
- `motorcycle.jpg` — Project illustration.

## 🚀 Skills Demonstrated

- SQL Data Analysis
- Data Aggregation
- Sales Performance Analysis
- Revenue Reporting
- Business Analytics
- Data-Driven Decision Making

## 📚 Project Source

**DataCamp — Analyzing Motorcycle Part Sales**

https://www.datacamp.com/projects/1574

*This project was completed for educational and
