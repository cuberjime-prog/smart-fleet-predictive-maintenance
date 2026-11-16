# Smart Fleet & Predictive Maintenance Platform

## Project Overview

Smart Fleet & Predictive Maintenance is an end-to-end Data Engineering and Machine Learning project built using Databricks.

The project aims to develop an intelligent fleet management platform that centralizes vehicle, driver, trip, telemetry, weather, and maintenance information.

Using a Lakehouse architecture and a Medallion data processing approach, the solution transforms raw operational data into reliable analytical datasets and predictive insights.

## Business Problem

Transportation companies need better visibility into fleet performance and vehicle conditions. Traditional maintenance processes are often reactive, resulting in unexpected failures, operational downtime, and increased repair costs.

This project addresses these challenges through centralized data processing, predictive maintenance, and analytics.

## Technology Stack

- Databricks Free Edition
- Apache Spark / PySpark
- Python
- SQL
- Delta Lake
- Unity Catalog
- Lakeflow
- MLflow
- Scikit-learn
- Databricks AI/BI Dashboards
- Databricks Genie
- GitHub

## Architecture

The project follows the Medallion Architecture:

- **Landing:** Initial data ingestion.
- **Bronze:** Raw data storage.
- **Silver:** Data cleaning and validation.
- **Gold:** Business-ready analytical datasets.
- **ML:** Machine learning features and predictions.

## Data Sources

- Vehicle information
- Driver information
- Trip records
- Vehicle telemetry
- Maintenance history
- Weather information

## Project Objectives

1. Build an end-to-end data ingestion pipeline.
2. Implement a Medallion Architecture.
3. Process vehicle telemetry data.
4. Implement data quality checks.
5. Develop predictive maintenance models.
6. Track experiments using MLflow.
7. Build analytical dashboards.
8. Integrate natural language analytics using Databricks Genie.
9. Develop a fleet management application.

## Project Status

Currently in Phase 1: Project Setup & Architecture.

More documentation and implementation details will be added as the project progresses.
