# X (formerly Twitter) -Data-Pipeline-using-Airflow
X (Formerly Twitter) Data Pipeline using Apache Airflow
📌 Project Overview

This project implements an end-to-end data pipeline to extract, process, and analyze data from X (formerly Twitter) using Apache Airflow for workflow orchestration.

The pipeline automates data ingestion, transformation, and storage processes while ensuring reliability, scalability, and monitoring capabilities.

The objective is to build a production-ready data engineering workflow that can collect social media data and make it available for analytics and reporting.

🎯 Project Objectives

Automate data extraction from X API

Orchestrate workflows using Apache Airflow DAGs

Clean and transform raw JSON data

Store processed data in a data warehouse / data lake

Enable downstream analytics and visualization

Ensure scalability and fault tolerance

🏗️ Architecture Overview

1️⃣ Data Extraction

Fetch tweets using X API (based on keywords, hashtags, or user handles)

2️⃣ Workflow Orchestration

Apache Airflow schedules and monitors tasks using DAGs

3️⃣ Data Processing

Clean, normalize, and transform tweet data

Extract important fields (tweet text, user info, retweets, likes, timestamps)

4️⃣ Data Storage

Store raw data in object storage (e.g., S3 / local storage)

Store processed data in PostgreSQL / Data Warehouse

5️⃣ Analytics & Reporting

Connect BI tools (Power BI / Tableau) for visualization
