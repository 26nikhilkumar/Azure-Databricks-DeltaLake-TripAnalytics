# Azure-Databricks-DeltaLake-TripAnalytics
End-to-end data engineering project utilizing Azure Data Factory, Databricks, and Delta Lake. Focuses on analyzing trip and rating data following the Medallion Architecture approach. Includes data ingestion, transformation, pipeline scheduling, and the use of Logic Apps for resiliency.

This project aims to implement Analytics/Insights on the trip transaction and ride-based
source data from SQL Server, utilizing a combination of Azure Data Factory (ADF),
Azure Blob Storage (ADLS Gen2), and Azure Databricks, in accordance with a
Medallion Architecture approach. The project entails data ingestion into a Bronze Zone,
data transformation through Azure Databricks, and data loading into Delta tables for the
Gold Zone. Moreover, we plan to create a pipeline and schedule it using Azure Data
Factory and leverage Logic Apps for pipeline resiliency in order to trigger emails.
Tech Stack
➔
Language: Python, SQL, Spark
➔
Package: PySpark
➔
Services: Azure Data Factory (ADF), Azure Blob Storage (ADLS Gen2), and Azure
Databricks, Logic Apps, Azure SQL Database

![github project drawio](https://github.com/26nikhilkumar/Azure-Databricks-DeltaLake-TripAnalytics/assets/59439090/89d83086-0cbb-4f63-8542-aba1d5ab1655)
