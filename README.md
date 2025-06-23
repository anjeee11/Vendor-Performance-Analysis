# Vendor Performance Analysis

This repository contains an end-to-end analysis of vendor and product performance to optimize profitability and efficiency in inventory and sales management. The project aims to provide insights for vendor selection, product pricing, and overall supply chain optimization.

## Project Structure

* `Exploratory Data Analysis.ipynb`: This Jupyter notebook is used for initial data exploration. [cite_start]It focuses on understanding the dataset's structure within the database to facilitate vendor selection for profitability and product pricing optimization. [cite: 1]
* `get_vendor_summary.py`: This Python script is responsible for creating a comprehensive vendor summary. It merges various tables, cleans the data, and engineers new features such as `GrossProfit`, `ProfitMargin`, `StockTurnover`, and `SalesToPurchaseRatio` for detailed analysis.
* `ingestion_db.py`: This script handles the ingestion of raw CSV data into an SQLite database named `inventory.db`. It automates the process of loading CSV files into database tables, with each filename serving as the table name.
* `Vendor Performance Analysis.ipynb`: This Jupyter notebook performs the core vendor performance analysis. [cite_start]It loads the processed `vendor_sales_summary` data and uses libraries like pandas, numpy, matplotlib, seaborn, and scipy.stats to conduct in-depth analysis. [cite: 4]
* `Vendor Performance Report.pdf`: This PDF document presents a comprehensive summary of the findings and recommendations from the vendor performance analysis. [cite_start]It addresses key business problems such as identifying underperforming brands, determining top vendors, analyzing bulk purchasing impact, assessing inventory turnover, and investigating profitability variance between vendor groups. [cite: 7]
* [cite_start]`vendor_sales_summary.csv`: This CSV file contains the summarized sales and purchase data for vendors, including calculated metrics like Gross Profit, Profit Margin, Stock Turnover, and Sales to Purchase Ratio. [cite: 5]

## Business Problem & Objectives

Effective inventory and sales management are crucial for optimizing profitability in the retail and wholesale industry. [cite_start]This project addresses the need to avoid losses due to inefficient pricing, poor inventory turnover, or vendor dependency. [cite: 7]

The key objectives of this analysis are to:
* [cite_start]Identify underperforming brands that require promotional or pricing adjustments. [cite: 7]
* [cite_start]Determine top vendors contributing to sales and gross profit. [cite: 7]
* [cite_start]Analyze the impact of bulk purchasing on unit costs. [cite: 7]
* [cite_start]Assess inventory turnover to reduce holding costs and improve efficiency. [cite: 7]
* [cite_start]Investigate the profitability variance between high-performing and low-performing vendors. [cite: 7]

## Key Findings & Recommendations

[cite_start]The analysis includes statistical validation of profit margin differences between top and low-performing vendors, confirming distinct profitability models. [cite: 7]

Final recommendations include:
* [cite_start]Re-evaluating pricing for low-sales, high-margin brands to boost sales volume. [cite: 7]
* [cite_start]Diversifying vendor partnerships to reduce dependency and mitigate supply chain risks. [cite: 7]
* [cite_start]Leveraging bulk purchasing advantages for competitive pricing and optimized inventory. [cite: 7]
* [cite_start]Optimizing slow-moving inventory through adjusted purchase quantities, clearance sales, or revised storage. [cite: 7]
* [cite_start]Enhancing marketing and distribution strategies for low-performing vendors to drive sales without compromising profit margins. [cite: 7]

## Technologies Used

* Python
* Pandas
* Numpy
* Matplotlib
* Seaborn
* SQLite3
* Scipy.stats
* SQLAlchemy
* Jupyter Notebook
