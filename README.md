# 📊 Olist E-commerce: Logistics Performance & Customer Satisfaction Analysis

[![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)]()
[![Data Modeling](https://img.shields.io/badge/Data_Modeling-Star_Schema-blue?style=for-the-badge)]()
[![DAX](https://img.shields.io/badge/DAX-Advanced_Measures-green?style=for-the-badge)]()

## 📋 Project Overview
This project is an *End-to-End* analysis of the logistics operations of **Olist**, the largest e-commerce marketplace in Brazil. The main objective is to identify supply chain bottlenecks, analyze delivery times, and demonstrate with data the direct impact that logistics delays have on the final customer experience and satisfaction.

## 🛠️ Tools & Methodology
- **Tool:** Power BI Desktop
- **ETL Process:** Power Query (handling null values, date standardization, creating calculated columns).
- **Data Modeling:** Star Schema connecting the Fact table (Orders) with multiple Dimensions (Customers, Sellers, Products, Reviews, Calendar).
- **Calculations:** Advanced DAX formulas for business metrics (KPIs, delay percentages, average times, promoter %).
- **UI/UX Design:** 3-level depth navigation, use of *Tooltips* (pop-up pages) to avoid visual clutter, and conditional formatting (Scatter plots, Data bars).

## 📂 Data Source
The data comes from the [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) hosted on Kaggle. It contains real, anonymized information from over 99,000 orders placed between 2016 and 2018.

---

## 🖥️ Dashboard Structure

The analytical panel is divided into three levels of depth:

### 1. Logistics Overview (Macro Vision)
Monitoring of global KPIs (Total Volume, Revenue, Average Delivery Times). Includes analysis of temporal trends and geographic distribution of demand.
> *(https://github.com/MarOliFernandez/Olist-logistics-dashboard/blob/main/Dashboard_Tab1.jpg)*

### 2. Operational Analysis (Bottlenecks)
Identification of inefficiencies using a Scatter Plot that cross-references delivery times and delay percentages by product category, along with a ranking of the slowest sellers and regions.
> *(Add your image here: `![Operational Analysis](Dashboard_Tab2.jpg)`)*

### 3. Customer Satisfaction (Impact on the Customer)
Analysis of the average review score. The key visual demonstrates the direct correlation between meeting deadlines and the satisfaction score, supported by a regional choropleth "heat" map.
> *(Add your image here: `![Customer Satisfaction](Dashboard_Tab3.jpg)`)*

---

## 💡 Key Business Insights
Through data analysis, the following critical conclusions were drawn for the company:
1. **The impact of delays is severe:** The average score drops drastically from **4.3 stars** (on-time orders) to **2.5 stars** (delayed orders).
2. **The main bottleneck is preparation:** The time from order confirmation to carrier handover (Processing Time) accounts for 20% to 25% of the total delivery time.
3. **Geographic disparity:** Northern and northeastern states of Brazil (e.g., Roraima, Amapá, Amazonas) record average delivery times that double the national average (up to 29 days), correlating with the worst satisfaction scores.
4. **Seasonal risk:** Volume peaks in November (Black Friday) and January generate the highest percentages of delayed orders, highlighting a lack of logistics scalability.

## 🎯 Strategic Recommendations
- Establish **internal SLAs (Service Level Agreements)** to reduce seller preparation time.
- Implement **proactive early warnings** to manage customer communication before delivery deadlines are missed.
- Anticipate the hiring of **extra logistics resources** during critical windows (November and January).

---
*If you have any questions about the data model, DAX measures, or the analysis, feel free to reach out to me on [LinkedIn](https://www.linkedin.com/in/maría-del-mar-oli-fernández-62b7b9172/).*
