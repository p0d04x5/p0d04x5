# 🚀 Databricks Medallion Retail Pipeline

![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-FDEE21?style=for-the-badge&logo=apachespark&logoColor=black)
![Delta Lake](https://img.shields.io/badge/Delta_Lake-003366?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Medallion Architecture](https://img.shields.io/badge/Architecture-Medallion-blue?style=for-the-badge)

---

## 📌 Project Overview

This project demonstrates a **Retail Sales Data Engineering Pipeline** built using **Azure Databricks** following the **Medallion Architecture (Bronze → Silver → Gold)**.

The pipeline ingests raw data, transforms it, and builds business-ready fact and dimension tables using Delta Lake.

It is fully orchestrated using **Databricks Workflows**.

---

## 🏗 Architecture
Raw Data
↓
Bronze Layer (Raw Ingestion)
↓
Silver Layer (Cleaned & Transformed)
↓
Gold Layer (Fact & Dimension Tables)
↓
Analytics / Reporting


I designed a Medallion Architecture pipeline in Azure Databricks.
Raw retail data is ingested into the Bronze layer and stored in Delta format.
The Silver layer applies cleaning and transformations.
The Gold layer builds dimensional and fact tables for analytics.
The entire pipeline is orchestrated using Databricks Workflows with task dependencies to ensure layer-by-layer execution.


## 📂 Folder Structure
databricks-medallion-retail-pipeline/bronze/silver/gold

---

## 🔹 Bronze Layer

- Loads raw retail data
- Stores data in Delta format
- Ensures schema consistency

---

## 🔹 Silver Layer

- Cleans null values
- Applies transformations
- Standardizes schema

---

## 🔹 Gold Layer

Creates business-level tables:

- Customer Dimension
- Product Dimension
- Sales Fact Table

---

## ⚙️ Pipeline Orchestration

The pipeline is orchestrated using **Databricks Workflows** with task dependencies:

1️⃣ Bronze Ingestion  
2️⃣ Silver Transformation  
3️⃣ Gold Dimension Tables  
4️⃣ Gold Fact Table  

Each task depends on the successful completion of the previous layer.

---

## 🛠 Tech Stack

- Azure Databricks
- Apache Spark (PySpark)
- Delta Lake
- Databricks Workflows
- Python

---

## 📊 Key Concepts Implemented

- Medallion Architecture
- Incremental Processing
- Delta Lake Optimization
- Fact & Dimension Modeling
- Workflow Orchestration

---

## 📚 Learning Reference

This project was implemented as part of hands-on learning inspired by:
👉 DataWithBaraa - databricks_bootcamp_2026
The architecture was recreated and implemented independently in Databricks.

---

## 👩‍💻 Author

Pooja DM  
Aspiring Data Engineer 🚀
