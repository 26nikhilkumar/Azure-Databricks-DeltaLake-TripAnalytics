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

## Key Takeaways 
● Understanding the Trip transaction dataset
● Understanding the Features of Delta Lake
● Understanding the Evolution of Delta Lake from Data Lake
● Understanding the Medallion Architecture
● Overview of Azure Data Factory
● Creating Dataflow in Azure Data Factory
● Creating Pipelines in Azure Data Factory
● Creating Datasets in Azure Data Factory
● Transforming data using PySpark in Databricks notebooks
● Scheduling the Pipeline in Azure Data Factory
● Creating Logic Apps to trigger emails for pipeline resiliency
● Monitoring Sessions in Azure Data Factory
