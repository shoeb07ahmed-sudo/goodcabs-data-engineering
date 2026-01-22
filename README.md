# goodcabs-data-engineering
End-to-end Data Engineering project using Databricks Lakehouse and AWS S3


# 🚕 GoodCabs – End-to-End Data Engineering Project

## 📌 Project Overview
GoodCabs is a cab service provider.  
This project demonstrates an **end-to-end data engineering pipeline** starting from an application database to an analytics-ready lakehouse using **AWS S3 and Databricks Lakehouse architecture**.

The goal is to design a **scalable, reliable, and streaming-capable data platform** using modern data engineering practices.

---

## 🏗️ Architecture
Application → Relational Database → AWS S3 → Databricks Lakehouse  
(Bronze → Silver → Gold)

## 🏗️ Architecture Diagram
<p align="center">
  <img src="3.other_files/architecture.png" alt="GoodCabs Data Engineering Architecture" width="850">
</p>



Key technologies:
- Relational Database
- AWS S3
- Databricks
- Lakeflow (Declarative Spark Pipelines)
- Delta Lake

---

## 🔄 Data Flow
1. Application data stored in a relational database
2. Data extracted and loaded into AWS S3
3. S3 data ingested into Databricks
4. Implemented **Medallion Architecture**
   - Bronze: Raw ingestion
   - Silver: Cleaned & standardized data
   - Gold: Business-ready analytics tables

---

## ⚙️ Key Implementations
- Lakeflow **Declarative Pipelines**
- Streaming tables for **Fact tables**
- Materialized Views for **Dimension tables**
- Auto CDC (Change Data Capture)
- Append mode for streaming ingestion

---

## 📊 Data Modeling
- Fact tables built using streaming pipelines
- Dimension tables built using materialized views
- Optimized for analytics and reporting

---

## 🧠 Learnings
- Difference between **Declarative vs Imperative programming**
- Building reliable pipelines using **Spark Declarative Pipelines**
- Implementing **Auto CDC**
- Designing Lakehouse architecture for real-time analytics
- Hands-on experience with Databricks streaming tables

---

## 🛠️ Tech Stack
- SQL
- Apache Spark
- Databricks
- AWS S3
- Delta Lake





