Amazon Sales Analysis Dashboard

Overview:

This repository contains a Power BI dashboard developed to analyze Amazon sales data. The dashboard provides actionable insights into sales performance, profit trends, and customer demographics, 
aiding in data-driven decision-making.

The dataset includes:

- Order ID, Order Date, Ship Date, Status
- Customer Name (extracted from email ID)
- Country, City, State
- Category, Product Name, Sales, Quantity, and Profit

Key Features:

- Data Cleaning:  Extracted customer names from email IDs and normalized geographical data.
- Interactive Dashboard:  Visualizations to explore sales trends, category-wise performance, and geographical insights.


Methodology:

1. Data Cleaning:
   - Extracted `Customer Name` from `Email ID`.
   - Split `Geography` into `Country`, `City`, and `State` columns.
   - Removed the redundant `Geography` column.

2. Data Visualization:
   - Created a Power BI dashboard with dynamic slicers for categories, regions, and statuses.
   - Key visuals include Sales Trends, Profitability by Product, and Geographical Sales Analysis.

3. Insights:
   - Top-performing categories and products.
   - Geographical regions contributing to high profitability.
   - Customer-wise order trends.


