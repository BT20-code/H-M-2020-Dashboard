# H&M-2020-Dashboard
🛍 H&M Sales Performance Dashboard | Power BI

An interactive Power BI dashboard built using the H&M Personalized Fashion Recommendations dataset (31 million+ retail transactions) to analyze sales performance across product categories, sales channels, and SKUs. The dashboard transforms large-scale retail data into actionable insights for merchandising, category management, and business decision-making through dynamic KPIs and interactive visualizations.

📊 Dashboard Preview

[Show Image](https://github.com/BT20-code/H-M-2020-Dashboard/blob/main/H%26M%202020%20Final%20Dashboard.jpg)

📌 Project Overview

Fashion retailers generate millions of transactions every month, making it difficult to identify high-performing products, monitor category performance, and understand customer purchasing behavior through raw transactional data.

This project demonstrates an end-to-end Business Intelligence workflow by preprocessing retail data in Python, building a Star Schema data model, creating DAX measures, and developing an interactive Power BI dashboard that supports data-driven merchandising decisions.

❓ Business Questions Answered
Which product categories generate the highest revenue?
Which SKUs contribute the most to overall sales?
How does Online performance compare with Physical Stores?
Which categories perform consistently throughout the year?
How efficiently is the product assortment generating revenue?
🛠 Tech Stack
Tool	Purpose
📊 Power BI Desktop	Dashboard development & visualization
🔄 Power Query	Data cleaning, transformation & ETL
🧠 DAX	Dynamic KPIs and business calculations
🐍 Python (Pandas)	Data preprocessing, merging datasets & model preparation
🗂 Star Schema	Optimized dimensional data modeling
📂 Data Source

Dataset: H&M Personalized Fashion Recommendations Source: Kaggle

The project uses H&M's public retail dataset containing 31+ million customer transactions along with product metadata. Only the Transactions and Articles datasets were used for analysis — Python was used to merge and preprocess the data into a centralized FactSales table supported by multiple dimension tables following a Star Schema design.

🏗 Data Model

The dashboard follows a Star Schema to improve report performance and simplify filtering.

Fact Table

FactSales

Dimension Tables

DimProduct
DimDate
DimChannel
DimIndexGroup
📈 Dashboard Features
Executive KPI Cards

Monitor key retail metrics including:

💰 Total Revenue
🛒 Total Transactions
👕 Unique SKUs
📈 Average Revenue per Transaction (ASP)
🏷 Revenue per SKU

These KPIs dynamically update based on the selected Index Group.

Revenue by Category

A horizontal bar chart comparing revenue generated across H&M's major merchandise Index Groups (Ladieswear, Divided, Menswear, Sport, Baby/Children), highlighting the strongest revenue-generating categories.

Online vs In-Store Channel Split

A 100% stacked bar chart comparing revenue contribution from Online and Physical Stores for each Index Group — useful for identifying which categories are online-driven vs store-reliant.

Monthly Sales Trend

A line chart tracking monthly revenue performance from January to September 2020, surfacing seasonal demand patterns and sales peaks.

Top 20 Revenue Generating SKUs

A ranked horizontal bar chart displaying the highest revenue-generating products, supporting replenishment and inventory decisions.

Interactive Index Group Filter

A slicer that dynamically updates every visual — KPI cards, category revenue, channel split, trend, and top SKUs — for focused category-level analysis.

📊 Key DAX Measures
Total Revenue
Total Transactions
Unique SKUs
Average Revenue per Transaction (ASP)
Revenue per SKU
💡 Key Business Insights
📈 Category Performance — Quickly identifies which merchandise categories contribute the highest revenue, enabling better assortment planning.
🛍 Product Performance — Highlights the highest revenue-generating SKUs, helping buyers prioritize replenishment and identify hero products.
🌐 Channel Strategy — Compares Online and In-Store sales distribution across merchandise groups, supporting omnichannel decision-making.
📅 Sales Trend Monitoring — Tracks revenue movement across months to surface seasonal demand patterns.
📊 Executive Reporting — Consolidates multiple retail performance metrics into a single interactive dashboard, reducing manual reporting effort.
⚡ Challenges & Solutions
Challenge	Solution
Large retail dataset (31M+ transactions)	Preprocessed and optimized data using Python (Pandas)
Complex relationships between entities	Implemented a Star Schema data model
Dynamic reporting requirements	Built reusable DAX measures and interactive filters
Dashboard performance at scale	Reduced model complexity through ETL and optimized data modeling
📁 Repository Structure
📦 H&M-Sales-Dashboard
├── Dashboard.pbix
├── Data/
│   ├── Processed CSV Files
│   └── Data Dictionary
├── Images/
│   └── Dashboard_Preview.png
├── Notebook/
│   └── Data_Preprocessing.ipynb
└── README.md

File Formats

.pbix – Power BI project
.csv – Processed datasets
.ipynb – Python preprocessing notebook
🎯 Skills Demonstrated

Power BI Dashboard Development · Data Cleaning & Transformation · Power Query (ETL) · Python (Pandas) · DAX Measures & Calculations · Star Schema Data Modeling · Fact & Dimension Table Design · Interactive Dashboard Design · KPI Development · Retail Sales Analytics · Merchandising & Category Analysis · Business Intelligence · Data Visualization

🚀 Key Takeaways
Built an end-to-end retail analytics solution using Power BI and Python.
Processed and modeled 31+ million retail transactions into an optimized Star Schema.
Developed dynamic KPIs and interactive dashboards using DAX and Power Query.
Delivered actionable insights to support merchandising, category management, and retail business decisions.
