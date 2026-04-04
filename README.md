# eCom-customer-behavior-analytics-project

eCommerce customer behavior analytics: batch ingestion with Airflow on GCP, Spark processing, dbt transformations, and Looker Studio dashboards.

## Overview
End-to-end batch data pipeline that ingests 285M+ eCommerce user behavior events (views, cart additions, purchases), processes them with Spark, loads into BigQuery, transforms using dbt, and visualizes customer insights in Looker Studio.

## Architecture
![Architecture Diagram](docs/architecture.png)

*Detailed documentation coming soon.*

## Tech Stack
- **Orchestration:** Apache Airflow (GCP Cloud Composer)
- **Compute:** Apache Spark (PySpark)
- **Data Lake:** Google Cloud Storage
- **Data Warehouse:** BigQuery
- **Transformations:** dbt Core (Dockerized)
- **Dashboard:** Looker Studio
- **Containerization:** Docker

## Dataset
[eCommerce Behavior Data from Multi Category Store](https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store) — 285M+ user events from a large multi-category online store (Oct 2019 – Apr 2020).

## Setup & Reproduction
*Instructions will be added as the project develops.*
