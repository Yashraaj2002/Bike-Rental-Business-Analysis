# 🚴‍♀️ Freedo Bike Rental Shop – SQL Case Study

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


1. How many bikes does the shop own in each category, considering only categories that have more than 2 bikes?   
2. How many memberships has each customer purchased, including those who haven't purchased any, and sorted by the highest membership count? 
3. What are the new discounted rental prices (hourly and daily) for each bike based on its category, along with the original prices for comparison?
4. How many bikes are currently available and how many are rented, shown separately for each bike category?
5. What is the total rental revenue broken down by month, year, and across all years, including subtotals and a final grand total?
6. What is the total membership revenue for every combination of year, month, and membership type?
7. For the year 2023, what is the membership revenue by type and month, including all subtotals and a grand total across all types and months?
8. How are customers segmented based on their rental history, categorized as: ‘fewer than 5’, ‘between 5 and 10’, and ‘more than 10’ rentals, along with the count of customers in each segment?



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
