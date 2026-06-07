## 📊 Sales Analytics Dashboard using MySQL & Power BI

### Project Overview

This project focuses on analyzing sales data using **MySQL** and **Power BI** to provide actionable business insights across products, customers, markets, and time dimensions. The dashboard enables stakeholders to monitor revenue trends, identify top-performing products and markets, and understand customer purchasing behavior.

---

## 🎯 Business Problem

The organization generated large volumes of sales transactions but lacked a centralized reporting system to monitor performance across different business dimensions. Decision-makers needed a solution to:

* Track sales performance in real time
* Identify high-revenue products and markets
* Analyze customer segments
* Monitor sales trends over time
* Support data-driven decision making

---

## 🛠️ Tech Stack

* MySQL
* Power BI
* SQL
* ODBC Connector
* Power Query

---

## 📂 Data Model

### Fact Table

**Transactions**

* product_code
* customer_code
* market_code
* order_date
* sales_qty
* sales_amount
* currency

### Dimension Tables

**Products**

* product_code
* product_type

**Customers**

* customer_code
* customer_name
* customer_type

**Markets**

* market_code
* market_name
* zone

**Date**

* date
* cy_date
* year
* month_name
* date_yy_mmm

---

## 🔗 Data Modeling

Implemented a **Star Schema** with:

* Products → Transactions (1:*)
* Customers → Transactions (1:*)
* Markets → Transactions (1:*)
* Date → Transactions (1:*)

This structure enables efficient filtering, aggregation, and reporting.

---

## 📊 Dashboard Features

### KPI Cards

* Total Revenue
* Total Sales Quantity
* Total Customers
* Total Products

### Visualizations

* Monthly Sales Trend Analysis
* Product Performance Analysis
* Market-wise Revenue Distribution
* Customer Type Analysis
* Interactive Filters & Slicers

---

## 🧹 Data Preparation

* Validated relationships between fact and dimension tables
* Standardized key fields for accurate joins
* Handled data quality issues and missing mappings
* Created a clean semantic model for reporting

---

## 📈 Key Insights

* Identified top-performing products contributing maximum revenue
* Analyzed revenue contribution across different markets and zones
* Evaluated customer segment performance
* Monitored monthly and yearly sales trends
* Enabled business users to make data-driven decisions

---

## 🚀 Business Impact

* Reduced manual reporting effort
* Improved visibility into sales performance
* Enabled faster business decision-making
* Created a scalable reporting solution with automated refresh capability

---

## 📸 Dashboard Preview

<img width="1920" height="1080" alt="Screenshot (185)" src="https://github.com/user-attachments/assets/cc50811e-c25f-41c5-94a7-de22d27e649f" />

---

## 📁 Project Structure

```text
Sales-Analytics-Dashboard/
│
├── Dataset/
├── SQL Scripts/
├── PowerBI Dashboard.pbix
└── README.md
```

---

## 📌 Future Enhancements

* Year-over-Year (YoY) Analysis
* Month-over-Month (MoM) Growth
* Profitability Dashboard
* Forecasting & Predictive Analytics
* Drill-through Reports

---

# Dataset Link

[Codebasics Sales Insights Project Dataset](https://codebasics.io/resources/sales-insights-data-analysis-project?utm_source=chatgpt.com)

