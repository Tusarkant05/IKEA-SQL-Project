# IKEA Retail Sales SQL Project
![](https://github.com/Tusarkant05/IKEA-SQL-Project/blob/main/Ikea-logo.png)

Welcome to the IKEA Retail Sales SQL Project! This project leverages a detailed dataset of millions of sales records, product inventory, and store information across IKEA's global operations. The analysis focuses on uncovering sales trends, product performance, and inventory management insights to assist in data-driven decision-making.

## Table of contents
- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Database Schema](#database-schema)
- [Business Problems](#business-problems)
- [SQL Queries & Analysis](#sql-queries--analysis)
- [Contact Me](#contact-me)

---

## Introduction
The IKEA Retail Sales SQL project demonstrates the use of SQL to analyze retail dat, including sales records, store performance, product trends, and inventory status. Using a robust schema, this project answers critical business questions and provides actionable insights to optimize IKEA's operational efficiency and profitability.

## Project Structure

1. **SQL Scripts**: Contains SQL queries to create the database schema, populate tables, and perform analyses.
2. **Dataset**: Include sales data, product information, store details, and inventory records.
3. **Analysis**: SQL queries to slove key business problems, leveraging advanced SQL techniques like joins, windows functions, aggregations, and subqueries.

---

## Database Schema

Here’s an overview of the database structure:

### 1. **Products table**
- **product_id**: Unique identifier for each product (primary key).
- **product_name**: Name of the product.
- **category**: Category to which the product belongs.
- **subcategory**: Subcategory of the product.
- **unit_price**: price per unit of the product.

### 2. **stores Table**
- **store_id**: Unique identifier for each store (primary key_.
- **store_name**: Name of the store.
- **city**: City where the store is located.
- **country**: Country where the store is operates.

### 3. **Sales Table**
- **Order_id**: Unique identifier for each sales order (primary key).
- **order_date**: Date when the order was placed.
- **Product_id**: Foreign key referencing *products* table.
- **qty**: Quantity of the product sold.
- **discount_percentage**: Discount applied to the order.
- **unit_price**: Price per unit of the product at the time of sales.
- **store_id**: Foreign key referencing *stores* table.

### 4. **Inventory Table**
- **inventory_id**: Unique identifier for each inventory records (primary key).
- **product_id**: Foreign key referencing the *products* table.
- **current_stock**: Current stock level of the product.
- **reorder_level**: Maximun stock level to trigger a reorder.

## Business Problems
