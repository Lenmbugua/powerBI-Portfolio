Global Superstore Sales Dashboard
📌 Project Overview

This project analyzes the Global Superstore dataset, focusing on sales, profit, customer behavior, product performance, and shipping efficiency. The data was cleaned (cleaned_sales_data.csv) and visualized using Power BI to uncover actionable business insights.

The dashboard is structured into four main pages:

Executive Summary

Product Analysis

Customer Analysis

Operational Insights

📂 Dataset

Source: Global Superstore dataset

File Used: cleaned_sales_data.csv

Data Fields Include:

Order details: Order ID, Order Date, Ship Date, Ship Mode, Order Priority

Customer details: Customer Name, Segment, Region, Country

Product details: Category, Sub-Category, Product Name

Sales metrics: Sales, Quantity, Discount, Profit

📊 Dashboard Pages & Visualizations
1. Executive Summary

KPIs: Total Sales, Total Profit, Profit Margin, Total Orders

Sales Trend: Year-over-year sales performance (2012–2014)

Regional Sales Distribution: Map view of sales by global region

2. Product Analysis

Sales by Category & Sub-Category (Furniture, Technology, Office Supplies)

Top Products by Revenue: Bar chart of the 15 highest-earning products

Profitability by Category: Technology leading in profit margins

Profit Trend Over Time: Seasonal fluctuations in profitability

3. Customer Analysis

Top Customers by Sales: Ranking of customers contributing most revenue

Customer Segment Performance: Pie chart of sales across Consumer, Corporate, Home Office

Customer Purchase Patterns:

Avg. Order Value by Segment (Column chart)

Number of Orders (Line overlay)

4. Operational Insights

Shipping Performance: Average delivery days by shipping mode (Standard, Second Class, Same Day, etc.)

Sales by Order Priority: Breakdown by Critical, High, Medium, Low

Delivery Days by Priority: Relationship between order priority and fulfillment speed

🔑 Key Insights
Executive Summary

Total Sales: 64.6K | Total Profit: 10.5K | Orders: 25

Sales peaked in 2013 with strong growth compared to 2012.

Western Europe and the US were the top-performing regions.

Product Analysis

Technology products dominate revenue (≈ 46.6K), especially Phones (43.7K).

Furniture is the second-largest contributor but with lower profit margins.

Office Supplies show minimal contribution, signaling potential underperformance.

Seasonal spikes in profit suggest high demand periods around March, October, and December.

Customer Analysis

A small group of top customers (e.g., Aaron Bergman, Mick Brown) account for a large share of revenue.

Consumer segment drives the majority of sales compared to Corporate and Home Office.

Average order value is highest in Corporate, but Consumer makes more frequent purchases.

Operational Insights

Standard Class is the most used shipping mode but has the longest delivery times.

Same-Day shipping ensures speed but accounts for a small portion of sales.

Orders marked as Critical priority have faster delivery but smaller sales volume.

🛠 Tools & Technologies

Data Cleaning: Python (pandas)

Visualization: Power BI

Data Format: CSV

🚀 How to Use

Open cleaned_sales_data.csv in Power BI Desktop.

Load the data model and apply transformations (if needed).

Navigate through the four dashboard pages to explore insights.