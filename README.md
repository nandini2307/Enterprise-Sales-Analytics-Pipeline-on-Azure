# Enterprise Sales Analytics Pipeline on Azure
End-to-end data engineering project using Azure Data Factory, Databricks, Synapse, and Power BI
This project demonstrates an end-to-end data engineering pipeline built on Microsoft Azure to enable enterprise sales analytics across regions and product categories.

## 🎯 Business Objective

Analyze sales performance by building a modern **data lakehouse architecture** supporting:

- Sales KPIs by Region, Product Category
- YoY Sales Trends
- Customer Insights
- Interactive dashboards for business users

## ⚙️ Architecture

![Architecture Diagram](architecture_diagram.png)

**Pipeline Flow**:

1. Ingest raw CSV / JSON data into **Azure Data Lake Storage Gen2**  
2. Use **Azure Data Factory** to orchestrate ETL workflows  
3. Transform & enrich data using **Azure Databricks (PySpark)** notebooks  
4. Load curated data into **Azure Synapse Analytics** (Dedicated SQL Pool)  
5. Build interactive dashboards in **Power BI**  

## 🗂️ Project Structure

azure-sales-analytics-pipeline/

├── README.md

├── architecture_diagram.png

├── datasets/                       # Raw sales, customers, products CSV

├── notebooks/                      # Databricks Notebooks (PySpark)

├── adf_pipelines/                  # Exported ADF pipeline JSON

├── synapse_sql_scripts/            # SQL DDL + Load scripts

├── powerbi_reports/                # PBIX files & screenshots

├── monitoring/                     # ADF monitoring setup, Synapse monitoring screenshots


|── LICENSE

