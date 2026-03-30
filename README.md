E-Commerce Sales Analysis 📊
Project Overview

This project performs Exploratory Data Analysis (EDA) on an e-commerce dataset to understand sales trends, category performance, and stock distribution. The analysis includes data cleaning, preprocessing, grouping, and visualization to extract business insights.

The project is implemented using Python, Pandas, NumPy, and Matplotlib in a Jupyter Notebook.

Objectives

The main objectives of this project are:

Understand overall sales performance
Analyze monthly sales trends
Identify top performing months
Analyze category-wise sales
Identify top and least performing categories
Analyze stock quantities by category
Visualize insights using charts
Technologies Used
Python
Pandas
NumPy
Matplotlib
Jupyter Notebook
Dataset

The dataset used in this project:

ecommerce.csv

It contains information such as:

Order Date
Category
Sales
Quantity
Stock
Month-Year
Steps Performed in Analysis
1. Import Libraries

Libraries like pandas, numpy, and matplotlib are imported for analysis and visualization.

2. Load Dataset

The dataset is loaded using pandas:

df = pd.read_csv('ecommerce.csv')

3. Data Exploration
View first rows
View last rows
Dataset description
Dataset info
Check missing values

4. Data Preprocessing

Converted Order Date to datetime format:

df['Order_date'] = pd.to_datetime(df['Order_date'])

Created Month-Year column for monthly analysis.

5. Monthly Sales Analysis

Grouped data by Month-Year to analyze sales trends and identify Top 3 Sales Months.

6. Category Analysis

Performed:

Category-wise sales
Category-wise stock quantity
Top 3 categories by sales
Least 3 categories by sales

7. Data Visualization

Used bar charts to visualize:

Monthly sales
Category sales
Top and least categories


Key Insights
Identified top performing months in sales
Identified best selling categories
Identified least performing categories
Stock distribution across categories analyzed
