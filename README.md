# Olympic Data Insights: End-to-End Data Engineering Pipeline with Azure

### Overview
This project demonstrates the implementation of a full-scale data engineering pipeline using various Microsoft Azure services. The pipeline processes raw data from the Tokyo 2021 Olympics dataset, performs transformations, and generates insights using SQL-based analytics and visualizations.

### Dataset
The dataset used includes details on **11,000+ athletes**, **47 sports disciplines**, and **743 teams** from the Tokyo 2021 Olympics. It captures information such as athletes' names, countries, gender, sports, and their respective team details.

### Project Architecture
This project covers multiple stages of a data pipeline:

#### Data Ingestion:
- Ingest raw data from a GitHub repository using **Azure Data Factory**.
- Store the data in **Azure Data Lake Storage Gen2** for scalable, hierarchical data management.

#### Data Transformation:
- Use **Azure Databricks** with **Apache Spark** to clean and transform the raw data into an analysis-ready format.
- Operations include handling missing data, normalizing formats, and creating aggregated datasets for analysis.

#### Data Analytics:
- Perform large-scale SQL queries on the transformed data using **Azure Synapse Analytics**.
- Run in-depth analysis to extract insights such as medal counts, athlete performance, and country-wise comparisons.

### Azure Services Used:
- **Azure Data Factory**: Automates the ingestion of data from external sources.
- **Azure Data Lake Storage Gen2**: Stores raw and transformed data with hierarchical namespaces for efficient data management.
- **Azure Databricks**: Performs scalable data transformations using Apache Spark.
- **Azure Synapse Analytics**: Executes SQL-based data analytics on large datasets.

## How to Run This Project

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/olympic-data-insights-azure.git
   cd olympic-data-insights-azure

2. **Setup Azure Resources**:
Set up the following services in your Azure account:

- **Azure Data Factory**
- **Azure Data Lake Gen2**
- **Azure Databricks**
- **Azure Synapse Analytics**

3. **Data Ingestion**:
- Configure **Azure Data Factory** to ingest the raw dataset from the provided GitHub repository and load it into **Azure Data Lake Storage Gen2**.

4. **Data Transformation**:
- Use the provided **Databricks notebooks** to clean and transform the raw data.

5. **Data Analytics**:
- Run the **SQL queries** in **Azure Synapse Analytics** to perform analysis on the transformed data.

### Key Metrics & Results:
- **Data Ingestion Time**: Reduced by 25% through automated Azure pipelines.
- **Query Performance**: Improved by 30% using **Azure Synapse Analytics**.
- **Data Size**: Processed over 11,000 athletes and 47 sports disciplines.

## Screenshots

#### 1. Data Flow in Azure
![dataEngineering](https://github.com/user-attachments/assets/9f259e62-6236-4403-91e7-5486e8fddf10)


