# Vendor Performance Analysis

This repository contains an end-to-end analysis of vendor and product performance to optimize profitability and efficiency in inventory and sales management. The project aims to provide insights for vendor selection, product pricing, and overall supply chain optimization.

## Project Structure

* `Exploratory Data Analysis.ipynb`: This Jupyter notebook is used for initial data exploration. It focuses on understanding the dataset's structure within the database to facilitate vendor selection for profitability and product pricing optimization.
* `get_vendor_summary.py`: This Python script is responsible for creating a comprehensive vendor summary. It merges various tables, cleans the data, and engineers new features such as `GrossProfit`, `ProfitMargin`, `StockTurnover`, and `SalesToPurchaseRatio` for detailed analysis.
* `ingestion_db.py`: This script handles the ingestion of raw CSV data into an SQLite database named `inventory.db`. It automates the process of loading CSV files into database tables, with each filename serving as the table name.
* `Vendor Performance Analysis.ipynb`: This Jupyter notebook performs the core vendor performance analysis. It loads the processed `vendor_sales_summary` data and uses libraries like pandas, numpy, matplotlib, seaborn, and scipy.stats to conduct in-depth analysis.
* `Vendor Performance Report.pdf`: This PDF document presents a comprehensive summary of the findings and recommendations from the vendor performance analysis. It addresses key business problems such as identifying underperforming brands, determining top vendors, analyzing bulk purchasing impact, assessing inventory turnover, and investigating profitability variance between vendor groups.
* `vendor_sales_summary.csv`: This CSV file contains the summarized sales and purchase data for vendors, including calculated metrics like Gross Profit, Profit Margin, Stock Turnover, and Sales to Purchase Ratio. 

## Business Problem & Objectives

Effective inventory and sales management are crucial for optimizing profitability in the retail and wholesale industry. This project addresses the need to avoid losses due to inefficient pricing, poor inventory turnover, or vendor dependency. 

The key objectives of this analysis are to:
* Identify underperforming brands that require promotional or pricing adjustments.
* Determine top vendors contributing to sales and gross profit.
* Analyze the impact of bulk purchasing on unit costs. 
* Assess inventory turnover to reduce holding costs and improve efficiency.
* Investigate the profitability variance between high-performing and low-performing vendors.

## Key Findings & Recommendations

The analysis includes statistical validation of profit margin differences between top and low-performing vendors, confirming distinct profitability models. 

Final recommendations include:
* Re-evaluating pricing for low-sales, high-margin brands to boost sales volume.
* Diversifying vendor partnerships to reduce dependency and mitigate supply chain risks.
* Leveraging bulk purchasing advantages for competitive pricing and optimized inventory. 
* Optimizing slow-moving inventory through adjusted purchase quantities, clearance sales, or revised storage. 
* Enhancing marketing and distribution strategies for low-performing vendors to drive sales without compromising profit margins.

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
