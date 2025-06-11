# 🚗 aws-etl-pipeline-cars

This project simulates a data engineering pipeline for a model car retailer. As a Data Engineer, the goal is to build a robust ETL pipeline that extracts sales data from a relational database on AWS, transforms it into a star schema, and enables efficient querying and visualization.

---

## 🧰 Tech Stack

* **AWS RDS (MySQL)** – Source system storing raw sales data
* **AWS Glue** – ETL service to transform and structure the data into a star schema
* **Amazon S3 (Parquet)** – Data lake for storing transformed data efficiently
* **Amazon Athena** – Serverless querying of S3 data using SQL
* **Jupyter Notebook** – Analyst-friendly dashboard for insights and exploration

---

## 🛠️ Pipeline Overview

**Data Flow:**

```
MySQL (RDS)
   ↓
AWS Glue (ETL + star schema transformation)
   ↓
Amazon S3 (Parquet format)
   ↓
Amazon Athena (SQL Queries)
   ↓
Jupyter Notebook (Data Visualisation)
```

---

## ✅ Objectives

* **Extract** raw sales data from AWS RDS (MySQL)
* **Transform** the data into a star schema (fact + dimension tables)
* **Load** the structured data into Amazon S3 in Parquet format
* **Query** using Amazon Athena for fast analytics
* **Visualise** using Python (Pandas, Matplotlib/Seaborn) in Jupyter Notebook

---

## 📁 Folder Structure (suggested)

```
aws-etl-pipeline-cars/
├── data
│   └── mysqlsampledatabase.sql
├── images/
│   └── ...
├── scripts
│   └── setup.sh
├── terraform
│   └── ...
├── architecture.md
├── C1_W2_Assignment.md
├── C1_W2_Assignment.ipynb
└── README.md
```
