# Azure NYC Taxi Lakehouse Pipeline

End-to-end Azure data engineering project using Azure Data Factory, ADLS Gen2, Azure Databricks, Delta Lake, and Power BI for NYC taxi analytics.

## Architecture

Source/API → Azure Data Factory → ADLS Gen2 Raw Zone → Databricks Transformations → ADLS Gen2 Transformed Zone → Delta Lake Serving Layer → Power BI

## Project Goals

- Ingest NYC taxi data into ADLS Gen2
- Store raw and transformed data using Parquet
- Transform data using Azure Databricks
- Build Delta Lake serving tables
- Apply basic security, validation, and monitoring concepts
- Document the pipeline like a production-ready data platform project
