# Telecom ETL Pipeline

An end-to-end ETL pipeline built using **SSIS** and **SQL Server** to process telecom transaction data from multiple CSV files into a structured database.

The pipeline automates data ingestion, validation, cleansing, transformation, and loading while ensuring data quality and operational reliability. It supports dynamic processing of multiple files through folder iteration, enabling batch execution in a single run.

### Key Features

* Automated ingestion of telecom transaction CSV files
* Data validation and cleansing
* Lookup transformations and reference data integration
* Rejected-record handling for invalid data
* Auditing and logging for execution tracking
* Dynamic folder looping to process multiple files automatically
* File archiving to prevent duplicate ingestion

### Tech Stack

* **SSIS (SQL Server Integration Services)**
* **SQL Server**
