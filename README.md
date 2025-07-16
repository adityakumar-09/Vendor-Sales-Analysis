# 📦 Vendor Sales Performance Analysis

[📄 View Full Report (PDF)](https://drive.google.com/file/d/your-report-link-id/view?usp=sharing)

This project analyzes vendor-level sales and purchase performance in an e-commerce inventory environment using SQL, Python, and Power BI. It highlights key patterns in sales, profitability, inventory inefficiencies, and vendor performance to support strategic decision-making.

---

## 📊 Business Objectives

- Identify top & bottom-performing vendors by sales, profit, and purchase behavior  
- Uncover unsold inventory impact across low-volume brands  
- Compare margins between volume-driven and premium pricing strategies  
- Analyze purchase concentration and vendor dependency

---

## 🧾 Dataset Description

The analysis is based on 6 raw tables ingested into SQLite for modeling:

| Table Name         | Description                                 | Record Count |
|-------------------|---------------------------------------------|--------------|
| `begin_inventory` | Initial stock levels                        | 205,629      |
| `end_inventory`   | Final stock levels                          | 224,489      |
| `purchase_prices` | Unit-level pricing details                  | 12,261       |
| `purchases`       | Purchase order data                         | 2,372,474    |
| `sales`           | Sales transactions                          | 12,825,363   |
| `vendor_invoice`  | Invoice and freight cost info               | 4,453        |

📂 [**Download the dataset**](https://drive.google.com/file/d/your-dataset-link-id/view?usp=sharing)

---

## 🛠️ Tools & Technologies

- **Python**: `pandas`, `sqlite3`
- **SQL**: Joins, CTEs, aggregations
- **Power BI**: Dashboards, visual storytelling
- **SQLite**: Data modeling & query execution

---

## 📌 Key Insights

- 💸 Unsold inventory amounts to **$2.71M**
- 🏆 Top 10 vendors account for **65%** of purchases
- 📉 Low-performing vendors have profit margins as low as **0.62**
- 📈 Bulk purchases yield **~72% cheaper unit cost**
- 🔍 Distinct margin patterns between target and non-target brands

---

## 📑 Exploratory Data Analysis

The initial data cleaning, profiling, and aggregation logic is documented in the following notebook:

📘 [`exploratory_data_analysis.ipynb`](notebooks/exploratory_data_analysis.ipynb)

---

## 📊 Power BI Dashboard

Below is the final Power BI visualization used to present business insights:

![Vendor Sales Power BI Dashboard](https://raw.githubusercontent.com/your-username/your-repo/main/visuals/vendor_sales_dashboard.png)

> 💡 Includes KPIs for sales, purchase, gross profit, profit margin, unsold capital, and vendor-level contributions.

---
