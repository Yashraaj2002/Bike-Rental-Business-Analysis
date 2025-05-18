# 🚴‍♀️ Bike Rental Shop – SQL Case Study

## 📘 Overview
This project simulates a real-world scenario where a bike rental shop owner, Emily, wants to make data-driven decisions to grow her business. You’ve been brought on as an SQL analyst to extract key insights from the shop’s database using SQL.

The dataset includes customer, bike, rental, and membership data, and the goal is to provide business insights such as rental revenue trends, bike availability, pricing strategies, and customer behavior.

## 🧠 Objectives
Analyze rental trends and revenue
Optimize pricing strategies
Segment customers based on activity
Provide detailed reports by time and product category

## 🗂️ Database Schema
The database consists of 5 tables:

### Table	Description
customer	Stores customer information (ID, name, email)
bike	Contains details about bikes (model, category, price, status)
rental	Tracks rental transactions (duration, total_paid, timestamps)
membership_type	Lists different membership plans
membership	Logs customer membership purchases

### SQL scripts to create and populate the tables are included in:
📄 DATASET-Bike_Rental_Case_Study.txt

## ❓ Business Questions
Emily, the owner of the bike rental shop, wants data-driven answers to the following questions:

Bike Inventory by Category
➤ How many bikes does the shop own in each category?
Show only categories with more than 2 bikes.

Memberships by Customer
➤ How many memberships has each customer purchased?
Include customers with 0 memberships. Sort by the highest count.

New Discounted Rental Prices
➤ What will the new prices be after applying winter discounts?
Calculate and display old vs. new prices (hourly and daily) for each bike based on its category.

Bike Availability and Rentals by Category
➤ How many bikes are currently available and how many are rented, broken down by category?

Rental Revenue by Time
➤ What is the total revenue from rentals by:
Month
Year
All-time
Display subtotals and grand totals.

Membership Revenue by Type and Time
➤ What is the total revenue from memberships for each combination of year, month, and membership type?

2023 Membership Revenue with Totals
➤ For 2023, what is the membership revenue by type and month, including subtotals and grand total?

Customer Segmentation by Rental Count
➤ How are customers segmented based on the number of rentals?
Group customers into: fewer than 5, between 5 and 10, more than 10

### Query solutions are provided in:
📄 SOLUTION-Bike_Rental_Case_Study.txt

# 🛠️ SQL Techniques Used
JOIN, GROUP BY, ORDER BY
CASE statements
Aggregate functions (COUNT, SUM, ROUND)
Date and time formatting (TO_CHAR)
Advanced grouping (GROUPING SETS, ROLLUP, CUBE)

# 📦 Project Files
File	Description
README.md	Project documentation
DATASET-Bike_Rental_Case_Study.txt	SQL scripts to create and populate the database
SOLUTION-Bike_Rental_Case_Study.txt	SQL queries for all business questions


# 🔍 Insights Gained
Real-world SQL reporting and analysis
Application of advanced grouping techniques
Practice in generating business dashboards and KPIs using raw SQL
