Schema Overview
This project uses a schema named `gold` that includes three core tables:

- `dim_customers`: Contains customer demographic and identity information
- `dim_products`: Stores product details including categories, pricing, and maintenance
- `fact_sales`: Holds transactional sales data such as order dates, quantities, and revenue

Purpose
The SQL queries in this file are designed to analyze sales performance over time, track customer engagement, and compute cumulative metrics using window functions. These insights support business reporting, trend analysis, and strategic planning.

---

Query Summary

 1. Sales Over Time
These queries show how sales metrics evolve across different time dimensions:

- **By Year**: Aggregates total sales, customer count, and quantity sold per year
- **By Month**: Same metrics aggregated monthly
- **By Year and Month**: Combined view to observe seasonal or cyclical patterns

 2. Cumulative and Window Function Analysis
These queries use window functions to compute running totals and moving averages:

- **Running Total Sales**: Cumulative sales across months
- **Partitioned Running Total**: Resets for each month, useful for intra-month comparisons
- **Moving Average Price**: Tracks average price trends over time using monthly partitions



 
