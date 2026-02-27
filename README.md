# 👋 Hi, I'm Pooja DM

A passionate Data Engineer with hands-on experience building **Databricks Medallion Retail Pipeline** project, **real-time** and **batch data pipelines** using modern tools and frameworks.

---

## 🚀 Projects

## Project - 1
# 🚀 Databricks Medallion Retail Pipeline

## 📌 Project Overview

This project demonstrates a **Retail Sales Data Engineering Pipeline** built using **Azure Databricks** following the **Medallion Architecture (Bronze → Silver → Gold)**.

The pipeline ingests raw data, transforms it, and builds business-ready fact and dimension tables using Delta Lake.

It is fully orchestrated using **Databricks Workflows**.

---

## 🛠️ Tech Stack

`Databricks` | `Apache Spark` | `PySpark` | `Delta Lake` | `SQL` | `Medallion Architecture` | `Databricks Workflows` | `Git` | `GitHub`


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
📂 [View Project Repo](https://github.com/p0d04x5/databricks-medallion-retail-pipeline)

## 👩‍💻 Author

Pooja DM  
Aspiring Data Engineer 🚀

### Project - 2

### 🔄 Kafka Sales Pipeline (Real-time)
- Simulates live sales transactions using a **Kafka Producer**
- Streams data into **Apache Kafka**
- Ingests and orchestrates data into **PostgreSQL** using **Apache Airflow**
- Built with: `Python`, `Kafka`, `PostgreSQL`, `Airflow`, `Streamlit`

📂 [View Project Repo](https://github.com/p0d04x5/kafka-sales-pipeline)

---

## Project - 3

### 🏥 Health Data Pipeline (Batch)
- Collects and processes patient health metrics (heart rate, blood pressure, etc.)
- Cleans and loads data into a **SQLite** database
- Visualizes key health indicators using **Streamlit Dashboard**
- Built with: `Python`, `Pandas`, `SQLite`, `Streamlit`

📂 [View Project Repo](https://github.com/p0d04x5/health-data-pipeline) <!-- Update this link if needed -->

---

## 🛠️ Tech Stack

`Python` | `Kafka` | `Airflow` | `SQL` | `PostgreSQL` | `SQLite` | `Streamlit` | `Docker` | `Pandas`

---

## 🌱 Currently Learning
- Mastering `PySpark`, `Data Lakes`, `DWH`, and advanced `ETL orchestration`

---

📫 **Let’s connect:** [LinkedIn](www.linkedin.com/in/pooja-dm-9366061a6)  
🧠 Always learning. Always building.

