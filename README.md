# Agricultural Sensor Data Pipeline

## Project Use Case

**Objective:**  
Build a production-grade data pipeline to ingest, process, validate, enrich, and store agricultural sensor data for downstream analytics.

**Context:**  
- The agricultural monitoring system collects sensor data across farmlands.  
- Sensors track **soil moisture, temperature, humidity, light intensity, and battery levels**.  
- Raw data is stored in **Parquet files**, partitioned by **date** and **sensor type**.

**Responsibilities / Tasks:**  
1. **Ingestion:** Efficiently load raw Parquet data from multiple sources.  
2. **Transformation:** Standardize, clean, and enrich sensor readings.  
3. **Validation:** Ensure data quality, detect anomalies, and handle missing or corrupt data.  
4. **Storage:** Deliver clean, query-optimized datasets for analytics and reporting.

**Outcome:**  
Enable accurate, timely insights into farmland conditions, supporting decision-making and downstream analytics workflows.
