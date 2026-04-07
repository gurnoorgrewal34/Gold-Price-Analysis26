# 🟡 Gold Price Analysis Dashboard (2016–2026)

## 📌 Project Overview
This project analyzes historical gold price data from 2016 to 2026 to identify trends, volatility, and key insights. The workflow includes data cleaning, transformation, and visualization using Alteryx and Power BI.

---

## ⚙️ Tools Used
- Alteryx Designer (Data Cleaning & Transformation)
- Power BI (Dashboard & Visualization)
- Excel/CSV (Data Source)

---

## 🔄 Workflow

### 1. Data Preparation (Alteryx)
- Cleaned raw dataset (handled %, K values, nulls)
- Converted data types (string → numeric/date)
- Created new fields:
  - Monthly aggregation (Month_G)
  - Price Range (Volatility)
- Generated summarized dataset (monthly level)

---

### 2. Data Visualization (Power BI)
Created an interactive dashboard with:
- 📈 Monthly & Yearly Price Trends
- 📊 Volatility Analysis
- 🏆 Top 5 Highest Price Months
- 📌 KPI Metrics (Max, Min, Average)
- 🎛 Filters for dynamic analysis

---

## 📊 Key Insights
- Gold prices show a strong upward trend over the years
- Significant growth observed after 2023
- Volatility increased in recent years (2025–2026)
- Peak prices occurred in late 2025 and early 2026

---

## 📁 Project Files
- `Gold_Analysis_Output.csv` → Cleaned dataset
- `workflow.yxmd` → Alteryx workflow
- `dashboard.pbix` → Power BI dashboard
- `dashboard_screenshot.png` → Dashboard preview

---

## 🚀 Conclusion
This project demonstrates end-to-end data analysis:
- Data cleaning → Transformation → Visualization → Insights

