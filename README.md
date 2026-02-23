# Azure-Healthcare-Medallion-Data-Pipeline

## 📌 Project Overview
This project demonstrates an end-to-end data engineering solution using Azure services by implementing the Medallion Architecture (Bronze–Silver–Gold) to build scalable, secure, and analytics-ready data pipelines.

The solution ingests raw structured data into Azure Data Lake Storage Gen2, transforms it using Azure Data Factory (ETL), and delivers business insights through interactive Power BI dashboards.

---

## 🏗 Architecture

Raw CSV Data  
   ↓  
Azure Data Lake (Bronze Layer)  
   ↓  
Azure Data Factory (Data Transformation - Silver Layer)  
   ↓  
Curated & Aggregated Data (Gold Layer)  
   ↓  
Power BI Dashboard (Analytics & Reporting)

---

## ⚙️ Technologies Used

- Azure Data Lake Storage Gen2
- Azure Data Factory (ADF)
- Azure Role-Based Access Control (RBAC)
- Power BI
- SQL
- Medallion Architecture (Bronze–Silver–Gold)

---

## 🔶 Medallion Architecture Implementation

### 🥉 Bronze Layer
- Ingested raw CSV data into Azure Data Lake
- Stored original data without transformation
- Maintained data traceability

### 🥈 Silver Layer
- Cleaned null values
- Standardized column formats
- Removed duplicates
- Applied business transformation logic

### 🥇 Gold Layer
- Created aggregated datasets
- Designed reporting-ready tables
- Optimized for analytics performance

---

## 🔐 Data Governance & Security
- Implemented Role-Based Access Control (RBAC)
- Restricted access to storage containers
- Ensured secure data access policies

---

## 📊 Power BI Dashboard Features
- KPI metrics visualization
- Trend analysis charts
- Department-wise performance analysis
- Interactive slicers for dynamic filtering

---

## 🚀 Key Achievements
- Automated end-to-end ETL pipeline
- Reduced manual data processing efforts
- Designed scalable and modular data architecture
- Enabled business-ready analytics reporting

---

## 📷 Screenshots
(Add screenshots of Azure Data Factory pipeline, Data Lake structure, and Power BI dashboard here)

---

## 📚 Learnings
- Practical implementation of Azure Data Engineering concepts
- Hands-on experience with ETL automation
- Understanding of Medallion Architecture in real-world scenarios
- Data governance and cloud security best practices

---

## 👨‍💻 Author
Teja Gulivindala
