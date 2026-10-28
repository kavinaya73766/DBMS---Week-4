# E-Commerce Order Management System

## Project Overview
The E-Commerce Order Management System is a database project developed using SQL. It manages customer orders, purchased products, order details, and order status. It helps organize order information and generate useful sales reports.

## Objectives
- To create and manage customer orders.
- To store order dates, total amounts, and order statuses.
- To manage multiple products within a single order.
- To update and delete order records.
- To generate customer order history and sales reports.
- To maintain data integrity using primary keys, foreign keys, and constraints.

## Technologies Used
- **Database:** MySQL
- **Language:** SQL

## Database Tables
1. **Customer** – Stores customer information.
2. **Product** – Stores product details.
3. **Category** – Stores product categories.
4. **Seller** – Stores seller information.
5. **Inventory** – Maintains product stock information.
6. **Orders** – Stores customer order information.
7. **Order_Details** – Stores products, quantities, and prices for each order.

## Features
- Create and manage customer orders.
- Insert order and product details.
- Calculate the total order amount using quantity and price.
- Update order status, such as PENDING, SHIPPED, DELIVERED, and CANCELLED.
- Modify product quantities in orders.
- Delete order details and eligible order records.
- Generate customer order history.
- Calculate total sales and average order value.
- Display the number of orders and total quantities sold for products.
- Calculate total spending for each customer.

## Database Relationships
- One customer can place many orders.
- One order can contain multiple order details.
- One product can appear in multiple order details.
- One category can contain multiple products.
- One product can have multiple inventory records.
- One seller can have multiple inventory records.

The `Order_Details` table connects orders and products and supports multiple products in one order.

## SQL Concepts Used
- CREATE DATABASE and CREATE TABLE
- INSERT, UPDATE, and DELETE
- SELECT and JOIN
- Aggregate functions: SUM(), AVG(), and COUNT()
- GROUP BY and ORDER BY
- Primary keys and foreign keys
- NOT NULL, UNIQUE, DEFAULT, and CHECK constraints
- Subqueries

## Conclusion
The E-Commerce Order Management System demonstrates how SQL can be used to build and manage a relational database. It helps maintain accurate order records, manage purchased products, and retrieve useful information through SQL queries.
