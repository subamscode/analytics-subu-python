# SQL-python Ecommerce Project
E-commerce analytics project leveraging SQL for data querying and Python (Pandas, NumPy, Matplotlib/Seaborn) for data cleaning, EDA, revenue analysis, cohort analysis, and business KPI reporting.

Project Overview

This project focuses on analyzing E-commerce sales data using SQL and Python to extract meaningful business insights.

The goal of this project is to:

Clean and preprocess raw e-commerce data

Perform exploratory data analysis (EDA)

Write SQL queries to analyze business metrics

Generate insights for decision-making

Visualize results using Python

This project demonstrates practical skills in:

SQL querying

Data Analysis

Data Cleaning

Business Insight Extraction

Data Visualization

🛠️ Tech Stack

Python

SQL (MySQL / PostgreSQL)

Pandas

NumPy

Matplotlib / Seaborn

Jupyter Notebook

MySQL Connector / SQLAlchemy

📂 Project Structure
SQL-Python-Ecommerce-Project/
│
├── data/
│   └── ecommerce_data.csv
│
├── sql/
│   └── ecommerce_queries.sql
│
├── notebooks/
│   └── analysis.ipynb
│
├── screenshots/
│   └── results.png
│
└── README.md

🔄 Project Workflow / Process
1️⃣ Data Collection

Imported E-commerce dataset (CSV format)

Loaded data into MySQL database

2️⃣ Database Creation

Created database and tables using SQL

Defined primary keys and relationships

Imported CSV data into SQL tables

3️⃣ Data Cleaning (Python)

Removed null values

Handled duplicates

Corrected data types

Converted date columns

4️⃣ SQL Analysis

Performed business-driven queries such as:

Total Revenue Calculation

Monthly Sales Trends

Top Selling Products

Top Customers by Revenue

Region-wise Sales

Category Performance

Order Status Analysis

5️⃣ Data Visualization

Used Python libraries to visualize:

Monthly Revenue Trends

Sales by Category

Top 10 Products

Customer Distribution

🧠 Key Business Questions Answered

list all uniqe cities where customers are located

count the number of orders placed in 2027

calculate the percentage of orders that were paid in installments

Calculate the number of order per month in 2018

Calculate the moving average of order values for each customer over thir order history


Identify the top 3 customers who spent the most money in each year.

📊 Results & Analysis
🔹 Revenue Insights

Identified total revenue generated during the period.

Found peak revenue months using time-series analysis.

🔹 Product Performance

Top-selling products were identified using SQL aggregation.

Certain categories significantly outperform others.

🔹 Customer Analysis

A small percentage of customers contributed to a large portion of revenue.

High-value customers were identified for potential targeting.

🔹 Regional Insights

Some regions showed consistent high performance.

Underperforming regions were identified for strategy improvement.

🚀 How to Run This Project
Step 1: Clone Repository
git clone https://github.com/yourusername/SQL-Python-Ecommerce-Project.git
cd SQL-Python-Ecommerce-Project

Step 2: Install Required Libraries
pip install pandas numpy matplotlib seaborn mysql-connector-python sqlalchemy

Step 3: Setup Database

Create database in MySQL

Run ecommerce_queries.sql to create tables

Import CSV data into tables

Step 4: Run Jupyter Notebook
jupyter notebook


Open analysis.ipynb and run all cells.

📈 Example SQL Query
SELECT category, SUM(sales) AS total_sales
FROM orders
GROUP BY category
ORDER BY total_sales DESC;

📌 Skills Demonstrated

SQL Joins

GROUP BY & Aggregations

Subqueries

Data Cleaning in Python

Exploratory Data Analysis

Data Visualization

Business Insight Generation
