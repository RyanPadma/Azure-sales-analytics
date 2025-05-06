# 🚀 Azure-Powered Sales Analytics: From Data Lake to Power BI

This is my first end-to-end data analytics project using Azure and Power BI. The goal was to build a complete data pipeline—from raw storage in Azure Data Lake all the way to interactive dashboards in Power BI.

---

## 📊 Project Overview

In this project, I designed a robust data pipeline and built interactive dashboards using tools from the Azure ecosystem. It was a hands-on learning journey where I integrated multiple Azure services to transform raw data into business insights.

---

## 🛠️ Tech Stack

- **Azure Data Factory** – ETL pipeline orchestration
- **Azure Data Lake** – Scalable cloud data storage
- **Azure Databricks (Apache Spark)** – Data transformation & big data processing
- **Azure Synapse Analytics** – SQL-based data warehouse for querying large datasets
- **Power BI** – Interactive dashboards for business insights

---

## 🔁 Workflow

```mermaid
flowchart LR
    A[Azure Data Lake] --> B[Azure Databricks - Spark Processing]
    B --> C[Azure Synapse Analytics]
    C --> D[Power BI Dashboard]
```

## 📌 Key Features
- Designed data pipelines with Azure Data Factory

- Transformed and cleaned data using Databricks & Apache Spark

- Queried processed datasets with Synapse Analytics

- Created live dashboards in Power BI

- Successfully configured access and integration across multiple Azure services

## 📂 Folder Structure
azure-sales-analytics/
├── databricks_notebooks/      # Spark code for data transformation
├── synapse_scripts/           # SQL scripts used in Synapse Analytics
├── powerbi/                   # Power BI dashboard file

##📷 Screenshots

- Dashboard End Result
![PowerBI Dashboard](https://github.com/user-attachments/assets/58e11ef1-aef8-47a0-ad8f-7d5e955583e9)

- Azure Data Factory
![Azure Data Factory](https://github.com/user-attachments/assets/b9186652-51ae-41db-8bc8-372424c4fa59)

- Azure Databricks
![Azure Databricks](https://github.com/user-attachments/assets/c4d7a235-9902-43c0-9e5f-42e6c68c6d00)

- Azure Synapse Analytics
![Azure Synapse Analytics](https://github.com/user-attachments/assets/86f50c5e-a737-4e88-9692-c62cd9caca7a)

## 🧠 Lessons Learned
- Navigating access control and permissions between Azure services

- Applying Spark efficiently within Databricks for big data workloads

- Leveraging Synapse for analytics over large datasets

- Connecting Power BI to Azure sources for real-time dashboarding

- Developing end-to-end thinking from raw data to business-ready insights
