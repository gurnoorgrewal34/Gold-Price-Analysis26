Gold Price Analysis Dashboard (2016–2026)

Project Overview
This project analyzes historical gold price data from 2016 to 2026 to identify trends, volatility, and key insights. It demonstrates an end-to-end data analysis workflow using Alteryx for data preparation and Power BI for visualization.

---

Tools Used

* Alteryx Designer (Data Cleaning & Transformation)
* Power BI Desktop (Dashboard & Visualization)
* Excel/CSV (Data Source)

---

How to Run This Project (Step-by-Step)

Step 1: Install Alteryx

* Go to the official Alteryx website
* Download Alteryx Designer (Non-Admin version)
* Install and open the application

Step 2: Activate License

* Open Alteryx Designer
* Sign in or create an account
* Activate the free trial license

Step 3: Run the Workflow

* Open the file: workflow.yxmd
* Update the input file path if required
* Click Run

Step 4: Generate Cleaned Data

* The workflow will generate a cleaned dataset named:
  Gold_Analysis_Output.csv

Step 5: Open Power BI

* Open Power BI Desktop
* Click Get Data → Text/CSV
* Load Gold_Analysis_Output.csv

Step 6: View Dashboard

* Open dashboard.pbix
* Explore charts, filters, and insights

---

Workflow Summary

Data Preparation (Alteryx)

* Cleaned raw dataset (handled %, K values, null values)
* Converted data types from string to numeric and date
* Created new columns:

  * Month_G (monthly aggregation)
  * Price_Range (volatility calculation)
* Aggregated daily data into monthly insights

Data Visualization (Power BI)

* Monthly and Yearly Trend Analysis
* Volatility Analysis
* Top 5 Highest Price Months
* KPI Cards (Maximum, Minimum, Average Price)
* Interactive filters for dynamic analysis

---

Key Insights

* Gold prices show a strong upward trend from 2016 to 2026
* Significant growth is observed after 2023
* Volatility increases in recent years (2025–2026)
* Peak prices occur in late 2025 and early 2026

---

Project Files

* Gold_Analysis_Output.csv → Cleaned dataset
* workflow.yxmd → Alteryx workflow
* dashboard.pbix → Power BI dashboard
* dashboard_screenshot.png → Dashboard preview

---

Conclusion
This project demonstrates a complete data analysis pipeline:
Raw Data → Cleaning → Transformation → Visualization → Insights



Now sleep peacefully 😄
And if tomorrow you want → I’ll make your **resume section + interview answers 💯**
