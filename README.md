# Databricks Bootcamp 2026 - Bike Lakehouse Project

This repository contains the end-to-end data engineering pipeline for a bike retail lakehouse implemented on **Databricks**.

## Project Architecture (Medallion)
The project follows the standard Medallion architecture to ensure data quality and reliability:

*   **Bronze:** Raw data ingestion from CSV files into Delta tables.
*   **Silver:** Data cleaning, transformation, and schema enforcement.
*   **Gold:** Final business-level aggregates and dimension tables for reporting.

## Tech Stack
*   **Databricks** (Compute & Workspace)
*   **PySpark** (Data Processing)
*   **Delta Lake** (Storage Layer)
*   **GitHub** (Version Control)
