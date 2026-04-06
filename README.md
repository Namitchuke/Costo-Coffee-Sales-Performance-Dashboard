# Costo-Coffe-Sales-Performance-Dashboard

# Costo-Coffe-Sales-Performance-Dashboard

This repository contains a comprehensive sales analysis project for a coffee shop, using MySQL for data processing and Power BI for creating a dynamic, interactive dashboard. The goal is to analyze sales data to uncover key trends, track performance metrics, and provide actionable insights.

-----

## Project Overview

This project provides an end-to-end analysis of coffee shop sales data with the goal of transforming raw data into actionable business intelligence. The primary objective is to develop a comprehensive Power BI dashboard that empowers stakeholders to make informed, data-driven decisions. By analyzing key metrics related to sales, orders, and customer behavior, this project aims to identify peak sales periods, uncover best-selling products, understand store level performance, and highlight opportunities for growth.

The analysis delves into month-over-month trends, daily and hourly sales patterns, and the performance of different product categories. The technical workflow involves using MySQL for robust back end data processing including cleaning, transformation, and complex calculations and Power BI for front end visualization. The final deliverable is an intuitive and interactive dashboard designed to help the coffee shop optimize staffing, manage inventory more effectively,

## Tools Used

  * **Database:** MySQL
  * **Data Visualization:** Microsoft Power BI

## Methodology

The project was executed in two main parts:

### Part 1: Data Preparation and Analysis with MySQL

1.  **Data Preparation:** The raw sales data file was reviewed and prepared for database import.
2.  **Database Setup:** A new database was created in MySQL to house the sales data.
3.  **Data Import & Cleaning:** The prepared file was imported into the database. Post-import, the data was cleaned, and data types were corrected (e.g., converting text to dates and numbers) to ensure data integrity.
4.  **SQL Querying:** SQL queries were written to extract insights and calculate the KPIs required for the dashboard. This involved complex functions to analyze month-over-month trends, daily patterns, and product performance.

### Part 2: Dashboard Creation in Power BI

The results from the SQL queries were used to build a comprehensive sales dashboard in Power BI. The dashboard is designed to be interactive, allowing users to filter data (e.g., by month) and drill down into specific details.

## Key Performance Indicators (KPIs)

The dashboard focuses on three core areas of analysis, each with month-over-month (MoM) comparisons:

1.  **Total Sales Analysis:**

      * Total sales for the selected month.
      * Month-over-month sales growth percentage.
      * The absolute difference in sales compared to the previous month.

2.  **Total Orders Analysis:**

      * Total number of orders for the selected month.
      * Month-over-month growth in the number of orders.
      * The absolute difference in order count compared to the previous month.

3.  **Total Quantity Sold Analysis:**

      * Total quantity of items sold in the selected month.
      * Month-over-month growth in quantity sold.
      * The absolute difference in quantity sold compared to the previous month.

## Dashboard Visualizations

The Power BI dashboard includes the following charts and visuals to provide a clear view of the business performance:

1.  **Calendar Heat Map:** A dynamic calendar showing sales volume for each day of the selected month. Darker shades indicate higher sales, with tooltips providing detailed metrics (Sales, Orders, Quantity).

2.  **Sales by Weekdays vs. Weekends:** A comparative analysis to understand how sales patterns differ between weekdays and weekends.

3.  **Sales by Store Location:** A breakdown of sales performance by store location, including MoM growth metrics to identify which locations are improving.

4.  **Daily Sales with Average Line:** A line chart displaying daily sales for the selected month, with an average sales line to quickly identify high-performing and low-performing days.

5.  **Sales by Product Category:** A visual analysis of sales across different product categories to identify which categories are the top revenue drivers.

6.  **Top 10 Products by Sales:** A bar chart highlighting the 10 best-selling products, allowing for quick identification of customer favorites.

7.  **Sales by Day and Hour Heat Map:** A heat map visualizing sales concentration by day of the week and hour of the day, perfect for optimizing staffing and operations.

## SQL Concepts Applied

This project utilized a wide range of SQL functionalities to perform the analysis, including:

  * **Date/Time Functions:** `STR_TO_DATE`, `MONTH`, `DAY`, `DAYOFWEEK`, `HOUR`
  * **Aggregate Functions:** `SUM`, `COUNT`, `AVG`, `MAX`, `MIN`
  * **Window Functions:** `LAG` (for MoM calculations)
  * **Table Operations:** `ALTER TABLE`, `UPDATE TABLE`, `CHANGE COLUMN`
  * **Clauses & Statements:** `WHERE`, `GROUP BY`, `ORDER BY`, `CASE`, `LIMIT`
  * **Advanced Concepts:** Subqueries, Joins, and Aliasing.
