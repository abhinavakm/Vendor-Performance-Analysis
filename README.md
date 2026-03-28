
# Vendor Performance Analysis

Analyzing vendor efficiency and profitability to support strategic purchasing and inventory decisions using SQL, Python, and Power BI.


## Overview

This project evaluates vendor performance and retail inventory dynamics to drive strategic insights for purchasing, pricing, and inventory optimization.
## Business Problem
Effective inventory and sales management are critical in the retail sector. This project aims to address key challenges by focusing on the following objectives:

1.Identify underperforming brands needing pricing or promotional adjustments
2.Determine vendor contributions to sales and profits
3.Analyze the cost-benefit of bulk purchasing
4.Investigate inventory turnover inefficiencies
5.Statistically validate differences in vendor profitability
## Tools and Technologies
SQL (Common Table Expressions, Joins, Filtering)

Python (Pandas, Matplotlib, Seaborn, SciPy)

Power BI (Interactive Visualizations)

GitHub (Version Control)
## Data Cleaning
Removed transactions with:

Gross Profit ≤ 0
Profit Margin ≤ 0
Sales Quantity = 0
Additional processing steps:

Created summary tables with vendor-level metrics
Converted data types
Handled outliers
Merged lookup tables
## Exploratory Data Analysis
Negative or Zero Values Detected:

Gross Profit: Min = -52,002.78 (loss-making sales)
Profit Margin: Min (sales at zero or below cost)
Unsold Inventory: Indicates slow-moving stock
Outliers Identified:

High Freight Costs (up to 257K)
Large Purchase/Actual Prices
Correlation Analysis:

Weak correlation between Purchase Price & Profit
Strong correlation between Purchase Qty & Sales Qty (0.999)
Negative correlation between Profit Margin & Sales Price (-0.179)

## Dashboard
<img width="1612" height="914" alt="image" src="https://github.com/user-attachments/assets/ffd9b513-4082-4631-a9d4-c5655b757187" />
