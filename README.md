#  Sales Performance Dashboard – Power BI

##  Project Overview

An interactive Power BI dashboard designed to analyze sales, profit, orders, quantity, and product performance using a Superstore-style sales dataset.

##  Tools Used

- Power BI
- Power Query
- DAX
- Excel

##  Dashboard Features

- Total Sales
- Total Profit
- Total Orders
- Total Quantity
- Profit Margin
- Monthly Sales Trend
- Sales by Category
- Sales by Region
- Sales by Segment
- Sales by Sub-Category
- Profit by Category
- Top 10 Products by Sales
- Sales by State – Shape Map

##  Interactive Filters

- Year
- Region
- Category
- Segment

##  Data Cleaning

Data was cleaned and transformed using Power Query.

- Removed blank rows
- Removed duplicate Order IDs
- Checked missing values
- Corrected data types
- Prepared data for analysis

##  DAX Measures

```DAX
Total Sales = SUM(Table1[Sales])

Total Profit = SUM(Table1[Profit])

Total Orders = DISTINCTCOUNT(Table1[Order ID])

Total Quantity = SUM(Table1[Quantity])

Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)
