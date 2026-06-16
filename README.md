# 📊 E-Commerce Business Analytics Platform

## 🚀 Project Overview

An end-to-end E-Commerce Analytics solution built using **Microsoft Fabric, SQL, Python, Power BI, Streamlit, and Machine Learning Forecasting** to transform raw transaction data into actionable business insights.

This project demonstrates the complete analytics lifecycle including data engineering, customer segmentation, business intelligence reporting, forecasting, and interactive analytics deployment.

---

## 🎯 Business Objectives

This project aims to answer key business questions:

* How is revenue performing over time?
* Which states generate the highest revenue?
* Which payment methods contribute most to sales?
* Who are the most valuable customers?
* Which customer segments are at risk?
* What future revenue can be expected?
* How can customer retention be improved?

---

## 🏗️ Solution Architecture

```text
Raw Data
   │
   ▼
Microsoft Fabric Lakehouse
   │
   ▼
Data Cleaning & Transformation
(SQL + Python)
   │
   ▼
Gold Analytics Tables
   │
   ├── Customer Analytics
   ├── Revenue Analytics
   ├── RFM Segmentation
   └── Sales Forecasting
   │
   ▼
Power BI Dashboard
   │
   ▼
Streamlit Analytics Application
```

---

## 🛠️ Technology Stack

| Category        | Technologies               |
| --------------- | -------------------------- |
| Data Storage    | Microsoft Fabric Lakehouse |
| Data Processing | SQL, Python                |
| Data Analysis   | Pandas, NumPy              |
| Visualization   | Power BI                   |
| Forecasting     | Prophet                    |
| Web Application | Streamlit                  |
| Version Control | GitHub                     |
| Deployment      | Streamlit Cloud            |

---

## 📂 Dataset Overview

### Fact Table

**fact_orders_clean**

Contains:

* Orders
* Revenue
* Payment Information
* Delivery Metrics
* Customer Transactions

### Dimension Tables

**dim_customers_clean**

* Customer Information
* Customer State
* Customer Location

**dim_products_clean**

* Product Information
* Product Categories
* Product Dimensions

### Analytics Tables

**customer_rfm_segments**

* Recency
* Frequency
* Monetary Value
* Customer Segments

**sales_forecast**

* Revenue Forecast
* Confidence Intervals
* Future Sales Predictions

---

## 📈 RFM Customer Segmentation

Customer segmentation was performed using the RFM framework.

### Recency

Days since the customer's last purchase.

### Frequency

Number of purchases made by the customer.

### Monetary

Total amount spent by the customer.

### Customer Segments

* Champions
* Loyal Customers
* Potential Loyalists
* At Risk
* Lost Customers

---

## 📊 Power BI Dashboard

### Executive Dashboard

KPIs:

* Total Revenue
* Total Orders
* Total Customers
* Average Order Value

Visualizations:

* Revenue Trend Analysis
* Revenue by State
* Payment Type Analysis
* Customer Distribution

### Customer Analytics Dashboard

Visualizations:

* RFM Segment Distribution
* Revenue by Segment
* Customer Spending Analysis
* Top Customers

### Forecasting Dashboard

Visualizations:

* Revenue Forecast
* Confidence Intervals
* Future Growth Trends

---

## 🤖 Machine Learning Forecasting

Future revenue was predicted using the Prophet Forecasting Model.

Forecast Outputs:

* Expected Revenue (yhat)
* Upper Confidence Bound
* Lower Confidence Bound

Business Benefits:

* Revenue Planning
* Inventory Optimization
* Budget Forecasting
* Strategic Decision Making

---

## 🌐 Streamlit Analytics Application

### Executive Dashboard

* Revenue Monitoring
* Sales KPIs
* Payment Analytics
* State Performance Analysis

### Customer Intelligence

* Customer Segment Filtering
* Customer Search
* RFM Insights
* Top Customer Analysis

### Forecasting Center

* Revenue Forecasting
* Scenario Analysis
* Forecast Downloads

---

## 📸 Project Screenshots

### Power BI Dashboard

Insert screenshot here:

```md
![Power BI Dashboard](screenshots/powerbi_dashboard.png)
```

### Microsoft Fabric Pipeline / Architecture

Insert screenshot here:

```md
![Fabric Pipeline](screenshots/fabric_pipeline.png)
```

### Streamlit Application

Insert screenshot here:

```md
![Streamlit Dashboard](screenshots/streamlit_dashboard.png)
```

---

## 📊 Key Insights

* Analyzed 99K+ customer orders.
* Identified high-value customer segments through RFM analysis.
* Built interactive business dashboards for decision-makers.
* Forecasted future revenue using machine learning.
* Delivered a complete end-to-end analytics solution using Microsoft Fabric and Power BI.

---

## 📁 Repository Structure

```text
├── app.py
├── requirements.txt
├── README.md
│
├── git_data
│   ├── fact_orders_clean.csv.gz
│   ├── dim_customers_clean.csv
│   ├── dim_products_clean.csv
│   ├── customer_rfm_segments.csv
│   └── sales_forecast.csv
│
├── screenshots
│   ├── powerbi_dashboard.png
│   ├── streamlit_dashboard.png
│   └── fabric_pipeline.png
│
└── notebooks
    └── analytics_notebook.ipynb
```

---

## 👨‍💻 Author

**Naaz**

Aspiring Data Analyst | Data Scientist | AI & Machine Learning Enthusiast

GitHub: https://github.com/naaz-719

---

⭐ If you found this project useful, consider giving it a star.
