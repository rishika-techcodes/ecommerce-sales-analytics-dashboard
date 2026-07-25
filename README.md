# 📊 E-Commerce Sales Analytics Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-Power%20BI-blue)
![License](https://img.shields.io/badge/License-MIT-green)

An interactive Power BI dashboard that transforms raw e-commerce transaction data into actionable business insights — covering revenue trends, customer behavior, order performance, and top-selling products.

## Dashboard Preview

<img src="images/dashboard-preview.png" alt="Dashboard Preview" width="800">

## 📌 Project Overview

This project analyzes e-commerce sales data using **Microsoft Power BI** to transform raw data into meaningful business insights. An interactive dashboard was developed to monitor sales performance, revenue trends, customer activity, and product performance.

The project demonstrates **data cleaning, data transformation, DAX-based KPI calculation, data visualization, and exploratory analysis in Python** to support data-driven decision-making.

## 🗂️ Data Source

- Dataset: e-commerce transaction-level sales data (orders, customers, products, revenue)
- *(Add: where the data came from, date range covered, and row/record count once finalized)*

## 🧹 Methodology

1. **Data Cleaning & Transformation** — Power Query was used to clean and reshape raw transaction data (handling nulls, standardizing date/customer fields, removing duplicates).
2. **KPI Modeling** — DAX measures were built to calculate revenue, order counts, customer counts, and time-based trends.
3. **Exploratory Analysis** — A Python/Jupyter notebook (`notebooks/ecommerce-analysis.ipynb`) was used to explore the dataset ahead of dashboard design.
4. **Dashboard Design** — Visuals were built in Power BI to surface trends, top performers, and customer segments interactively.

## 🚀 Features

- 💰 Total Revenue Analysis
- 🛒 Total Orders Tracking
- 👥 Customer Analysis
- 📈 Monthly Revenue Trend Analysis
- 📦 Top-Selling Product Analysis

## 🛠️ Tools & Technologies

- Power BI
- Power Query
- DAX
- Python
- Jupyter Notebook

## 📋 Prerequisites

To explore and run this project, you will need:

- Microsoft Power BI Desktop
- Python 3.x
- Jupyter Notebook
- Required Python libraries used in the analysis notebook (pandas, matplotlib, etc.)

## 📁 Project Structure

```text
 ecommerce-sales-analytics-dashboard/
│
├── dashboard/
│   └── ecommerce-dashboard.pbix          # Interactive Power BI dashboard
│
├── notebooks/
│   └── ecommerce-analysis.ipynb          # Python-based exploratory analysis
│
├── images/
│   ├── dashboard-preview.png             # Main dashboard preview
│   ├── monthly-revenue-trend.png         # Monthly revenue trend visual
│   ├── top-products.png                  # Top-selling products visual
│   ├── top-customers.png                 # Top customers by spending visual
│   └── customer-segmentation.png         # Customer segmentation visual
│
└── README.md
```
📊 Key Business Insights
💰 Total Revenue: 8M
🛒 Total Orders: 24K
👥 Total Customers: 4K
📦 Top-Selling Product: White Hanging Heart T-Light Holder
📈 Revenue Trend: Higher sales activity was observed toward the end of the year, with several significant revenue spikes.
📈 Dashboard Insights

The interactive Power BI dashboard provides a comprehensive view of e-commerce business performance, enabling users to:

📊 Analyze revenue trends
👥 Monitor customer activity
🛒 Track order volume
📦 Evaluate product performance
📈 Measure overall business performance
▶️ How to Use the Project
Download dashboard/ecommerce-dashboard.pbix from this repository.
Open the file using Microsoft Power BI Desktop.
Explore the dashboard using the interactive filters, slicers, and charts.
Open notebooks/ecommerce-analysis.ipynb in Jupyter Notebook to review the Python-based data analysis.
🔮 Future Enhancements
📌 Add interactive customer segmentation analysis.
🌍 Include geographical sales analysis.
💰 Add profit and profit-margin KPIs.
📅 Develop month-over-month and year-over-year sales comparisons.
🤖 Perform advanced customer behaviour analysis.
☁️ Publish the dashboard to Power BI Service for online access.
📸 Project Visualizations
📊 Dashboard Preview
<p align="center"> <img src="images/dashboard-preview.png" alt="Dashboard Preview" width="900"> </p>
📈 Monthly Revenue Trend
<p align="center"> <img src="images/monthly-revenue-trend.png" alt="Monthly Revenue Trend" width="700"> </p>
📦 Top 10 Selling Products
<p align="center"> <img src="images/top-products.png" alt="Top 10 Selling Products" width="700"> </p>
👥 Top 10 Customers by Spending
<p align="center"> <img src="images/top-customers.png" alt="Top 10 Customers by Spending" width="700"> </p>
🧩 Customer Segmentation
<p align="center"> <img src="images/customer-segmentation.png" alt="Customer Segmentation" width="700"> </p>
🧠 Skills Demonstrated
✅ Power BI Dashboard Development
✅ Data Cleaning & Transformation (Power Query)
✅ DAX Measure Creation & KPI Design
✅ Exploratory Data Analysis using Python (Pandas)
✅ Business Intelligence & Data Visualization
✅ Customer Segmentation Analysis
✅ Sales Trend & Product Performance Analysis
✅ Business Insight Communication
📄 License

This project is licensed under the MIT License.

See the LICENSE file for more information.
