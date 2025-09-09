# etl-streaming-data-procesing-pemex-production

This project demonstrates an **ETL pipeline** using publicly available production data from **Pemex**.  
The goal is to simulate a **streaming ETL process** following the **Medallion Architecture** (Bronze, Silver, Gold layers).

## Project Structure

Data-prod/ # Raw production data from Pemex
ETL process/
├── Bronze.ipynb # Ingestion & raw layer
├── Silver.ipynb # Cleansing & standardization
└── Rank_Pozos.ipynb # Gold layer: ranking of wells

## Purpose

This code serves as a **practice project** to explore what the **Databricks Free Edition** can do.  
It highlights how Databricks can be used effectively for **data engineers** and **ML engineers** to build scalable ETL processes.  

## Key Features

- Simulated **streaming ingestion** of Pemex production data.  
- Implementation of the **Medallion Architecture**.  
- Example of a **Gold table** with ranked wells (`Rank_Pozos`).  
- Designed for **learning and practice** with Databricks notebooks.  

---

💡 *Databricks is a powerful tool for both aspiring and experienced data engineers / ML engineers to practice real-world pipelines.*
