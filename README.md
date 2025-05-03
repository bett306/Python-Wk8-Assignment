# Python-Wk8-Assignment
# Sales Data Analysis and Visualization (Python)
This project demonstrates a basic but complete data analysis workflow using Pandas and Matplotlib in Python. The dataset used (sample_sales.csv) contains daily sales records of three electronic products: Laptop, Mouse, and Keyboard.

# Tools Used
- Pandas
- Matplotlib
- Jupyter Notebook (Anaconda Environment)

# Process Overview

## 1. Loading and Exploring the Dataset
The dataset (sample_sales.csv) was loaded using pandas.read_csv().
A preview of the dataset was displayed using .head().
Checked for data types and missing values using .info() and .isnull().sum().

## 2. Cleaning the Data
Rows with missing values in critical columns were dropped using .dropna().
This ensures consistent, error-free analysis.

## 3. Basic Data Analysis
Total revenue was computed using .sum().
The best-selling product was identified by grouping data by Product and summing Quantity Sold.
The day with the highest total revenue was found by grouping by Date.
Grouping by product allowed us to compute average quantity sold and average revenue — which revealed patterns like higher sales volume for cheaper items like mice.

# 4. Data Visualization
Several visualizations were created using matplotlib.pyplot:
Line Chart: Daily total revenue over time.
Bar Chart: Average revenue by product.
Histogram: Distribution of revenue values across all transactions.
Scatter Plot: Relationship between quantity sold and revenue per transaction.

## 5. Insights and Observations
Laptops generated the highest revenue but were sold in lower quantities.
Mice had the highest sales volume but lower revenue per item.

# How to Run
Clone the repository
Open Assignment.ipynb in Jupyter Lab or Notebook
Run all cells to see the full analysis and visualizations

