# E-Commerce Sales & Revenue Analysis

## Overview
This project focuses on analyzing sales, revenue, and customer behavior for an e-commerce platform across six product categories: Agriculture, Grocery, Health, Homecare, Pet, and Skincare. The analysis includes exploratory data analysis (EDA), feature engineering, sales forecasting, and customer behavior analysis to provide insights and help stakeholders make data-driven decisions.

---

## Table of Contents
1. [Prerequisites](#prerequisites)
2. [Project Steps](#project-steps)
3. [Key Insights](#key-insights)
4. [Visualization Dashboards](#visualization-dashboards)
5. [Conclusion](#conclusion)


---

## Prerequisites

To run this project, you’ll need:

1. **Python 3.7+**
2. **MySQL Database**
3. **Python Libraries:**
   - pandas
   - numpy
   - pymysql
   - matplotlib
   - seaborn
   - statsmodels
   - scikit-learn
   - plotly

4. **Tableau Desktop** for visualizations.

---
   
## Project Steps

1. **Data Extraction**
   - Using pymysql to connect to the MySQL database.
   - Extract data for each product category and store in Pandas DataFrames.
2. **Data Cleaning**
   - Handle missing values, e.g., replacing blank ratings with 0.
   - Parse date fields to extract month and year.
   - Convert ratings like "4.5 out of 5 stars" to numerical values.
3. **Exploratory Data Analysis (EDA)**
   - Conduct univariate, bivariate, and multivariate analyses.
   - Explore relationships between product categories, sales, and revenue.
4. **Feature Engineering**
   - Calculate fields such as Average Order Value (AOV) and revenue per product.
   - Segment products into price bands (Low, Mid, High, Premium).
5. **Customer Behavior Analysis**
   - Differentiate between new and returning customers.
   - Analyze customer demographics and purchase patterns.


---

## Key Insights

1. **Sales Performance**
   - Agriculture and Pet categories drive most of the revenue.
   - Skincare products have the highest Average Order Value (AOV).
2. **Customer Behavior**
   - 74.8% of revenue comes from new customers, indicating strong sales.
   - Also we want to improve the customer to return back and purchace with us.
3. **Revenue Trends**
   - Revenue spikes during March and November.
   - Strong month-over-month growth in Agriculture and Skincare.
  

---

## Visualization Dashboards

Using Tableau and PowerBI, the following dashboards were created:

1. **Sales Performance Dashboard:**
   - Shows total sales, average order value, and product-wise sales.
2. **Revenue Analysis Dashboard:**
   - Visualizes monthly revenue growth and category-specific revenue.
3. **Customer Segmentation Dashboard**
   - Segments customers into new and returning categories
  
**Tableau Dashboard :**  https://public.tableau.com/app/profile/gowtham.g8004/viz/OrganicEcommerceStore/Dashboard1?publish=yes

**PowerBI Dashboard :**  https://app.powerbi.com/view?r=eyJrIjoiZmE1NTdmNjYtZDU0OC00ZGUxLTljOWMtYzVlYTFjY2QzNzllIiwidCI6ImZlYmNlODJhLTViNmEtNDc0NS05NmU3LTA1MDg3ZjUyZmQyZCJ9

---

## Conclusion

This analysis provides actionable insights into the e-commerce platform's performance, highlighting the importance of customer retention, strategic promotions, and pricing. The results inform data-driven decisions to improve product offerings, customer engagement, and revenue growth.
