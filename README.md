# 7.Bee_Haven
Case Study – Bee Haven Data Lakehouse (Completed)

Objective: Revived a multi-year bee health monitoring project by integrating legacy hive sensor data with live streams into a unified Azure-based data lakehouse.
Project Goal: Built a scalable, end-to-end pipeline in Azure Data Lake Gen2 + Data Factory + Synapse that merged historical CSV logs, real-time JSON telemetry, and external weather APIs—delivering clean, queryable insights for researchers at the University of Honighausen.
Key Achievements:
Designed a medallion architecture (Bronze → Silver → Gold) to handle raw, cleaned, and analytical layers.
Created dynamic ADF pipelines using Get Metadata + ForEach to auto-ingest hundreds of legacy files regardless of naming or schema drift.
Transformed semi-structured JSON hive events and enriched with OpenWeather API data using Synapse Spark notebooks.
Enforced RBAC/IAM security across storage, factory, and analytics workspaces—zero open buckets, full audit trail.

Focus: Real-world ETL/ELT orchestration in the cloud—because bees don’t wait for bad data engineering.

Steps Completed:

🏗 Created Data Lake with Hierarchical Namespaces
🏗 Built First Data Factory Pipeline
🏗 Deployed Fully Dynamic Ingestion Pipeline
🏗 Cleaned and Standardized Hive Sensor Data
🏗 Joined Hive + Weather on Timestamp/Location
