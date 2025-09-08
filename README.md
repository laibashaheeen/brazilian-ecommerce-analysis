# 📊 Olist E-Commerce Analytics Dashboard

## 📌 Project Overview

This project analyzes the Brazilian E-Commerce Public Dataset by Olist to uncover insights into sales, customer behavior, payments, logistics, and customer satisfaction.
The final output is an interactive Power BI dashboard designed for stakeholders to monitor KPIs and support data-driven decisions.

## 🎯 Problem Statement

“How can Olist track sales, customer satisfaction, and logistics performance to improve business decisions?”

## 🚀 Objectives

Monitor total revenue, orders, and customers

Track delivery performance (on-time vs. late)

Analyze sales trends across time, categories, and regions

Identify best-performing product categories.

Understand payment preferences

Measure customer satisfaction with reviews

Identify repeat vs. new customers
Track delivery efficiency and problem areas.

## 📂 Dataset

Brazilian E-Commerce Public Dataset by Olist (8 CSV files):

Orders

Order Items

Products

Customers

Sellers

Payments

Reviews

Product Category Translations

## 🛠 Data Cleaning & Preprocessing (Python / Jupyter Notebook)

Steps performed:

Loaded all 8 CSVs into Pandas

Selected useful columns only (dropped irrelevant ones)

Filtered orders → kept only delivered orders

Created new features:

total_order_value = price + freight_value

delivery_days = delivered_date – purchase_date

late_delivery_flag (on-time vs late)

Repeat vs. New customer flag

Merged tables → one clean analysis-ready CSV

Exported final dataset → olist_cleaned.csv

## 📊 Dashboard Layout (Power BI)
1. Top Section – KPIs

Total Revenue

Total Orders

Total Customers

Avg. Delivery Time

Avg. Review Score

2. Sales Overview

Revenue over time (line chart)

Orders by payment type (stacked column)

Revenue by product category (treemap)

3. Customer Insights

Orders by state (bar chart)

Revenue by location (map)

New vs repeat customers (donut chart)

4. Operations & Feedback

On-time vs late deliveries (clustered column)

Avg delivery days (gauge)

Avg review score by category (bar chart)

Word Cloud of review comments

## ⚡ Key Insights

[Example] 60% of payments are via credit card

[Example] Late deliveries reduce average review score by ~1 star

[Example] Electronics generate highest revenue, but fashion has most orders

[Example] São Paulo is the top customer state by revenue

📁 Repository Structure
📦 olist-ecommerce-analytics
 ┣ 📂 data
 ┃ ┣ olist_orders_dataset.csv
 ┃ ┣ olist_order_items_dataset.csv
 ┃ ┗ ... (other raw csvs)
 ┣ 📂 notebooks
 ┃ ┗ data_cleaning_and_merging.ipynb
 ┣ 📂 dashboard
 ┃ ┗ powerbi_dashboard.pbix
 ┣ 📂 exports
 ┃ ┗ olist_cleaned.csv
 ┣ README.md
 ┗ requirements.txt

## 🛠 Tools Used

Python (Pandas, NumPy) → data cleaning & preprocessing

Jupyter Notebook → exploration & processing

Power BI → dashboard visualization

GitHub → version control & portfolio showcase

## 🎯 Outcome

The dashboard enables Olist stakeholders to:

See sales trends and customer satisfaction

Identify bottlenecks in delivery performance

Analyze regional sales patterns

Understand customer behavior (repeat vs new)

## 📷 Dashboard Preview

(Insert screenshots or GIF of your Power BI dashboard here)
