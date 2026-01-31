# 💊 Pharmacy Sales & Profitability Analytics Dashboard (Power BI)
Power BI dashboard analyzing pharmacy sales performance, regional trends, and product insights.

## 📌 Project Overview
This project analyzes sales and profitability data for a **European pharmacy chain distributor** operating across multiple countries.  
The goal is to provide **actionable business insights** into sales trends, regional performance, pharmacy benchmarking, product analytics, and promotional effectiveness using **Power BI**.

The dashboard was built as part of the **Onyx Data – Pharmacy Analytics Data Challenge** and is designed to simulate a real-world business intelligence solution.

---

## 🎯 Business Objectives
The dashboard helps stakeholders answer key business questions such as:
- How do **revenue, units sold, and margin** change over time?
- Are there clear **seasonal patterns** in sales?
- Which **countries and regions** contribute the most to total revenue and margin?
- How does performance vary when drilling down from **country → region → pharmacy**?
- Which pharmacies **outperform or underperform** compared to others in the same region?
- How do **Urban, Suburban, and Rural** pharmacies differ in sales volume and profitability?
- Which **product categories and brands** generate the most revenue and margin?
- Are there **high-volume, low-margin** or **low-volume, high-margin** products?
- How do **promoted vs non-promoted** sales compare?
- Are there visible **geographic patterns** in sales and profitability?

---

## 🗂️ Dataset Description
**Source:** Onyx Data Challenge  
**Granularity:** Daily sales transactions by pharmacy and product  

### Data Model (Star Schema)
- **FactSales**
  - SalesID, DateKey, PharmacyID, ProductID
  - Units Sold, Revenue, Cost, Margin
  - Promo Flag
- **DimDate**
  - Date, Year, Quarter, Month, YearMonth
- **DimPharmacy**
  - Country, Region, City, Pharmacy Type (Urban/Suburban/Rural)
  - Store size and location details
- **DimProduct**
  - Category, Brand, Generic flag
  - Price, Cost, Launch & Discontinuation info

---

## 📊 Dashboard Pages & Key Insights

### 🔹 1. Sales Overview
**Visuals Used**
- KPI Cards (Revenue, Units Sold, Margin %, Promo Sales)
- Revenue Trend (YoY & YTD)
- Revenue by Region
- Seasonal Pattern by Month
- Generic vs Non-Generic Revenue Split

**Key Insights**
- Revenue shows consistent **YoY growth** with stable margins
- Strong **seasonal peaks** observed in mid-year months
- Non-generic products contribute the majority of total revenue

---

### 🔹 2. Product Analytics
**Visuals Used**
- High Volume vs Low Margin Scatter Chart
- Revenue by Product Category
- Revenue by Brand
- Product Performance Table

**Key Insights**
- Certain OTC products have **high sales volume but lower margins**
- Prescription products tend to deliver **higher margin percentages**
- Revenue is concentrated among a small set of top-performing brands

---

### 🔹 3. Pharmacy Performance
**Visuals Used**
- Drill-down analysis (Country → Region → Pharmacy)
- Pharmacy benchmarking with **average line**
- Urban vs Suburban vs Rural comparison
- Pharmacy Type KPI Matrix with indicators

**Key Insights**
- Urban pharmacies drive the **highest sales volume**
- Suburban pharmacies show a **balanced mix of volume and margin**
- Clear **outperformers and underperformers** identified within regions

---

## 📈 Key KPIs Tracked
- Total Revenue
- Total Units Sold
- Margin %
- Revenue YTD
- Year-over-Year (YoY) Growth %
- Promotional Revenue
- Average Transaction Value
- Pharmacy Count

---

## 🧮 Key DAX Concepts Used
- Time intelligence (YTD, YoY)
- Dynamic averages for benchmarking
- Conditional formatting for performance indicators
- Calculated measures for margin and promo analysis

---

## 🛠️ Tools & Technologies
- **Power BI Desktop**
- **DAX**
- **Power Query**
- **Data Modeling (Star Schema)**

---

## 💡 Business Value
This dashboard enables decision-makers to:
- Identify **top-performing regions and pharmacies**
- Optimize **product mix and promotional strategies**
- Detect **low-margin, high-volume products** for pricing review
- Understand **regional contribution** to overall business performance
- Support data-driven expansion and optimization decisions

---

## 🚀 Future Enhancements
- Sales and demand **forecasting**
- Inventory optimization analysis
- Target vs Actual performance tracking
- Customer-level or basket analysis
- Automated Power BI Service refresh & sharing

---

## 📸 Dashboard Preview
Screenshots of all dashboard pages are available in the `Dashboard_Screenshots` folder.

---

## 👤 Author
**DHIVYA PRIYA. A**  
Power BI | Data Analytics | Business Intelligence  

---

⭐ *If you found this project useful, feel free to star the repository!*  
