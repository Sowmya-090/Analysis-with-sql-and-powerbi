# Analysis-with-sql-and-powerbi
# Axon Business Analysis

## 📋 Overview
This project implements a **Business Intelligence (BI) solution** for Axon, a company selling classic cars. Using **Power BI** and **SQL**, the project analyzes and visualizes sales data from a MySQL database, focusing on sales trends, customer behavior, and promotional effectiveness.

---

## 🛠️ Key Steps

### Data Integration & Transformation
- Imported and cleaned sales data (2003–2005) using **Power Query** in Power BI.
- Created custom columns for key metrics:
  - `Sales = Quantity Ordered * Price Each`
  - `Profit = Sales - Margin`
- Performed advanced transformations, such as merging columns and handling null values.

### SQL Processing
- Used SQL queries for deeper analytics:
  - Total sales by year, product line, and customers.
  - Customer acquisition trends.
  - Promotion effectiveness and growth analysis.
- Leveraged joins and calculations across tables like `Orders`, `OrderDetails`, `Customers`, and `Products`.

### Power BI Visualizations
- Created interactive dashboards with:
  - **KPI Cards**: Total Sales, Profit, Orders, and Customers.
  - **Stacked Charts**: Sales trends and product category analysis.
  - **Pie & Waterfall Charts**: Sales distribution and top-performing products.
  - **Tornado & Bar Charts**: Customer distribution by country and performance comparisons.

---

## 🔍 Insights
- **Sales Trends**:
  - Top-performing products and categories identified.
  - Significant growth observed in key product lines (2003–2005).
- **Customer Behavior**:
  - High-value customers and acquisition rates analyzed.
- **Promotion Effectiveness**:
  - Evaluated the impact of discounts and promotional campaigns on sales.

---

## 🚀 Impact
- Real-time dashboards for management to track performance and trends.
- Data-driven strategies to improve customer engagement and profitability.

---
