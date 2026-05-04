# 🚚 Supply Chain Freight & Delivery Performance Dashboard

## 📊 Live Dashboard
👉 [View Live on Power BI Public] [https://app.powerbi.com/groups/me/reports/d52f24f6-9f37-41e4-8233-4b54128f3daa/54f5e42c670ee2c8609e?experience=power-bi]

## 📌 Project Overview
An end-to-end supply chain analytics dashboard built in Power BI 
analysing freight spend, delivery performance, and vendor efficiency 
across 10,334 deliveries worth $68.82M across African markets.

## 🔍 Key Insights Uncovered
- Total freight spend: **$68.82M** across all projects
- **1,186 late deliveries** identified out of 10,334 total
- Project **#1989** worst performer — avg delay of **91 days**
- **SCMS from RDC** accounts for ~50% of total freight spend
- Average cost per KG: **$3.15**

## 🛠️ Tools & Technologies
- **Power BI Desktop** — dashboard design & DAX measures
- **DAX** — custom measures for KPIs, delay analysis, 
  conditional formatting
- **Star Schema Data Model** — Fact_Deliveries + 4 dimension 
  tables (Dim_Vendors, Dim_Projects, Dim_Products, Dim_Calendar)
- **Python & Claude AI** — data profiling and cleaning
- **Azure OpenAI** — AI-assisted DAX generation and 
  data summarization

## 📐 Data Model
Star schema with central fact table connected to:
- Dim_Vendors
- Dim_Projects  
- Dim_Products
- Dim_Calendar

![Data Model](screenshots/data_model.png)

## 📈 Dashboard Features
- 4 KPI cards — Freight Spend, Weight, Cost/KG, Avg Delay
- Freight cost breakdown by Vendor (bar chart)
- Delivery performance table with conditional formatting
- Country slicer for geographic filtering
- Filled map showing freight distribution by country

## 💡 AI Usage in This Project
- Used **Claude** to generate and debug DAX measures
- Used **LLMs** for data quality checks and anomaly detection
- AI-assisted README and documentation writing
