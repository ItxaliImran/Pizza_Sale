Pizza Sales Data Analysis using SQL
Project Overview
This project explores and visualizes pizza sales data using SQL and Power BI to uncover actionable business insights. Key objectives include analyzing revenue, sales trends, customer behavior, and identifying top-performing products to drive strategic decisions.

Project Files
Pizza Sales Data Analysis using SQL.pptx — Presentation summarizing the methodology and key findings.
analysis_queries.sql — SQL scripts for data transformations and insights.

Dataset Structure
The dataset includes detailed transaction records, likely with tables such as:
orders: Contains order metadata like ID, date, and time.
order_details: Includes order-specific pizza items and quantities.
pizzas: Pizza details including type, size, and price.
pizza_types: Additional metadata like category or name.

Key fields include:
order_id, pizza_id, quantity, price, order_date, order_time
Derived fields: total revenue, average order value, sales by category/size


Analysis Steps
Data Ingestion & Cleaning
Loaded data into SQL from CSV/source files.
Ensured consistency and clarity in field types and values.
Descriptive Statistics & KPIs
Total revenue, total pizzas sold, number of orders
Average order value, average pizzas per order
Trend Analysis
Daily and monthly sales trends
Peak hours and days (e.g., Friday evenings, weekend spikes)

Product Insights
Top and bottom 5 pizza types by revenue, orders, and quantity
Category and size breakdowns to reveal best performers


Key Findings
Peak periods: Friday and Saturday evenings are busiest.
Best-selling: Large-sized and Classic category pizzas drive most revenue.
Top performer: Classic Deluxe shines in sales and popularity.
Underperformers: Certain niche pizzas underdeliver—candidates for menu reevaluation.

