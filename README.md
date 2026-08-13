# Hi, I'm Ahmad

I'm a **Software & Data Engineer** based in Indonesia with 4+ years of experience building data-intensive systems across the full stack — from backend APIs to ETL pipelines to data warehouses.

My background spans **core banking** and **multi-finance systems**, where data accuracy and pipeline reliability aren't optional. I'm now actively building toward the modern cloud data stack.

---

## 🛠️ What I Work With

**Data Engineering**
- ETL/ELT: SSIS · Pentaho · Apache Airflow · Azure Data Factory
- Processing: PySpark · Apache Spark · DuckDB
- Storage: Oracle · PostgreSQL · MS SQL · MinIO (S3-compatible) · ADLS Gen2
- Formats: Parquet · Delta Lake · JSONL · CSV
- Patterns: Medallion Architecture · Incremental Loading · Watermark-based CDC

**Backend Engineering**
- Java Spring Boot · REST API Design · Apache Kafka
- PHP CodeIgniter · Python · FastAPI

**Cloud & Infra**
- Azure (ADF · ADLS Gen2 · Databricks — hands-on learning)
- Docker · Docker Compose · WSL

**Tooling**
- Git · GitHub · GitLab · Bitbucket
- Jira · Confluence · Agile & Waterfall SDLC

---

## 📂 Featured Projects

### 🗞️ [Indonesian News Data Pipeline](https://github.com/kingofpajamas/data-pipeline-stuff)
End-to-end data pipeline scraping Indonesian news sites (Detik, Kompas, Tempo) using **Apache Airflow + PySpark + MinIO**.
Raw articles land as JSONL in a local S3-compatible data lake, get transformed to partitioned Parquet via Spark, and are served through a **FastAPI + DuckDB** query layer.

`Airflow` `PySpark` `MinIO` `FastAPI` `DuckDB` `Docker` `Parquet`

---

### 💱 [Finance Data Ingestion Service](https://github.com/kingofpajamas/finance-data-ingestion)
Spring Boot service that ingests IDR exchange rate data from external financial sources on startup and on a configurable schedule. Results are served via REST API and published to **Apache Kafka** for downstream consumption.

`Java` `Spring Boot` `Apache Kafka` `REST API` `Docker`

---

## 🏦 Production Experience Highlights

**Core Banking ETL — SSIS + Oracle**
Built and maintained production ETL pipelines for a core banking system handling customer data, payments, repossessions, disbursements, and regulatory reports. Managed live SSIS jobs as IT Production Support.

**Multi-Finance Data Warehouse — Oracle**
Designed end-to-end data flows across staging, transaction, and reporting layers. Integrated with external bank/vendor APIs for transaction processing and feedback ingestion. Generated financial transaction reports via scheduled SSIS jobs.

**Data Migration — Oracle → MS SQL**
Built schema migration pipelines migrating customer and contract data between Oracle and external vendor MS SQL systems using SSIS.

---

## 📈 Currently Learning
- Azure Synapse Analytics · Microsoft Fabric · Power BI
- Delta Lake · Advanced PySpark patterns
- dbt for analytics engineering

---

## 📫 Let's Connect
- 💼 Open to Data Engineer opportunities
- 📍 Based in Indonesia
