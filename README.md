# Azure-Databricks-DeltaLake-TripAnalytics
End-to-end data engineering project utilizing Azure Data Factory, Databricks, and Delta Lake. Focuses on analyzing trip and rating data following the Medallion Architecture approach. Includes data ingestion, transformation, pipeline scheduling, and the use of Logic Apps for resiliency.

# Azure-Databricks-DeltaLake-TripAnalytics
This project implements Analytics/Insights on trip transaction and ride-based data from SQL Server, leveraging Azure Data Factory (ADF), Azure Blob Storage (ADLS Gen2), and Azure Databricks. It follows the Medallion Architecture approach, which includes data ingestion into a Bronze Zone, data transformation via Azure Databricks, and data loading into Delta tables for the Gold Zone. Additionally, it involves pipeline creation and scheduling using Azure Data Factory and Logic Apps for pipeline resiliency to trigger emails.

## Tech Stack
- **Languages:** Python, SQL, Spark
- **Package:** PySpark
- **Services:** Azure Data Factory (ADF), Azure Blob Storage (ADLS Gen2), Azure Databricks, Logic Apps, Azure SQL Database

## Architecture Diagram
![github project drawio](https://github.com/26nikhilkumar/Azure-Databricks-DeltaLake-TripAnalytics/assets/59439090/89d83086-0cbb-4f63-8542-aba1d5ab1655)

# Project Structure

### Folders:
1. **Bronze Zone:** This folder contains the 'Delta_Lake_validation' script related to the initial stage of data processing where raw data is ingested.
2. **Silver Zone:** This folder is designed for scripts that transform the raw data from the Bronze Zone into a more analyst-friendly format. It includes six different scripts.
3. **Gold Zone:** This folder holds scripts for the final stage of data processing, where transformed data from the Silver Zone is further refined and made ready for analytics. It includes the following file:
    - **Final_Reports:** This script generates final reports with customer and driver rankings based on different measures such as total distance, total fare, and the number of trips.

### Files:
1. **Config:** This file contains the configuration settings for the Azure Blob Storage.
2. **PySpark_upload_data_to_DB_Script:** This file contains the PySpark script for loading the CSV data from Azure Blob Storage into an Azure SQL Database.

## Key Takeaways 
- Understanding the Trip transaction dataset
- Understanding the Features of Delta Lake
- Understanding the Evolution of Delta Lake from Data Lake
- Understanding the Medallion Architecture
- Overview of Azure Data Factory
- Creating Dataflow in Azure Data Factory
- Creating Pipelines in Azure Data Factory
- Creating Datasets in Azure Data Factory
- Transforming data using PySpark in Databricks notebooks
- Scheduling the Pipeline in Azure Data Factory
- Creating Logic Apps to trigger emails for pipeline resiliency
- Monitoring Sessions in Azure Data Factory
