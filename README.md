# 📊 Olist E-Commerce Analytics Dashboard

## 📌 Project Overview

An interactive Power BI dashboard built on the Olist Brazilian E-commerce dataset, providing insights into revenue trends, customer behavior, product performance, payment preferences, and delivery efficiency to support data-driven decision-making.

## 🎯 Problem Statement

“How can Olist track sales, customer satisfaction, and monitor perfrmance to improve business decisions?”

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

(📝 NOTE: The dataset is uploaded on Google Drive and can be directly accessed via the notebook. If you do not want to run the notebook, you can access the [raw dataset](https://drive.google.com/drive/folders/1_QhnnIgG1JtUz3Np_dsfU5feN7ssS1Iu?usp=sharing)
 and [cleaned dataset](https://drive.google.com/file/d/10gle5RGetvhyTaKCsrTJAufL2_hKKUPR/view?usp=sharing)
 directly.)

## 🛠 Data Cleaning & Preprocessing (Python / Jupyter Notebook)

Steps performed:

Loaded all 8 CSVs into Pandas

Selected useful columns only (dropped irrelevant ones)

Filtered orders → kept only delivered orders

Merged tables → one clean analysis-ready CSV

Created new features:

total_order_value = price + freight_value

delivery_days = delivered_date – purchase_date

late_delivery_flag (on-time vs late)

Repeat vs. New customer flag

Translated reviews into english

Exported final dataset → cleaned_df.csv

## ⚡ Key Insights

88.5% of payments are via credit card

Delivery performance is relatively slow compared to typical e-commerce benchmarks (2–7 days)

beleza_saude is top performing category

São Paulo is the top customer state by revenue

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

<img width="1341" height="757" alt="image" src="https://github.com/user-attachments/assets/1bce35e5-66b4-4951-b006-223532a4d36f" />

<img width="1342" height="756" alt="image" src="https://github.com/user-attachments/assets/ea36cdd6-d7e6-4a99-978e-3cd912c68ccb" />


