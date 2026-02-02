Business Performance Dashboard (Power BI)
Overview

This project analyzes retail sales performance using an interactive Power BI dashboard. The goal is to provide a clear, executive-level view of revenue, profit, and order trends over time, along with category and regional performance insights to support data-driven decision-making.

Business Questions

The dashboard was designed to answer the following questions:

How are sales and profit performing overall?

How do sales trend month over month?

Which product categories drive the most revenue?

Which regions are the most profitable?

How do these metrics change when filtered by year, region, or category?

Dataset

Source: Sample Superstore (Retail Sales Dataset)

Granularity: Order-level transaction data

Key Fields: Order Date, Sales, Profit, Category, Sub-Category, Region, Quantity, Discount

Tools Used

Power BI Desktop

Power Query (data cleaning and transformation)

DAX (measure creation)

Key Metrics

The following KPIs were created using DAX measures:

Total Sales

Total Profit

Order Count

Average Order Value (optional)

These metrics dynamically update based on applied filters.

Dashboard Features

KPI Cards: High-level snapshot of overall performance

Monthly Sales Trend: Line chart showing sales by month

Category Breakdown: Sales performance by product category

Regional Breakdown: Profit performance by region

Interactive Filters: Year, Region, and Category slicers for drill-down analysis

(Insert dashboard screenshot below)

Key Insights

Overall sales are strong, but profit does not increase at the same rate, suggesting potential margin pressure.

Sales demonstrate noticeable seasonal variation, with higher performance toward the end of the year.

Technology is the top revenue-generating category, making it a primary business driver.

The West region delivers the highest profit, while other regions show opportunities for margin improvement.

Files Included
business-performance-dashboard/
├── README.md
├── Superstore.pbix
├── dashboard_screenshot.png

Summary

This project demonstrates the full data analysis workflow, including data preparation, metric development, dashboard design, and insight generation. It showcases the ability to translate raw data into clear, actionable business insights using Power BI.
