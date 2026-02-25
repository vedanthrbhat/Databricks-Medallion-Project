# 🥉🥈🥇 Databricks Medallion Architecture – Ecommerce Learning Project

[Live Dashboard Link --> (https://dbc-ba8c955b-e181.cloud.databricks.com/embed/dashboardsv3/01f10dcd87801f8890226a567dd402f9?o=2639517554661251))")]

## 📖 About the Project

This project is a **learning-focused implementation of the Medallion Architecture** using Databricks and Delta Lake.  
It is **not an end-to-end production pipeline**, but a **hands-on reference** designed to understand:

- How data flows across **Bronze, Silver, and Gold layers**
- How Databricks notebooks are used to build data pipelines
- How Delta Lake enables reliable, layered data processing

The primary goal is to **learn and visualize how a data pipeline works** inside a modern Lakehouse architecture.

---

## 🧰 Tech Stack

This project uses a **minimal yet industry-relevant tech stack** to clearly demonstrate Medallion Architecture concepts.

### 🔹 Core Platform
- **Databricks** – Unified analytics platform for building Spark-based pipelines
- **Apache Spark** – Distributed processing engine used for transformations

### 🔹 Storage & Table Format
- **Delta Lake** – ACID-compliant tables for Bronze, Silver, and Gold layers
- **Parquet** – Columnar storage format used internally by Delta

### 🔹 Programming & Querying
- **PySpark** – Data ingestion and transformation logic
- **Spark SQL** – Layer-to-layer transformations and aggregations

### 🔹 Architecture Pattern
- **Medallion Architecture (Bronze → Silver → Gold)**
- Layered data refinement approach

---

## 🏗️ Medallion Architecture Overview

```text
Raw Data
   │
   ▼
Bronze Layer
(Raw / Ingested Data)
   │
   ▼
Silver Layer
(Cleaned & Standardized Data)
   │
   ▼
Gold Layer
(Structured & Aggregated Data)
```
---
## Dashboard Screenshot
<img width="1917" height="861" alt="Screenshot 2026-02-20 190814" src="https://github.com/user-attachments/assets/a718a64d-4335-497e-a1c1-5e5ba3a8ecc0" />
