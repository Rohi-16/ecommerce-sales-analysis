# E-Commerce Sales Data Cleaning & Analysis


## Overview
End-to-end data cleaning and exploratory data analysis (EDA) 
of a messy real-world e-commerce sales dataset using Python.

## Problem Statement
The raw dataset had multiple quality issues — inconsistent 
category names, missing values, wrong data types, duplicate 
rows, and corrupted entries. The goal was to clean the data 
and extract meaningful business insights.

## Dataset
- Source: [Kaggle - Messy E-Commerce Sales Dataset](https://www.kaggle.com/datasets/kandeelai22/messy-e-commerce-sales-dataset)
- Raw: 103 rows, 11 columns
- Clean: 96 rows, 14 columns

## Tools & Libraries
- Python, Pandas, Matplotlib
- Kaggle Notebooks

## Data Cleaning Steps
- Stripped leading spaces from column names
- Removed duplicate rows
- Fixed data types (Order_Date, Quantity, Price)
- Handled missing values (median imputation + Unknown fill)
- Recalculated missing Total values
- Standardized inconsistent category names
- Removed corrupted row with negative Total (-196741)

## Key Insights
- 📚 **Books** is the top revenue category (₹40,296)
- 💳 **Cash on Delivery** is the most preferred payment method (31.2%)
- 📅 **February** had the highest monthly sales
- 🚨 **Delivery rate is only 10.4%** — serious operational concern
- 🛒 **Average order value: ₹1,612**
