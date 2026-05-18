# Retail-Performance-Snapshot--Big-Bazaar-
# 🛒 Retail Performance Snapshot (Big Bazaar) Analytics

## 📌 Project Overview
This project focuses on an end-to-end data preparation, cleaning, and business intelligence analysis of a **Big Bazaar Retail Performance dataset**. The objective was to take a raw, fragmented retail dataset, clean and restructure it using Excel and Power Query, and build analytical frameworks (KPIs, Descriptive Statistics, and Pivot Tables) to extract critical retail insights regarding sales, profitability, and customer behavior.

## 🛠️ Tools & Technologies
* **Data Cleaning & ETL:** Microsoft Excel, Power Query
* **Data Analysis & Modeling:** Pivot Tables, Descriptive Statistics, KPI Modeling
* **Documentation:** Markdown

## 📊 Key Objectives
* **ETL & Preprocessing:** Clean, transform, and denormalize fragmented retail data into a single, reliable source of truth.
* **Performance Metrics:** Formulate essential retail Key Performance Indicators (KPIs) to track business health.
* **Operational Insights:** Analyze sales performance across different product categories, regions, and time segments.
* **Descriptive Analysis:** Run statistical checks to understand sales and profit distributions, variances, and outliers.

## 🔍 Project Architecture & Workflow

### 1. Data Cleaning & Preprocessing (`Clean Data`)
* **Power Query Transformation:** Removed duplicate transactions, handled missing values, and standardized date formats.
* **Data Type Corrections:** Ensured financial columns (Sales, Profit, Discounts) were explicitly formatted as currency, and categorical data was properly encoded.
* **Structural Merging:** Combined lookup data (like Superstore samples) to build a unified transactional table ready for analytical consumption.

### 2. Descriptive Statistics
* **Distribution Analysis:** Calculated metrics including Mean, Median, Mode, Standard Deviation, and Variance for critical business values like `Sales Amount`, `Quantity`, and `Profit Margin`.
* **Outlier Detection:** Identified transaction anomalies (such as ultra-high value orders or severe loss-making transactions) to understand profit variances.

### 3. KPI & Performance Modeling (`KPIs` & `Pivot Tables`)
* **Top-Line Metrics:** Designed and computed core retail KPIs:
    * **Total Revenue & Net Profit Margin**
    * **Average Order Value (AOV)**
    * **Total Units Sold & Average Discount Percentage**
* **Multi-Dimensional Analysis:** Built dynamic Pivot Tables to slice and dice performance by:
    * **Time:** Year-over-year and month-over-month growth trends.
    * **Geography:** Top-performing regions and regional profit gaps.
    * **Product:** Segmenting performance by Category and Sub-Category to identify cash cows vs. underperforming inventory.

## 📈 Key Insights & Business Recommendations
* **Product Performance:** Identified specific sub-categories that generate high revenue but suffer from thin margins due to aggressive discounting.
* **Seasonal Peaks:** Highlighted specific quarters/months that experience sharp demand spikes, enabling better inventory and supply chain planning.
* **Discount Optimization:** Discovered that discounts above a specific threshold do not significantly boost unit volume but heavily erode net profits.

---
*Developed as a portfolio project to demonstrate proficiency in Retail Business Intelligence, data warehousing principles, and Excel/Power Query data pipeline management.*
