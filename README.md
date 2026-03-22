# security-market-analytics-pipeline

S&P 500 securities market analytics: batch ingestion with Airflow on GCP, dbt transformations, and Looker Studio dashboards.

## Overview
End-to-end batch data pipeline that ingests S&P 500 stock market data, loads it into BigQuery, transforms it using dbt, and visualizes insights in Looker Studio.

## Architecture
![Architecture Diagram](docs/architecture.png)

*Detailed documentation coming soon.*

## Tech Stack
- **Orchestration:** Apache Airflow (GCP Cloud Composer)
- **Data Lake:** Google Cloud Storage
- **Data Warehouse:** BigQuery
- **Transformations:** dbt Core (Dockerized)
- **Dashboard:** Looker Studio
- **Containerization:** Docker

## Dataset
[S&P 500 Stocks (daily updated)](https://www.kaggle.com/datasets/andrewmvd/sp-500-stocks) from Kaggle

## Setup & Reproduction
*Instructions will be added as the project develops.*
