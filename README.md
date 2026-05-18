# 🌿 Global Skincare & Beauty E-Store — Power BI Analytics Dashboard

> **Course Project | Big Data Technologies | University of Delaware — MS Data Science (Spring 2026)**
> Built by **Bhargav Pathuri** | [LinkedIn](https://www.linkedin.com/in/bhargav-pathuri-2486b61a7)

---

## 📌 Project Overview

This end-to-end Power BI project analyzes a global skincare and beauty e-commerce store's transactional data across **164 countries**, **5 markets**, and **4 years (2020–2023)**. The goal was to uncover actionable insights around sales performance, profitability, customer behavior, and product trends — while demonstrating advanced Power BI capabilities from data modeling to DAX to interactive storytelling.

The project was completed as the **final capstone** for the *Big Data Technologies* course and mirrors real-world analyst work I performed during my tenure at **Wipro** building Power BI dashboards for RSA Insurance Group.

---

## 📂 Repository Contents

```
├── Bhargav_Pathuri_Project3.pbix          # Power BI Desktop file (7 report pages)
├── Global_skincare_and_Beauty_e-store_    
│   E-commerce_Analysis_English.xlsx       # Source dataset (51,290 rows)
└── README.md
```

---

## 📊 Dataset Summary

| Attribute | Details |
|---|---|
| **Source** | Global Skincare & Beauty E-Store (simulated e-commerce) |
| **Rows** | 51,290 transactions |
| **Time Period** | January 2020 – December 2023 |
| **Markets** | Asia Pacific, Europe, LATAM, USCA, Africa |
| **Countries** | 164 |
| **Categories** | Body Care, Face Care, Hair Care, Make Up, Home & Accessories |
| **Subcategories** | 17 (incl. Lipsticks, Foundations, Shampoos, Fragrances, etc.) |
| **Customer Segments** | Consumer, Corporate, Self-Employed |
| **Key Metrics** | Sales (~$6.5M), Profit (~$1.06M), Quantity, Discount |

---

## 📋 Business Questions Answered

The 7 dashboard pages were designed to answer the following analytical questions:

1. **Executive Overview** — What is the overall business performance? How are Sales, Profit, and Quantity trending YoY?
2. **Sales by Geography** — Which markets and countries drive the most revenue? Where are the growth opportunities?
3. **Product Performance** — Which categories and subcategories are most profitable? What products have the highest return?
4. **Customer Segmentation** — How do Consumer, Corporate, and Self-Employed segments behave differently?
5. **Discount Impact Analysis** — How does discounting affect profit margins across categories and markets?
6. **Time Intelligence & Trends** — What are the seasonal patterns? How does YTD/QTD performance compare?
7. **KPI Summary / Executive Scorecard** — A single-page executive summary with all critical KPIs at a glance.

---

## 🛠️ Power BI Concepts & Features Used

### Data Preparation (Power Query)
- Data type corrections and null handling
- Column renaming and custom column creation
- Date table generation for time intelligence
- Merging and transforming raw Excel data

### Data Modeling
- Star schema design (Fact + Dimension tables)
- Relationships across Order, Customer, Product, Geography, and Date tables
- Cardinality and cross-filter direction configuration

### DAX Measures
- `Total Sales`, `Total Profit`, `Profit Margin %`
- `YoY Sales Growth`, `YoY Profit Growth`
- `YTD Sales`, `QTD Profit` using `TOTALYTD`, `TOTALQTD`
- `Running Total Sales` using `CALCULATE` + `DATESYTD`
- `Sales Rank by Country` using `RANKX`
- `Discount Impact` — custom measure showing profit loss from discounting
- Dynamic titles using `SELECTEDVALUE`

### Visualizations
- Clustered Bar & Column Charts
- Line and Area Charts (trend analysis)
- Map Visual (geo distribution)
- Matrix with conditional formatting
- KPI Cards and Multi-row Cards
- Treemap (category/subcategory breakdown)
- Scatter Plot (Sales vs. Profit by Subcategory)
- Decomposition Tree
- Slicers with sync across pages

### Advanced Features
- **Bookmarks & Buttons** for toggle views and navigation
- **Drill-through** pages for country-level and product-level deep dives
- **Tooltip Pages** — custom hover tooltips on visuals
- **Dynamic Titles** changing based on slicer selection
- **Field Parameters** for user-controlled axis switching
- **Conditional Formatting** on tables and matrices
- **Row-Level Security (RLS)** concept applied for market-based access

---

## 🔍 Key Insights Discovered

- **Asia Pacific** is the highest-grossing market, but **USCA** has the best profit margin.
- **Make Up** has strong sales volume but lower margins due to higher discount rates.
- **Face Care** — specifically face moisturizing products — yields the highest profit per unit.
- **Corporate segment** drives the highest average order value; **Self-Employed** shows the most discount-sensitive behavior.
- Discounts above **30%** consistently result in negative profit across all categories.
- Strongest sales peak in **Q4 each year** — driven by holiday season demand in USCA and Europe.
- **2022** was the highest revenue year; **2023** showed slight dip likely tied to increased discount activity.

---

## 🚀 How to Use

1. Download `Bhargav_Pathuri_Project3.pbix` and `Global_skincare_and_Beauty_e-store_E-commerce_Analysis_English.xlsx`
2. Place both files in the **same folder**
3. Open the `.pbix` file in **Power BI Desktop** (free download from Microsoft)
4. If prompted, refresh the data source and point it to the `.xlsx` file in your local folder
5. Explore all 7 report pages using the navigation buttons or the tab bar at the bottom

> **Note:** Power BI Desktop is required to open `.pbix` files. It is free and available at [powerbi.microsoft.com](https://powerbi.microsoft.com/desktop)

---

## 👤 About the Author

**Bhargav Pathuri** — MS Data Science, University of Delaware (GPA: 3.8)

Previously worked as a **Data Analyst at Wipro** (2021–2024), building Power BI dashboards and conducting EDA for RSA Insurance Group. This project was built to sharpen and showcase those same real-world analytics skills in an academic setting.

Currently open to **Data Analyst, Business Intelligence, and Data Science** opportunities.

📧 bpathuri@udel.edu 
📧 pathuribhargav99@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/bhargav-pathuri-2486b61a7)

---

## 📄 License

This project is for educational and portfolio purposes. The dataset is publicly available for learning use.
