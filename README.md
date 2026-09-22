# Azure ADF Spotify Data Engineering Project

This project demonstrates a data ingestion pipeline built using **Azure Data Factory (ADF), Azure SQL Database, and Azure Data Lake Storage Gen2 (ADLS Gen2)**.

## 🚀 Project Overview

The pipeline uses **Azure Data Factory** to automate the extraction of data from multiple SQL source tables and stores the raw data in the **Bronze layer** of ADLS Gen2 in Parquet format. The pipeline follows a **metadata-driven approach** to process multiple source tables using activities such as **Lookup, ForEach, Copy Data, and If Condition**. It implements **watermark-based incremental loading** to process only new or updated records and avoid unnecessary reprocessing of previously ingested data. Failure paths are configured to trigger **alert activities** when monitored pipeline activities fail, providing information about the pipeline execution and failure.

## 🏗️ Architecture

```text
Azure SQL Database
        ↓
Azure Data Factory
        ↓
ADLS Gen2 - Bronze Layer
        ↓
     Parquet

## 🛠️ Resources & Technologies Used

- **Microsoft Azure**
- **Azure Data Factory**
- **Azure SQL Database**
- **Azure Data Lake Storage Gen2**
- **SQL**
- **Parquet**
- **Git / GitHub**

## ✨ Key Features
- Metadata-driven data ingestion
- Incremental loading using watermarks
- Multiple SQL table processing
- Bronze layer storage in ADLS Gen2
- Parquet file format
- Pipeline monitoring and failure alerts

## 🔗 Connect with Me
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue)](http://www.linkedin.com/in/anush-mallya-3ba198286)

