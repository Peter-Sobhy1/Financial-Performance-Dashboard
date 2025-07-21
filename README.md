# Financials-and-Sales-Performance-Dashboard

**Link** for the dashboard: https://app.powerbi.com/view?r=eyJrIjoiMTczZmM2ZDgtNjJkMy00YjgxLWIyMWEtOTg4OGRjYTUzMzFjIiwidCI6IjJiYjZlNWJjLWMxMDktNDdmYi05NDMzLWMxYzZmNGZhMzNmZiIsImMiOjl9

![Sales Dashboard](https://github.com/Peter-Sobhy1/Sales-Performance-Dashboard/blob/main/Assets/Dashboard.png?raw=true)

## 🗂️ Project Overview
This Power BI report provides a comprehensive **financial and sales performance overview** using data sourced from a centralized **Data Warehouse (DWH)**. The dashboard includes separate pages for Revenue, Cost of Goods Sold (COGS), Units Sold, Gross Profit, and an executive summary Dashboard.

It helps business users track key financial metrics, analyze product and customer performance, and make data-driven decisions.

---

## 🔌 Data Source & Refresh
- **Source**: Enterprise Data Warehouse (DWH)
- **Connection Mode**: Import Mode (for optimized performance and better speed)
- **Scheduled Refresh**: Daily via Power BI Service

---

## 📁 Report Pages & Dashboard

1. **Revenue** – Revenue breakdown by time, customer, and product
![Revenue](https://github.com/Peter-Sobhy1/Financials-and-Sales-Performance-Dashboard/blob/main/Assets/Revenue.png?raw=true)

2. **COGS** – Cost of goods sold and cost trend analysis
![COGs](https://github.com/Peter-Sobhy1/Financials-and-Sales-Performance-Dashboard/blob/main/Assets/COGs.png?raw=true)

3. **Units Sold** – Units sold by product and time
![Units Sold](https://github.com/Peter-Sobhy1/Financials-and-Sales-Performance-Dashboard/blob/main/Assets/Units%20Sold.png?raw=true)

4. **Gross Profit** – Profitability analysis and performance vs goals
![Gross Profit](https://github.com/Peter-Sobhy1/Financials-and-Sales-Performance-Dashboard/blob/main/Assets/Gross%20Profit.png?raw=true)

5. **Dashboard** – High-level KPIs and summary visuals
![Dashboard](https://github.com/Peter-Sobhy1/Financials-and-Sales-Performance-Dashboard/blob/main/Assets/Dashboard.png?raw=true)
---

## 🧱 Data Model Overview

- **Fact Table**:  
  - `gold_fact_sales`

- **Dimension Tables**:  
  - `gold_dim_products`  
  - `gold_dim_customers`  
  - `Calendar` (Date Dimension)

## 📷 Screenshot – Data Model
![Data Model!](https://github.com/Peter-Sobhy1/Financial-Performance-Dashboard/blob/main/Assets/Data%20Model.png?raw=true)

---

## 📌 Key Insights

This report uncovered several important insights based on analysis of product, sales, and customer data:

 🌍 **Top 5 Countries by Revenue**

 🛒 **Top 5 Products by Units Sold**

 📦 **Top 5 Product Categories by Revenue**

 👤 **Top 5 Customers by Purchase Value**

 📈 **Sales Trend Over Time**

 🔢 **Profit Margin, Revenue, COGs, Units Sold, Gross Profit**



> 💡 These insights enable targeted strategies for top-performing products, markets, and customer segments, while helping monitor performance trends over time.

---

## 🎯 Key Features
- 📌 Page navigation using **custom buttons and bookmarks**
- 🎨 Color-coded pages for easy visual distinction
- 🧮 Custom DAX measures to compare actuals vs goals
- 📅 Slicers and filters for time, product, and customer dimensions
- 💼 Executive-friendly dashboard view for quick insights

---

## 🧠 Purpose
This report was developed to simulate real-world BI reporting scenarios and showcase Power BI's capability to:
- Connect to enterprise-grade data (DWH)
- Use import mode for performance
- Model data across star schema
- Deliver impactful, interactive dashboards for business decision-making

---

## 📎 Tools Used
- Power BI Service
- Power BI Desktop
- Power Query
- SQL (Data Warehouse Queries)
- DAX (Custom Measures & KPIs)


Let's stay in touch!

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/peter-sobhy/)
