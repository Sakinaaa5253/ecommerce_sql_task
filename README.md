# Ecommerce SQL Analysis Project

## 📊 Objective
This project demonstrates SQL skills applied to an eCommerce relational database. The main goal is to extract, analyze, and optimize queries using SQL to gain business insights from structured data.

## 📁 Contents

- `ecommerce_analysis.sql` – SQL script containing multiple queries
- `output1.png` to `output4.png` – Screenshots of sample query results
- `Ecommerce_SQL_Task.zip` – Packaged file with all contents

## 🛠️ Tools Used

- SQL (compatible with MySQL, PostgreSQL, SQLite)
- Mock screenshots generated for demonstration
- Sample schema assumed includes tables: `Customers`, `Orders`, `OrderDetails`, `Products`

## 🧠 SQL Concepts Covered

✅ Basic Querying:
- `SELECT`, `WHERE`, `ORDER BY`, `GROUP BY`

✅ Joins:
- `INNER JOIN` used for connecting tables

✅ Aggregate Functions:
- `SUM`, `AVG`, `COUNT`

✅ Subqueries:
- Used to filter customers above average order counts

✅ Views:
- Created a view (`ProductRevenue`) for total revenue per product

✅ Index Optimization:
- Created indexes on `Orders.CustomerID` and `OrderDetails.ProductID` for faster query performance
