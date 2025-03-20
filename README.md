# Data Processing System

## Overview
The **Data Processing System** is designed to analyze **TriMet GPS tracking data**, commonly referred to as *breadcrumb data*, along with *Stop Events API* data to enhance public transportation in **Portland**.  

### Key Features:
- **Data Ingestion & Processing**:  
  - Raw data is ingested into **data pipelines** and undergoes **validation, transformation, and enrichment** to ensure data accuracy and consistency.  
- **Streaming & Pub/Sub Integration**:  
  - Processed data is published to **Google Cloud Pub/Sub** for real-time data distribution and further analysis.  
- **Automation & Reliability**:  
  - **Python scripts** deployed on **Virtual Machines (VMs)** execute at scheduled intervals using **cron jobs** for automated data retrieval.  
  - The **trimer-receiver.service** is configured to automatically initiate on VM startup and restart upon failure, ensuring system resilience.  

## Collaboration  
This project was developed in collaboration with:  
- **Vipul**  
- **Raghuram**  
- **Siddhanth**  

---
