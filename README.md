# 📦 Vendor Sales Performance Analysis

[📄 View Full Report (PDF)](https://drive.google.com/file/d/your-drive-file-id/view?usp=sharing)

This project analyzes vendor-level sales and purchase performance in an e-commerce inventory environment using SQL, Python (SQLite3 + Pandas), and Power BI. The aim is to uncover actionable insights that help improve profitability, vendor efficiency, inventory movement, and pricing strategies.

---

## 📊 Business Objectives

- Identify underperforming brands for promotional or pricing optimization  
- Determine top vendors by sales and gross profit contribution  
- Analyze impact of bulk purchasing on unit cost  
- Detect low-inventory turnover and holding inefficiencies  
- Compare profit margins between high and low performing vendors

---

## 🧾 Dataset Description

The raw data is extracted from a real-world inventory system and consists of **6 interconnected tables**, ingested into a SQLite database:

| Table Name         | Description                                 | Record Count |
|-------------------|---------------------------------------------|--------------|
| `begin_inventory` | Initial stock levels                        | 205,629      |
| `end_inventory`   | Final stock levels                          | 224,489      |
| `purchase_prices` | Unit-level pricing details                  | 12,261       |
| `purchases`       | Purchase order data                         | 2,372,474    |
| `sales`           | Sales transactions                          | 12,825,363   |
| `vendor_invoice`  | Invoice and freight cost info               | 4,453        |

🔗 [**Download the dataset here**](https://drive.google.com/file/d/your-dataset-link/view?usp=sharing)

---

## 🛠️ Tools & Technologies Used

- **Python** (`pandas`, `sqlite3`)
- **SQL** (CTEs, aggregation, joins, filtering)
- **Power BI** (interactive dashboard & visualizations)

---

## 📌 Key Findings

- 📉 **$2.71M in unsold inventory** tied to low-turnover vendors  
- 🧾 **Top 10 vendors** account for 65% of purchases, suggesting dependency  
- 💰 **Bulk buyers** pay ~72% lower unit prices, encouraging large-volume discounts  
- 📈 High-margin vendors often lack volume, while high-volume vendors have tighter margins  
- 📊 Significant statistical difference found in profit margins between top and bottom performers

---

## ✅ Final Recommendations

- Optimize pricing for low-sales, high-margin brands  
- Reduce reliance on a few vendors by diversifying partnerships  
- Leverage bulk-buying to cut costs  
- Improve marketing/distribution for low-performing vendors  
- Address slow-moving inventory via clearance or purchase planning  

---

