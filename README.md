# Databricks + Power BI Project

This project aims to build an end-to-end data pipeline using Databricks and integrate it with Power BI for interactive reporting and insights.

## Folder Structure

- `01_raw_data/` - raw data files (Excel, CSV)
- `02_etl/` - notebooks for data ingestion and transformation
- `03_eda` - notebooks and SQL for exploration and BI support
- `04_outputs/` - generated charts, exports, and temporary outputs
- `05_docs/` - documentation and metadata

## Tech Stack

- Databricks (Delta Lake, Spark SQL, PySpark)
- Power BI
- Python + Pandas (for initial loading of Excel files)

## How to Run

1. Upload Excel files to `01_raw_data/`
2. Execute `02_etl/01_load_raw_data.py` to create Delta tables
3. Use `03_analysis/` notebooks for exploration or Power BI queries

