# Customer Shopping Behavior Analysis

## Overview

This end-to-end data analytics project analyzes customer shopping behavior to uncover patterns in purchasing habits, product preferences, discount usage, and revenue trends. The goal is to generate actionable insights that can help businesses improve their sales strategy and customer retention.

The project covers the full data analytics workflow — from raw data exploration to an interactive dashboard and a professional presentation.

## Dataset

1. File - customer_shopping_behavior.csv
2. Source - Available in this repository
3. Records - ~3,900 customer transactions
4. Key Columns - Customer ID, Age, Gender, Item Purchased, Category, Purchase Amount, Discount Applied, Subscription Status, Review Rating, Previous Purchases, Shipping Type

The dataset covers customer demographics, product details, and transaction attributes across multiple retail categories.

## Tools Used

1. Python (Pandas) - Data loading, cleaning, and exploratory data analysis (EDA)
2. PostgreSQL - Querying and aggregating data using SQL
3. Power BI - Interactive dashboard and data visualization
4. Microsoft Word - Project report with findings and recommendations
5. Gamma - Professional presentation (PPT)
6. GitHub - Version control and project hosting

## Project Steps

### 1. Data Loading & Exploration (Python

Loaded the dataset using Pandas
Inspected data types, shape, and column names
Checked for missing values and duplicates
Explored basic statistics (mean, median, distribution)


### 2. Data Cleaning (Python)

Removed duplicate rows
Handled null/missing values
Standardized column formats (e.g., text casing, data types)
Created derived columns such as age_group for segmentation


### 3. Exploratory Data Analysis — EDA (Python)

Visualized purchase amount distribution by gender, age group, and category
Analyzed discount usage patterns
Explored review ratings across products
Identified top-performing categories and items


### 4. SQL Analysis (PostgreSQL)

Ran 10 business-focused queries, including:

Total revenue by gender
Customers who used discounts but still spent above average
Top 5 products by average review rating
Subscription vs. non-subscription spending comparison
Customer segmentation: New, Returning, and Loyal
Top 3 products per category using window functions
Revenue contribution by age group

SQL file: customer_behavior_sql_queries.sql



### 5. Dashboard (Power BI)

Built an interactive dashboard with slicers for gender, category, and subscription status
Visualized KPIs: total revenue, average purchase amount, customer count
Included charts for revenue by age group, top products, and discount impact

Dashboard file: customer_behavior_dashboard.pbix



### 6. Report (Microsoft Word)

Documented project objectives, methodology, key findings, and recommendations
Written for a non-technical business audience

Report file: Customer_Shopping_Behavior_Analysis.docx


### 7. Presentation (Gamma)

Created a clean, visual slide deck summarizing the project
Covers problem statement, approach, key insights, and recommendations

Presentation file: Customer-Shopping-Behavior-Analysis.pptx


## Dashboard Preview

<img width="1175" height="641" alt="image" src="https://github.com/user-attachments/assets/1ffe9c1b-a9d8-4055-b8c1-6b701b2c0717" />

Key visuals included:

Revenue by Gender and Age Group
Top 10 Products by Purchase Volume
Discount vs. Non-Discount Spend Comparison
Subscriber vs. Non-Subscriber Revenue
Category-wise Sales Breakdown



## Key Results

1. Top Revenue Group - Loyal customers (10+ previous purchases) contribute the highest revenue
2. Discount Impact - Certain customers used discounts yet still spent above average
3. Subscriber Spending - Subscribed customers showed higher average spend and total revenue
4. Top Product Category - Clothing ranked highest in purchase volume
5. Shipping Preference - Standard shipping was more common but Express had slightly higher average spend
6. Review Ratings - Top-rated products did not always correlate with highest sales volume


## How to Run

### Python Notebook

1. Clone this repository
2. Install required libraries:
   
   import pandas as pd

Open customer_shoppiing_behavior_analysis_.ipynb in Jupyter Notebook or Google Colab
Run all cells from top to bottom


### SQL Queries

1. Set up a PostgreSQL database and create a table named customer
2. Import the dataset from customer_shopping_behavior.xlsx
3. Open customer_behavior_sql_queries.sql in pgAdmin or any PostgreSQL client
4. Run queries individually or all at once

### Power BI Dashboard

1. Download and install Power BI Desktop (free)
2. Open customer_behavior_dashboard.pbix
3. Use the slicers and filters to explore the data interactively



## Repository Structure

📁 Customer-Shopping-Behavior-Analysis
│
├── 📄 README.md
├── 📊 customer_shopping_behavior.xlsx              ← Dataset
├── 📓 customer_shoppiing_behavior_analysis_.ipynb  ← Python EDA notebook
├── 🗄️ customer_behavior_sql_queries.sql            ← SQL queries (PostgreSQL)
├── 📊 customer_behavior_dashboard.pbix             ← Power BI dashboard
├── 📝 Customer_Shopping_Behavior_Analysis.docx     ← Project report
└── 📑 Customer-Shopping-Behavior-Analysis.pptx     ← Presentation


## About

Project Type: Portfolio Project — End-to-End Data Analytics
Domain: Retail / E-Commerce
Skills Demonstrated: Data Cleaning, EDA, SQL (Window Functions, CTEs, Aggregations), Data Visualization, Dashboard Design, Business Reporting


