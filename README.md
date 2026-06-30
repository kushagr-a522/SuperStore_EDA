# SuperStore_Sales-Analysis
> Status: In Progress (Started June 29, 2026, Targeted completion: July 10, 2026)

## Overview
Analysis of superstore sales data (51,000+ records) to uncover revenue trends, profit drivers, and regional performance insights.

## Tools Used
- Python (NumPy, Pandas, Matplotlib, Seaborn)
- SQL
- Power BI

## Dataset
- 51,000+ orders
- Columns: {'order_id', 'order_date', 'ship_date', 'ship_mode', 'customer_name',
       'segment', 'state', 'country', 'market', 'region', 'product_id',
       'category', 'sub_category', 'product_name', 'sales', 'quantity',
       'discount', 'profit', 'shipping_cost', 'order_priority', 'year'],
      dtype='object'}

## Business Questions Answered
- WHich region geenrates highest revenue?
- Which products are most/least profitable?
- How does discount affect profit?
- What are the monthly sales trends?

## Key Insights
*(Will be updated as analysis progresses)*

## Project Structure
- 'SuperStoresOders.csv' - raw dataset
- 'Superstore_sales_analysis.ipynb' - Python analysis notebook
- 'Superstore_Dashboard.pbix' - Power BI Dashboard

## Progress
- [x] Dataset loaded into Power BI
- [x] Date columns formatted correctly - (Power BI)
- [x] First visual: Sales by Region
- [ ] Python data cleaning (nulls, duplicates, data types)
- [ ] Exploratory Data Analysis (EDA) - (Python)
- [ ] SQL queries for business questions
- [ ] Profit & discount analysis
- [ ] Full Power BI dashboard with KPIs
- [ ] Business insights write-ups
