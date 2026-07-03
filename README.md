# SuperStore-Sales-Analysis
> Status: In Progress (Started June 29, 2026, Targeted completion: July 10, 2026)

## Overview
Analysis of superstore sales data (51,000+ records) to uncover revenue trends, profit drivers, and regional performance insights.

## Tools Used
- Python (NumPy, Pandas, Matplotlib, Seaborn)
- SQL (SQLite)
- Power BI

## Dataset
- 51,000+ orders
- **Columns:** order_id, order_date, ship_date, ship_mode, customer_name,
       segment, state, country, market, region, product_id,
       category, sub_category, product_name, sales, quantity,
       discount, profit, shipping_cost, order_priority, year

## Business Questions Answered
- Which region generates highest revenue?
- Which products are most/least profitable?
- How does discount affect profit?
- What are the yearly sales trends?

## Key Insights
1. Central region leads in total sales ($1.9M) but Canada is the least profitable market.
2. Canon imageCLASS 2200 Copier is the highest profit product at $25,199.
3. Cubify CubeX 3D Printer is worst performer — losses $8,879 on just $675 in sales.
4. Office Supplies → Appliances sub-category has the best profit margin at 36.11%.
5. Heavy discounting (40%+) is causing $627K+ in total profit loss — biggest finding.
6. Business shows consistent YoY growth from 2011 to 2014.

## Project Structure
SuperStore_EDA/
* charts/
  - 1_sales_by_region.png
  - 2_profit_by_region.png
  - 3_yearly_trend.png
  - 4_category.png
  - 5_discount_profit.png
  - 6_top10_products.png
  - 7_heatmap.png
  - Sales_complete_overview.png
  - Product_analysis.png

* SuperStoreOrders.csv
* SuperStore_Cleaned.csv
* Superstore_Dashboard.pbix
* Superstore_sales_analysis.ipynb
* README.md
* .gitignore

## Dashboard Preview
### Page 1 - Sales Overview
![Page 1](charts/Sales_complete_overview.png)

### Page 2 - Product Analysis
![Page 2](charts/Product_analysis.png)

## Key Business Recommendation
Capping all discounts at 20% company-wide could potentially recover $600K+ in lost profit annually while maintaining sales volume.

## Progress
- [x] Dataset loaded into Power BI
- [x] Date columns formatted correctly - (Power BI)
- [x] First visual: Sales by Region
- [x] Python data cleaning (nulls, duplicates, data types)
- [x] SQL queries for business questions
- [x] Exploratory Data Analysis (EDA) - (Python)
- [x] Profit & discount analysis
- [x] Full Power BI dashboard with KPIs
- [ ] Business insights write-ups
