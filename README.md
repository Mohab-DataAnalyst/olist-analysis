![Logo](https://techcrunch.com/wp-content/uploads/2021/04/Olist-HQ-in-Brazil-1.jpg)
# 📊 Olist E-Commerce Full Analysis Pipeline (Excel, Python, Power BI)

## 🔎 Project Overview
This is one of my largest self-directed, end-to-end analysis pipelines, combining technical depth with business storytelling. It was developed as part of my Elevvo Internship, using the Brazilian E-Commerce Public Dataset by Olist.

The goal was to perform a full-cycle analysis workflow:
- Clean and preprocess sales, product, and customer data  
- Conduct technical and business-oriented exploratory data analysis (EDA)  
- Build interactive dashboards for executive-level decision making  
- Translate insights into business recommendations  

---

## 🛠️ Tools & Technologies
- **Python (Jupyter Notebook):** Data Cleaning & Preprocessing, Technical EDA, Business EDA & Deep Analysis (KPIs, Trend & Time, Dimensional & Ranking, Customer Behavior & RFM, Logistics, and Correlation Analysis)
- **Excel:** Pivot tables and charts for quick KPI validation  
- **Power BI:** Four fully interactive dashboards with full interactivity, navigation, and slicers (Revenue, Customers, Products & Sellers, and Logistics dashboards)
- **Word:** Professional business report with business insights, recommendations, and executive summary

---

## 📊 Key Metrics
- **Total Revenue:** $15.4M  
- **Total Orders:** 96K  
- **Total Customers:** 96K  
- **Average Order Value (AOV):** $159.8  
- **Average Product Price:** $120.7  
- **Average Freight per Order:** $20.0  
- **Average Review Score:** 4.1  
- **% Repeating Customers:** 3.1%  
- **% High-Value Customers:** 40.8%  
- **% Late Deliveries:** 7.6%  
- **Average Delivery Time:** 12 days  

---

## 📓 Notebook Structure  
- **Importing Libraries & Reading CSVs** – Load datasets and essential libraries (pandas, numpy, matplotlib, seaborn, etc.).  
- **Data Cleaning & Technical EDA** – Clean raw data, handle missing values, and perform initial exploratory checks to prepare preprocessed datasets.  
- **Business EDA & Deep Analysis** – Conduct KPI tracking, time & trend analysis, dimensional breakdowns, ranking analysis, customer behavior & RFM analysis, logistics evaluation, and correlation studies.  
- **Raw Business Insights & Suggestions** – Summarize findings and provide actionable recommendations for improving business performance.

---

## 🗂️ Data Model  
The Power BI report is powered by a structured relational data model that integrates all key aspects of the Olist dataset.  
- **Fact tables:** Orders, Order Items, Payments, Reviews  
- **Dimension tables:** Customers, Sellers, Products, Categories, custom Date, RFM segmentation  
- **Measures:** Separate table for custom DAX calculations for KPIs (Revenue, AOV, Late Deliveries, RFM Segments, etc.)  

This modeling approach mimics the original Olist data structure and incorporates ready-for-visualization notebook dataframes, ensuring clean relationships, accurate KPI calculations, and flexible slicing across dashboards. 

---

## 📈 Dashboards

### 🔹 Revenue Dashboard
- Revenue & orders trend  
- Average order value trend  
- Monthly seasonality analysis  
- **Slicers:** Category, RFM Segment, State 

### 🔹 Customer Dashboard
- Top customer states  
- One-time vs repeating customers  
- RFM segmentation & value labels  
- Review score distribution  
- **Slicers:** Year, Month  

### 🔹 Logistics Dashboard
- Delivery performance trend  
- On-time vs late deliveries  
- Delivery time distribution  
- **Slicers:** Category, State, City  

### 🔹 Products & Sellers Dashboard
- Top seller states  
- Top categories by product quantity
- Best performing categories by revenue  
- Sellers by review distribution  
- **Slicers:** Year, Month

---

## 💡 Business Insights
- **Revenue Growth:** Clear upward trend with strong seasonal peaks.  
- **Customer Loyalty:** Only 3.1% repeat customers, yet 40.8% high-value, highlighting untapped retention opportunities.  
- **Delivery Performance:** 92% on-time, but 7.6% late deliveries show operational inefficiencies.  
- **Customer Satisfaction:** Average review score of 4.1, with logistics delays contributing to low ratings.  
- **Category Performance:** Health & beauty and watches & gifts lead in revenue.  

---

## Notebook, Data Model, and Dashboards Snapshots
<p align="center">
  <img src="https://github.com/Mohab-DataAnalyst/olist-analysis/blob/main/Notebook%20Snapshot.PNG" width="800" height="500"/>
  <img src="https://github.com/Mohab-DataAnalyst/olist-analysis/blob/main/Data%20Model%20Snapshot.PNG" width="800" height="500"/>
  <img src="https://github.com/Mohab-DataAnalyst/olist-analysis/blob/main/Revenue%20Snapshot.PNG" width="800" height="500"/>
  <img src="https://github.com/Mohab-DataAnalyst/olist-analysis/blob/main/Customers%20Snapshot.PNG" width="800" height="500"/>
  <img src="https://github.com/Mohab-DataAnalyst/olist-analysis/blob/main/Products%20&%20Sellers%20Snapshot.PNG" width="800" height="500"/>
  <img src="https://github.com/Mohab-DataAnalyst/olist-analysis/blob/main/Logistics%20Snapshot.PNG" width="800" height="500"/>
</p>

---

## 🚀 Outcomes
This project showcases my ability to:
- Execute an end-to-end analytics workflow independently  
- Extract actionable insights from raw data  
- Design interactive dashboards for decision-making  
- Apply business storytelling for executive communication  

---

## 📜 Acknowledgments
- **Dataset:** [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce/) 
- **Developed as part of my Elevvo Internship – Data Analytics Track**  
