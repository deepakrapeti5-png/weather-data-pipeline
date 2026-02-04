# Weather Data Pipeline

This project builds an end-to-end data pipeline that ingests weather forecast data
from the Open-Meteo API and loads it into Google BigQuery using Airflow.

## Tech Stack
- Google Cloud Platform (GCS, BigQuery)
- Apache Airflow (Dockerized)
- Terraform (Infrastructure as Code)

## Architecture
- Airflow orchestrates the pipeline
- Raw JSON data is stored in GCS
- Parsed hourly data is loaded into BigQuery
