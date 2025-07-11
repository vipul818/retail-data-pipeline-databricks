# 🛒 Retail Data Engineering Pipeline on Databricks

## 🚀 Overview
This project builds a complete, end-to-end data pipeline using **Databricks**, **PySpark**, and **Delta Lake**. It processes raw retail sales data, cleans and enriches it, stores it in Delta format, and enables fast analytics and visualization — all orchestrated through **Databricks Jobs**.

---

## 📦 Dataset
- Source: [Kaggle Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

---

## 🧰 Tech Stack
- 🔹 Databricks
- 🔹 PySpark
- 🔹 Delta Lake
- 🔹 Databricks Jobs (orchestration)
- 🔹 GitHub (version control)
- 🔹 Built-in SQL Visualizations

---

## 🔄 Pipeline Stages

| Stage | Description |
|-------|-------------|
| 1️⃣ Ingestion | Load CSV into Spark DataFrame |
| 2️⃣ Transformation | Clean, cast, and enrich data |
| 3️⃣ Delta Storage | Write data in Delta format and register temp views |
| 4️⃣ Optimization | OPTIMIZE table layout|
| 5️⃣ Visualization | Run SQL queries and pin charts to dashboards |
| 6️⃣ Orchestration | Run all stages via Databricks Job scheduler |

---

## 🛠️ Job Orchestration

This pipeline is orchestrated using **Databricks Jobs**.

- 📋 [Job JSON config](https://github.com/vipul818/retail-data-pipeline-databricks/blob/main/Jobs/retail-data-pipeline-job.json)
- 📸 DAG:

![Job Orchestration DAG](https://github.com/vipul818/retail-data-pipeline-databricks/blob/main/dashboard_screenshots/Screenshot%202025-07-12%20002458.png)

---

## 📊 Visualizations

Example insights generated from the Delta table:

### 🔹 Sales Trend by Month
![Sales Trend](https://github.com/vipul818/retail-data-pipeline-databricks/blob/main/dashboard_screenshots/visualization%20(1).png)

### 🔹 Order Trend by Month
![Order Trend by Month](https://github.com/vipul818/retail-data-pipeline-databricks/blob/main/dashboard_screenshots/visualization%20(2).png)

### 🔹 Sales Trend by Category
![Sales Trend by Category](https://github.com/vipul818/retail-data-pipeline-databricks/blob/main/dashboard_screenshots/visualization.png)

---

## 🧠 Key Features

- ✅ End-to-end ETL pipeline using PySpark & Delta Lake
- ✅ OPTIMIZE for performance tuning
- ✅ SQL-based reporting & dashboard visualizations
- ✅ Git-based version control integrated in Databricks
- ✅ Automated orchestration using Databricks Jobs

---

## 👨‍💻 Author

**Vipul Anand**


