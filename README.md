# 📊 Adidas US Sales Analysis Dashboard

An interactive Business Intelligence dashboard built in Power BI to analyze US retail sales performance, product category trends, and channel distribution.

## 🚀 Project Overview
This project processes and visualizes over **9,600 transactional records** of US retail data for Adidas. The goal of this dashboard is to transform raw sales data into actionable commercial insights, tracking revenue drivers, regional performance, and profitability across multiple retail partners.

---

## 📈 Key Performance Indicators (KPIs)
* **Total Revenue:** ~$900 Million ($899,902,125)
* **Total Operating Profit:** ~$332 Million ($332,134,761)
* **Total Units Sold:** 17.88 Million
* **Average Operating Margin:** 42.3%

---

## 🔍 Key Insights & Findings
* **Top Product Categories:** *Men's Street Footwear* ($208.8M) and *Women's Apparel* ($179.0M) led total revenue generation across the portfolio.
* **Leading Retail Partnerships:** Major distribution was dominated by *West Gear* ($243.0M) and *Foot Locker* ($220.1M), accounting for nearly half of total sales.
* **Sales Channels:** Performance across distribution channels showed strong physical presence alongside digital growth:
  * **In-Store:** $356.6M (39.6%)
  * **Outlet:** $295.6M (32.8%)
  * **Online:** $247.7M (27.6%)

---

## 🛠️ Tech Stack & Skills Demonstrated
* **Business Intelligence:** Power BI (Data Modeling, Interactive Slicers, Custom KPI Cards, Geographic Mapping)
* **Data Transformation & Querying:** Advanced Excel, Power Query, DAX Measures
* **Design Framework:** Fluent2 UI design integration for clean, executive-ready layouts

---

## 📊 Core DAX Measures Used
```dax
Total Revenue = SUMX('Data Sales Adidas', 'Data Sales Adidas'[Price per Unit] * 'Data Sales Adidas'[Units Sold])
