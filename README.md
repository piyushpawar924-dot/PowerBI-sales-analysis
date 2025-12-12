🍕 Pizza Sales Analysis – Power BI Dashboard
📌 Project Overview

This Power BI project analyzes pizza sales data to identify key business insights such as top-selling products, revenue trends, customer preferences, and overall performance metrics.
The goal of the dashboard is to help stakeholders make data-driven decisions about marketing, inventory, pricing, and operations.

📁 Files in This Repository
File	Description
PIZZA_SALES_DSHB.pbix	Main Power BI dashboard file
pizza_sales.csv	Raw dataset used for analysis
/images	Contains dashboard screenshots for quick preview
README.md	Documentation (this file)

🎯 Business Objectives

This dashboard answers important sales questions, including:
Which pizza categories and pizza types generate the most revenue?
Which days and months have the highest sales?
What are the top 10 best-selling pizzas?
What operational trends can help optimize production and marketing?

📊 Dashboard Features

1️⃣ KPI Cards

Total Revenue
Total Orders
Average Order Value
Total Quantity Sold

2️⃣ Sales Analysis

Sales by Pizza Category (Classic, Supreme, Veggie, Chicken, etc.)
Sales by Pizza Size (S, M, L, XL)
Hourly/Monthly sales trend visualizations

3️⃣ Top Performers

Top 5 Pizzas by Revenue
Top 5 Pizzas by Quantity Sold

4️⃣ Time-Series Insights

Revenue trend across months
Daily order trends
Identifying peak sales days

5️⃣ Interactive Filters

Category slicers
Pizza size slicers
Date filters

🧠 Key Insights

Here are the most important business insights found in the dashboard (general placeholders—you can update based on your actual numbers):

Classic pizzas generate the highest total revenue.
Large-size pizzas are the most popular, contributing a major portion of sales.
Fridays and weekends show the highest order volume, indicating peak demand times.
The top-selling pizza contributes significantly to monthly revenue trends.
Sales show strong seasonal/weekly patterns, useful for promotional planning.

🛠️ Tech Stack

Power BI Desktop
Data cleaning using Power Query
DAX Measures for KPIs (example):

Total Revenue = SUM(pizza_sales[total_price])
Total Orders = DISTINCTCOUNT(pizza_sales[order_id])

📂 How to Open the Project

Download or clone this repository.
Open Power BI Desktop.
Double-click PIZZA_SALES_DSHB.pbix.
Explore visuals, filters, and insights.

💡 Author

Piyush Pawar
Data Analyst Enthusiast | Power BI | SQL | Python
