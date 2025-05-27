# Tailwind-Traders-Microsoft-Power-BI-Capstone-Project


# 🧾 Tailwind Traders – Microsoft Power BI Capstone Project

This project was completed as part of the Microsoft Power BI Professional Certificate. It demonstrates end-to-end data analysis and report building using Excel, Power Query, DAX, and Power BI Service.

---

## 📦 Project Scope

Tailwind Traders, a fictional retail company, provided raw datasets. The goal was to:

- Prepare and model data using Excel and Power BI
- Configure relationships across datasets
- Create calculated fields using DAX
- Design insightful dashboards and reports
- Publish interactive reports to the Power BI Service
- Configure alerts and subscriptions for stakeholders

---

## 📊 Key Features

### 1. **Excel Preprocessing**
- Created columns: Gross Revenue, Total Tax, Net Revenue
- Used formulas: `=E2*G2`, `=F2*G2`, `=H2-I2`
- Validated record distribution by observing min/max values

### 2. **Power BI ETL**
- Imported Excel and CSV files
- Applied transformations via Power Query
- Used Python script to load exchange rate data

### 3. **Data Modeling**
- Built a snowflake schema
- Created Calendar table via DAX
- Established bidirectional relationships

### 4. **DAX Measures**
- Yearly, Quarterly, and YTD Profit Margins
- Median Sales using `MEDIAN()` function
- Gross Revenue USD, Net Revenue USD, Total Tax USD

### 5. **Reports Created**
- **Sales Overview**: Loyalty by Country, Quantity by Product, Median Sales, Cards
- **Profit Overview**: Net Revenue by Product, Profit Margins, KPI Visuals
- **Executive Dashboard**: Mobile-compatible, summarized insights for stakeholders

### 6. **Power BI Service**
- Published dashboards and reports
- Configured data alerts (e.g., Gross Revenue < $400)
- Created weekly email subscriptions for Sales and Profit summaries

---

## ⚙️ Tools Used
- Microsoft Excel
- Power BI Desktop
- Power BI Service
- DAX, Power Query
- Python (StringIO, pandas)
