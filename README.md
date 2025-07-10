# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project
highlights industry best practices in data engineering and analytics.

---

## 📘 Project Overview

This project involves:

1. **Data Architecture**: Designing a Modern Data Warehouse Using Medallion Architecture **Bronze**, **Silver**, and **Gold** layers.  
2. **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.  
3. **Data Modeling**: Developing fact and dimension tables optimized for analytical queries.  
4. **Analytics & Reporting**: Creating SQL-based reports and dashboards for actionable insights.

🎯 This repository is an excellent resource for professionals and students looking to showcase expertise in:

- SQL Development  
- Data Architect  
- Data Engineering  
- ETL Pipeline Developer  
- Data Modeling  
- Data Analytics

---

## 🚀 Project Requirements

### Building the Data Warehouse (Data Engineering)

#### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

#### Specifications
- **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality**: Cleanse and resolve data quality issues prior to analysis.
- **Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scoper**: Focus on the latest dataset only; historization of data is not required.
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.

---

### BI: Analytics & Reporting (Data Analytics)

#### Objective
Develop SQL-based analytics to deliver detailed insights into:
- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

These insights empower stakeholders with key business metrics, enabling strategic decision-making

---

## 🏗️ Data Architecture

[data_architecture.pdf](https://github.com/user-attachments/files/21171285/data_architecture.pdf)

The data architecture for this project follows **Medallion Architecture**:  
**Bronze**, **Silver**, and **Gold** layers:

### Sources → Data Warehouse → Consume

**Sources**:  
- CRM, ERP systems  
- Object Type: CSV Files  
- Interface: Files in Folders  

---

### 🔶 Bronze Layer
- **Description**: Stores raw data *as-is* from the source systems.  
- **Load**:  
  - Batch Processing  
  - Full Load  
  - Truncate & Insert  
- **Transformations**: None  
- **Data Model**: None (as-is)  
- **Storage**: Tables in SQL Server  

---

### ⚪ Silver Layer
- **Description**: Cleansed and standardized data.  
- **Load**:  
  - Batch Processing  
  - Full Load  
  - Truncate & Insert  
- **Transformations**:  
  - Data Cleansing  
  - Data Standardization  
  - Data Normalization  
  - Derived Columns  
  - Data Enrichment  
- **Data Model**: Cleaned Tables  

---

## 🛡️ License 

This project is licensed under [MIT License]. You are free to use, modify, and share this project with proper attribution.

## About Me

Hi there! I'm **Dawid Ryskala**. I am BI Developer | Data Analyst ...
