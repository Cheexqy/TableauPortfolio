# Sales & Customer Dashboard | Tableau

## 📌 Project Overview
This project presents a pair of interactive Tableau dashboards designed to analyse **sales performance** and **customer behaviour** across multiple years (2020–2023).

The dashboards allow business stakeholders to dynamically explore historical trends, monitor key KPIs over time, and conduct year-over-year (YoY) comparisons. The solution supports both high-level performance monitoring and deeper analysis across products and customer segments.

The project includes:
- **Sales Dashboard** – focused on revenue, profit, quantity, and product performance
- **Customer Dashboard** – focused on customer behaviour, order distribution, and high-value customers

---

## 🎯 Business Requirements

### Sales Dashboard – Purpose
The Sales Dashboard provides an overview of sales metrics and trends across multiple years (2020–2023) to:
- Analyse year-over-year sales performance
- Identify seasonal patterns and long-term trends
- Compare product subcategory performance and profitability over time

### Key Sales Requirements
- **KPI Overview**
  - Total Sales
  - Total Profit
  - Total Quantity
  - YoY comparison based on the selected year
- **Sales Trends**
  - Monthly trends for each KPI for the selected year
  - Clear identification of highest and lowest performing months
- **Product Subcategory Comparison**
  - Comparison of sales performance across product subcategories
  - Profit vs. loss analysis by subcategory
- **Weekly Trends**
  - Weekly sales and profit trends for the selected year
  - Average weekly benchmarks
  - Highlight weeks above and below the average to identify performance fluctuations

---

### Customer Dashboard – Purpose
The Customer Dashboard provides insights into customer data, trends, and behaviours across multiple years (2020–2023), supporting:
- Customer segmentation analysis over time
- Identification of high-value customers
- Understanding changes in order frequency and customer engagement

### Key Customer Requirements
- **KPI Overview**
  - Total Customers
  - Total Sales per Customer
  - Total Orders
  - YoY comparison based on the selected year
- **Customer Trends**
  - Monthly trends for customer-related KPIs
  - Identification of highest and lowest performing months
- **Customer Distribution**
  - Distribution of customers by number of orders
  - Insights into customer loyalty and repeat purchasing behaviour
- **Top Customers Analysis**
  - Top 10 customers ranked by profit
  - Display of rank, total orders, sales, profit, and last order date

---

## 🛠 Tools & Skills
- Tableau (Dashboard Design & Visual Analytics)
- KPI Design & Performance Measurement
- Data Modelling (Orders, Customers, Products, Locations)
- Time Series Analysis (Monthly & Weekly Trends)
- Business Insight Communication

---

## 📊 Dashboard Preview

### Sales Dashboard
![Sales Dashboard](images/Sales Dashboard.png)

### Customer Dashboard
![Customer Dashboard](images/Customer Dashboard.png)

---

## 🔗 Tableau Public (Interactive Dashboard)
👉 View the interactive dashboards on Tableau Public:  
https://public.tableau.com/views/SalesCustomer_Dashboard_17695774621680/CustomerDashborad?:language=zh-CN&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

---


## 🔄 Interactivity & Design Features
- Dynamic year selection enabling analysis from 2020 to 2023
- Interactive charts supporting cross-filtering across dashboards
- Navigation buttons allowing users to switch seamlessly between Sales and Customer dashboards
- Filters by:
  - Product Category & Subcategory
  - Geographic attributes (Region, State, City)

---

## 📁 Dataset
The raw datasets used in this project are stored in the `datasets/` folder and include:
- Orders data
- Customer information
- Product and subcategory details
- Location data

These datasets were integrated and modelled within Tableau to support KPI calculations, YoY comparisons, and interactive filtering.

---

## 📂 Tableau Workbook (Interactive Version)
A packaged Tableau workbook is provided for full interactivity and reproducibility.

- File: `tableau/sales_customers_dashboard.twbx`
- Includes all dashboards, calculated fields, parameters, and filters
- Intended for technical review and further exploration in Tableau Desktop

---

## 💡 Key Insights
- Sales and profit show consistent growth across selected years, with strong seasonal patterns
- A limited number of product subcategories contribute disproportionately to overall profit
- Weekly trend analysis highlights periods of volatility that may require operational attention
- Customer analysis reveals that a small group of customers generates a significant share of total profit
- Most customers place a limited number of orders, indicating opportunities for retention and upselling

---

## 🚀 Business Recommendations
- Prioritise retention strategies for high-value customers identified through profit-based ranking
- Focus inventory and promotional planning on high-margin product subcategories
- Investigate subcategories with high sales but low or negative profitability
- Use weekly trend monitoring to proactively respond to performance fluctuations
