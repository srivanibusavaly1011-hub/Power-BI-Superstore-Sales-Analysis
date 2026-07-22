# 📊 Power BI Superstore Sales Analysis

## 📌 Project Overview

This project presents an interactive **Power BI Sales Analysis Dashboard** created using the Superstore dataset.

The objective of this project is to analyze sales performance, profitability, customers, products, regions, categories, and sub-categories to generate meaningful business insights and support data-driven decision-making.

---

## 🛠️ Tools & Technologies

- Power BI
- SQL
- Excel
- DAX
- Python

---

## 📂 Dataset

The dataset used for this project is the **Superstore Sales Dataset**.

The dataset contains information about:

- Orders
- Customers
- Products
- Categories
- Sub-Categories
- Sales
- Profit
- Discount
- Quantity
- Regions
- Segments
- Order Dates

---

## 📊 Dashboard Pages

### 1️⃣ Executive Sales Dashboard

This dashboard provides an overview of the overall sales performance.

### Key KPIs:

- Total Sales
- Total Profit
- Total Orders
- Total Quantity

### Key Analysis:

- Top 10 Products by Sales
- Sales by Category
- Sales by Region
- Sales by Sub-Category
- Monthly Sales Trend

---

### 2️⃣ Customer Analysis Dashboard

This dashboard focuses on customer performance and customer-level insights.

### Key KPIs:

- Total Customers
- Total Orders
- Average Profit
- Average Sales

### Key Analysis:

- Orders by Region
- Top 10 Customers by Sales
- Top Customers by Profit
- Sales by Segment
- Sales vs Profit by Customer

---

### 3️⃣ Profit Analysis Dashboard

This dashboard focuses on profitability and loss-making products.

### Key KPIs:

- Total Profit
- Profit Margin
- Average Discount
- Loss-Making Products

### Key Analysis:

- Monthly Profit Trend
- Profit by Category
- Top 10 Profitable Products
- Top 10 Loss-Making Products
- Profit by Sub-Category

---

## 📈 Key Business Insights

- Technology generated the highest profit among the major categories.
- Office Supplies also contributed significantly to overall profitability.
- Some products generated negative profits and require further investigation.
- A small number of products contributed significantly to total sales.
- Profitability varies across different regions and customer segments.
- High discounts can negatively impact product profitability.
- Monthly profit trends help identify periods of strong and weak performance.

---

## 🧮 DAX Measures

```DAX
Total Sales = SUM(Orders[Sales])

Total Profit = SUM(Orders[Profit])

Profit Margin =
DIVIDE([Total Profit], [Total Sales])

Average Discount =
AVERAGE(Orders[Discount])
```

---

## 👩‍💻 My Role – Data Analyst

As a Data Analyst, I worked on this project to transform raw sales data into meaningful business insights.

My responsibilities included:

- Cleaning and preparing the dataset for analysis.
- Performing data analysis using SQL and Excel.
- Creating data models and relationships in Power BI.
- Developing DAX measures for KPIs such as Sales, Profit, Profit Margin, and Average Discount.
- Designing interactive dashboards and reports using Power BI.
- Analyzing sales, profit, customers, products, regions, categories, and sub-categories.
- Identifying top-performing and loss-making products.
- Creating monthly sales and profit trend analysis.
- Generating insights to support data-driven business decisions.

  ---

## 📸 Dashboard Preview

### Executive Sales Dashboard

![Executive Sales Dashboard](Executive%20Sales%20Dashboard.png)

### Customer Analysis Dashboard

![Customer Analysis Dashboard](Customer%20Analysis%20Dashboard.png)

### Profit Analysis Dashboard

![Profit Analysis Dashboard](Profit%20Analysis%20Dashboard.png)

---

## 📁 Project Files

- `Superstore_Sales_Analysis.pbix` – Power BI Dashboard
- `sample_-_superstore.xls` – Dataset
- `Executive Sales Dashboard.png` – Executive Sales Dashboard Screenshot
- `Customer Analysis Dashboard.png` – Customer Analysis Dashboard Screenshot
- `Profit Analysis Dashboard.png` – Profit Analysis Dashboard Screenshot

---

## 👩‍💻 Author

**Srivani**

### Skills

Power BI | SQL | Excel | Python

---

⭐ If you find this project useful, feel free to explore the repository.
