📊 Sample Superstore Data Analysis
📌 Project Overview
This project performs data analysis on the Sample Superstore dataset using Python.

The dataset contains information about customer orders, products, sales, discounts, shipping methods, and profits.

The main objective of this project is to analyze the sales and profit performance of different categories, regions, and products using Pandas and Matplotlib.

📂 Dataset
File Name: 1ac96a13-30d2-46e3-b643-97982dfd443a.xlsx

Sheet Name: samplesuperstore

Dataset Size
Rows: 10,194
Columns: 21
🛠️ Technologies Used
Python
Pandas
Matplotlib
Google Colab
Microsoft Excel
📋 Dataset Columns
Column	Description
Row ID	Unique row identification number
Order ID	Unique order identification
Order Date	Date when the order was placed
Ship Date	Date when the order was shipped
Ship Mode	Shipping method used
Customer ID	Unique customer identification
Customer Name	Name of the customer
Segment	Customer segment
Country/Region	Country or region
City	Customer city
State/Province	Customer state or province
Postal Code	Postal code
Region	Sales region
Product ID	Unique product identification
Category	Product category
Sub-Category	Product sub-category
Product Name	Name of the product
Sales	Sales amount
Quantity	Quantity of products ordered
Discount	Discount provided
Profit	Profit generated
🎯 Objectives
The main objectives of this project are:

To understand the structure of the dataset.
To check missing values.
To perform basic statistical analysis.
To calculate total sales.
To calculate total profit.
To calculate total quantity sold.
To analyze sales by category.
To analyze sales by region.
To analyze profit by category.
To identify the top 10 products based on sales.
To visualize the results using charts.
🔍 Data Analysis Performed
1. Data Loading
The Excel dataset is loaded using Pandas.

import pandas as pd

df = pd.read_excel("sample_superstore.xlsx")
