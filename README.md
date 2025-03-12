📊 Sales Analysis Insights

🔍 Project Overview

This project aims to analyze the company's sales data and provide valuable insights that can help improve revenue. An interactive dashboard is created using Power BI to assist in decision-making.

🛠 Tools Used

MySQL: For writing queries and extracting data.
Power BI: For creating dashboards and visualizations.
DAX: For generating KPIs and measures.

🎯 Objective

✅ Analyze sales data to uncover trends and insights.
✅ Provide actionable recommendations for revenue growth.
✅ Develop an interactive dashboard to visualize key metrics and facilitate decision-making.

🧹 Data Cleaning

🔹 Handling Missing Values:

- "Market" table had missing values, possibly due to one-time business transactions.
- Removed missing values from the "zone" column in the "market" table.

🔹 Sales Amount Issues:

- The "transactions" table had negative values in the 'sales_amount' column.
- Removed records where 'sales_amount' was 0 or <0.

🔹 SQL Queries Used:

- Utilized SQL functions like WHERE, LIKE, SELECT, FROM, SUM, COUNT, ORDER BY, GROUP BY to analyze the data.

🔹 Currency Normalization:

- Some transactions were recorded in USD.
- Converted USD transactions to INR and created a new column named normalized_currency.

📂 About the Data

📌 Transactions Table: ~150,283 records
📌 Unique Customers: 38
📌 Unique Products: 279
📌 Unique Markets: 17

🔄 Data Preprocessing

- Established Many-to-One relationships among different tables using STAR Schema
- Fact Table: Transactions
- Dimension Tables: Customer, Product, Date, Market
- Utilized Power Query Editor, DAX functions, and ETL processes to refine data.

📊 Dashboard & Key Metrics

📌 KPI Metrics

✅ Revenue
✅ Sales Quantity
✅ Profit Margin
✅ Yearly Comparisons

📌 Visualizations

🎯 Slicers: Filters by year and current year date.
🎯 Charts Used:

📊 Bar Charts
📈 Line Charts
🍩 Donut Charts

📋 Tables
🎯 Conditional Formatting: Highlights regions with negative profit.

📈 Features & Analysis

1️⃣ Key Insights

Revenue & Sales Quantity Analysis 📊
Stacked bar chart to analyze revenue and sales quantity by market & product_code.

Revenue Trends Over Years 📈
- Line chart to visualize revenue trends over the past years.

Revenue Contribution by Market 🍩
- Donut chart to show revenue distribution across markets.

2️⃣ Profit Analysis

Revenue Contribution %, Profit Contribution %, Profit % by Market 📊
- Stacked bar chart for visualization.

Yearly Revenue Trends 📈
- Line chart depicting revenue changes over the years.

Customer Contribution Analysis 📋
- Table showing highest revenue-contributing customers, their revenue contribution %, and profit margin %.

3️⃣ Performance Analysis

Yearly Revenue Comparison 📈
- Line and clustered column chart to compare revenue between the previous year and the current year.

Deep-Dive Revenue Analysis 📊
- Level 3 analysis for revenue contribution % by market, city, customer, and product.
- Stacked bar chart for effective comparison.

🏆 Technical & Soft Skills

🖥 Technical Skills

✔ SQL
✔ Power BI
✔ DAX
✔ ETL
✔ Data Cleaning
✔ Data Visualization
✔ Report Building

🗣 Soft Skills

✔ Presenting Insights
✔ Deriving Solutions

📌 Contribution

This repository contains all necessary files, including Power BI dashboards, and documentation for reproducing the analysis. Feel free to contribute, suggest improvements, or report issues!

🚀 Happy Analyzing! 🚀
