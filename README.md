# Databricks Lakehouse with AI-Driven Data Quality

## Project Overview
This project demonstrates an end-to-end Databricks Lakehouse implementation using the Medallion Architecture (Bronze, Silver, Gold) with an AI-based data quality layer to automatically detect anomalies in business metrics.
The solution ingests raw sales data, transforms it into analytics-ready KPIs, and applies machine learning–based anomaly detection to improve trust in reporting.

## Business Problem
Many organizations face:
  
    - Silent data issues in reports    
    - Unexpected revenue drops or spikes    
    - Heavy dependence on manual, rule-based data quality checks    
    - Traditional checks fail to detect business-level anomalies.

 This project solves the problem by applying AI-driven anomaly detection on Gold-level KPIs.

 ## Architecture Overview
 ### High level flow
  Source CSV  
   ↓
  Bronze Layer (Raw Ingestion)  
   ↓
  Silver Layer (Clean & Standardized)  
   ↓
  Gold Layer (Business KPIs)  
   ↓
  AI Data Quality (Anomaly Detection)  

  
