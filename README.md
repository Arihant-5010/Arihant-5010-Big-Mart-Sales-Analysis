# Arihant-5010-Big-Mart-Sales-Analysis
This project provides a comprehensive analysis of D-Mart's sales data using Python. The goal is to derive actionable business insights by cleaning the data, performing exploratory data analysis (EDA), and visualizing patterns related to sales, profit, customers, and regions.

Business problem-
**How can D-Mart identify key drivers of high-profit transactions and optimize product, regional, and customer strategies to boost overall profitability using historical sales data and predictive modeling**



*** Project Workflow************
 1. Data Cleaning & Preprocessing
    Checked for null values

** Explored dataset structure **

 Dropped unnecessary columns to simplify analysis
 
 Converted Order Date and Ship Date to datetime format
 
 Checked and removed duplicate records
 
 Handled outliers using IQR (Interquartile Range) method
 
 Created boxplots for all numerical columns to visualize data spread

**Data Visualization & Analysis**

** Sales & Profit Overview**
 
**Sales Distribution** – Distribution of sales values across all transactions

**Profit Distribution** – Understanding overall profit trends

**Sales vs Profit (Scatter Plot)** – Relationship between sales and profit

**Category-Level Insights**

**Sales by Category**

Profit Distribution by Category

Sales Contribution by Category


**Time-Series Trends**

Monthly Sales Trend

Monthly Sales and Profit Trends

Seasonal Trends in Sales and Profit

Regional & Customer Insights

Sales by Region and Segment

Sales and Profit by Region

Top 10 Cities by Profit

**Product Performance**

Top 10 Products by Sales

**Tools Used**
Python (Pandas, Matplotlib, Seaborn)
Jupyter Notebook for step-by-step analysis


** Key Insights**

**Sales & Profit Correlation**: Higher sales do not always translate to higher profit.

**Top Categories**: Technology contributes the most to sales and profit.

**Seasonal Patterns**: Notable increase in sales during end-of-year months.

**Customer Segments**: Consumer and Corporate segments show different profit margins.

**Regional Differences**: Western and Southern regions drive more sales compared to others.

**Modeling:**

**Applied Random Forest Classifier to train the model.**

Split the data into training (80%) and testing (20%) sets.

**Evaluation Metrics:**

**Accuracy**: 94.99%

**Precision**: 0.91 for High Profit

**Recall**: 0.77 for High Profit

**F1-Score**: 0.83 for High Profit

 **Results**
The model achieved 94.99% accuracy and effectively identified high-profit transactions with precision and recall that balanced performance for both classes.

The F1-score for high-profit transactions was 0.83, showcasing a strong ability to predict profitable transactions.
