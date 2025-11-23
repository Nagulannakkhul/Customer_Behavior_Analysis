# Customer_Behavior_Analysis
Data analytics project of  Customer_Behavior_Analysis using Python, SQL, PowerBI.
📊 Customer Shopping Behavior Analysis – Summary
1. Overview

This project analyzes customer shopping behavior using Python, SQL, and Power BI.
It covers data loading, EDA, cleaning, SQL-based insights, and dashboard creation.

2. Dataset

File: customer_shopping_behavior.csv

Contains customer demographics, purchases, product categories, ratings, and discounts.

3. Tools Used

Python: Pandas, NumPy, Matplotlib

Database: PostgreSQL, PgAdmin4

Visualization: Power BI

Data Loading: SQLAlchemy

4. Data Loading
df = pd.read_csv("customer_shopping_behavior.csv")


Loaded into PostgreSQL using SQLAlchemy for running SQL queries.

5. EDA

Distribution of purchase amounts

Category-wise spending

Customer demographics

Rating patterns & discount impact

6. Data Cleaning

Missing value handling (median imputation)

Outlier removal

Standardizing column names

Data type corrections

7. SQL Analysis

Queries answered:

Revenue by gender

Top categories

High-value customers

Review rating patterns

8. Power BI Dashboard

Interactive dashboard includes:

Sales overview

Customer segments

Category performance

Discount & revenue insights

9. Key Results

Electronics & Clothing lead in revenue

Young adults shop the most

Discounts increase order volume

Higher ratings link to repeat purchases
