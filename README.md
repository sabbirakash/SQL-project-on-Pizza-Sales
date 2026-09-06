# 🍕 Pizza Sales SQL Analysis

![SQL](https://img.shields.io/badge/Language-SQL-003B5C?style=for-the-badge&logo=mysql&logoColor=white)
![MySQL](https://img.shields.io/badge/Database-MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Data Analytics](https://img.shields.io/badge/Analytics-Business_Insights-232F3E?style=for-the-badge)

A comprehensive SQL analytics project exploring a relational pizza sales database. This repository contains queries ranging from basic metrics to advanced analytical calculations using CTEs and window functions to derive business-critical insights regarding revenue, ordering trends, and product performance.

---

<p align="center">
  <img src="https://github.com/sabbirakash/SQL-project-on-Pizza-Sales/blob/main/SQL%20queries%20on%20Pizza%20Sales-Banner.jpg" alt="Pizza Sales Analysis SQL Project Banner">
</p>

---

## 📌 Table of Contents
- [Project Overview](#-project-overview)
- [Objectives](#-objectives)
- [Tech Stack](#-tech-stack)
- [Database Schema](#-database-schema)
- [Business Questions Solved](#-business-questions-solved)
- [Key Business Insights](#-key-business-insights)
- [Project Structure](#-project-structure)
- [Learning Outcomes](#-learning-outcomes)
- [Future Enhancements](#-future-enhancements)
- [Author & Contact](#-author--contact)

---

## 📌 Project Overview

This project analyzes transactional data for a pizza restaurant chain using MySQL. The goal is to solve real-world operational and business problems by performing structured queries on product categories, size distributions, peak sales hours, and cumulative revenue performance.

---

## 🎯 Objectives

- **Analyze Performance:** Evaluate revenue metrics and sales volume across product lines.
- **Problem Solving:** Practice translating complex business questions into clean, performant SQL queries.
- **Advanced Querying:** Apply complex joins, subqueries, Common Table Expressions (CTEs), aggregate functions, and window functions.
- **Actionable Insights:** Generate data-driven insights to support product inventory and marketing decisions.

---

## 🛠️ Tech Stack

- **RDBMS:** MySQL
- **SQL Techniques:** Aggregate Functions, Multi-Table Joins, Subqueries, CTEs, Window Functions (`RANK`, `DENSE_RANK`), CASE Statements

---

## 🗂️ Database Schema

The database consists of four normalized tables:

| Table | Description |
| :--- | :--- |
| **`orders`** | Stores transaction-level details including order ID, date, and time. |
| **`order_details`** | Connects orders to specific pizzas along with quantities purchased. |
| **`pizzas`** | Contains unique pizza IDs, size designations, and pricing. |
| **`pizza_types`** | Stores pizza names, category classifications, and ingredients. |

---

## 📊 Business Questions Solved

### 🟢 Basic Analysis
1. Retrieve the total number of orders placed.
2. Calculate the total revenue generated from pizza sales.
3. Identify the highest-priced pizza.
4. Determine the most common pizza size ordered.
5. List the top 5 most ordered pizza types along with their quantities.

### 🟡 Intermediate Analysis
6. Join the necessary tables to find the total quantity of each pizza category sold.
7. Determine the distribution of orders by hour of the day.
8. Find the category-wise distribution of pizzas.
9. Group the orders by date and calculate the average number of pizzas ordered per day.
10. Determine the top 3 most ordered pizza types based on revenue.

### 🔴 Advanced Analysis
11. Calculate the percentage contribution of each pizza category to total revenue.
12. Analyze the cumulative revenue generated over time.
13. Determine the top 3 most ordered pizza types based on revenue for each pizza category using ranking functions.

---

## 📈 Key Business Insights

* **Revenue Drivers:** Identified the top revenue-generating pizza types and calculated category-level percentage contributions to overall turnover.
* **Customer Preferences:** Discovered the most popular pizza size and ranked best-selling pizza types across categories.
* **Peak Demand Hours:** Analyzed hourly order distributions to identify peak operational hours for better staff and inventory scheduling.
* **Cumulative Growth:** Modeled daily revenue trends to track business performance over time.

---

## 🚀 Learning Outcomes

This project provided hands-on execution of core and advanced SQL concepts:
* Multi-table relational joins (`INNER JOIN`, `LEFT JOIN`)
* Data aggregation using `GROUP BY`, `HAVING`, and `ORDER BY`
* Advanced analytical queries using **CTEs** and **Subqueries**
* Complex analytical operations using **Window Functions** (`SUM() OVER()`, `RANK()`)
* Business-oriented reporting and data synthesis

---

## 📌 Future Improvements
*	📊 Power BI Dashboard: Build an interactive visual dashboard connected to this dataset.
*	🐍 Python EDA: Conduct Exploratory Data Analysis (EDA) using Pandas, Seaborn, and Matplotlib.
*	📈 KPI Dashboards: Develop KPI dashboards for business performance reporting.
*	⚡ Performance Optimization: Optimize SQL queries and create indexes for better execution performance.
*	⚙️ Stored Procedures & Views: Create reusable stored procedures and database views for automated analysis.


---

## 👨‍💻 Author
**Sabbir Uddin Akash**
*	Portfolio: [Sabbir Uddin Akash](sabbirakash.github.io)
*	LinkedIn: [Sabbir Uddin Akash](linkedin.com/in/sabbirakash)
*	GitHub: [sabbirakash](github.com/sabbirakash)

---


## ⭐ If you found this project helpful, consider giving it a star on GitHub! It motivates me to build and share more data analytics projects.

