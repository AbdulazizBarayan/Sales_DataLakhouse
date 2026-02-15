# Sales Data Lakehouse

## 📌 Overview
This project demonstrates an end-to-end Data Engineering pipeline built using Databricks and PySpark following the Medallion Architecture (Bronze, Silver, Gold).

The pipeline processes raw sales data and transforms it into an analytics-ready Star Schema model.

---

## 🏗 Architecture

The project follows the Medallion Architecture:

- **Bronze Layer** – Raw data ingestion (unprocessed source data)
- **Silver Layer** – Data cleaning and transformation using PySpark
- **Gold Layer** – Business-ready data modeling (Star Schema)

---

## 📊 Data Modeling

Transformed 6 raw tables into:

- 1 Fact table (Sales)
- 2 Dimension tables (Customer, Product)

Designed to support analytical reporting and BI tools.



---

## 🛠 Technologies Used

- Databricks
- PySpark
- SQL
- Delta Lake
- Star Schema Modeling

---

## 🚀 Key Learnings

- Practical implementation of Medallion Architecture
- Understanding the difference between Data Processing and Data Modeling
- Designing scalable and analytics-ready data pipelines
