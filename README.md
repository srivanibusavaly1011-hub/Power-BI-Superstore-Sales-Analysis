# 📊 Power BI Superstore Sales Analysis Dashboard

## 📌 Project Overview

This project is an interactive Power BI dashboard created using the Sample Superstore dataset.

The objective is to analyze sales performance, customer behavior, regional performance, product performance, and profitability to support data-driven business decisions.

The dashboard contains three pages:

- Executive Sales Dashboard
- Customer Analysis Dashboard
- Profit Analysis Dashboard

---

## 🛠️ Tools & Technologies

- Power BI
- Power Query
- DAX
- Microsoft Excel
- Data Cleaning
- Data Visualization

---

## 📊 Dashboard Pages

### 1. Executive Sales Dashboard

Analyzes overall business performance, including:

- Total Sales
- Total Profit
- Total Orders
- Total Quantity
- Sales by Category
- Sales by Region
- Top 10 Products
- Sales by Sub-Category
- Monthly Sales Trend

### 2. Customer Analysis Dashboard

Analyzes customer and order performance:

- Total Customers
- Total Orders
- Average Sales
- Average Profit
- Top Customers by Sales
- Top Customers by Profit
- Sales by Segment
- Sales vs Profit by Customer

### 3. Profit Analysis Dashboard

Focuses on profitability and loss analysis:

- Total Profit
- Profit Margin
- Average Discount
- Loss-Making Products
- Profit by Category
- Profit by Sub-Category
- Top 10 Profitable Products
- Top 10 Loss-Making Products
- Monthly Profit Trend

---

## 🔄 Data Preparation

The data was cleaned and transformed using Power Query.

Key activities included:

- Promoting headers
- Changing data types
- Handling date fields
- Preparing data for analysis
- Creating DAX measures

---

## 👩‍💻 My Role

- Cleaned and transformed data using Power Query
- Created DAX measures for KPIs
- Designed interactive Power BI dashboards
- Analyzed sales, customer, product, regional, and profitability trends
- Created interactive slicers and page navigation
- Derived business insights and recommendations

---

## 📐 Key DAX Measures

```DAX
Total Sales = SUM(Orders[Sales])

Total Profit = SUM(Orders[Profit])

Profit Margin =
DIVIDE([Total Profit], [Total Sales])

Average Discount =
AVERAGE(Orders[Discount])

---

## 📊 Dashboard Preview

### Executive Sales Dashboard

![Executive Sales Dashboard](Dashboard%20Screenshots/Executive_Sales_Dashboard.png)

### Customer Analysis Dashboard

![Customer Analysis Dashboard](Dashboard%20Screenshots/Customer_Analysis_Dashboard.png)

### Profit Analysis Dashboard

![Profit Analysis Dashboard](Dashboard%20Screenshots/Profit_Analysis_Dashboard.png)

---

## 👩‍💻 Author

Srivani

Skills: Power BI | SQL | Excel | Python


