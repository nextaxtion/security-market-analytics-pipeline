# stock-market-analytics-pipeline

Stock market analytics: batch ingestion with Airflow on GCP, Spark processing, dbt transformations, and Looker Studio dashboards.

## Overview
End-to-end batch data pipeline that ingests daily stock price data for 8000+ NASDAQ tickers, processes them with Spark, loads into BigQuery, transforms using dbt, and visualizes market insights in Looker Studio.

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
[Stock Market Dataset](https://www.kaggle.com/datasets/jacksoncrow/stock-market-dataset) — Historical daily prices for 8000+ NASDAQ-traded stocks and ETFs.

## Setup & Reproduction
*Instructions will be added as the project develops.*
