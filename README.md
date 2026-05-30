# Data Warehouse and Analytics Project

Welcome to the  **Data Warehouse and Analytics Project**🚀
From creating a data warehouse to producing useful insights, this project exemplifies a complete data warehousing and analytics solution. In order to create a contemporary data warehouse that uses SQL Server to aggregate sales data and facilitate analytical reporting and well-informed decision-making, it outlines industry best practices in data engineering and analytics.

----------

## 🏗️ Data Architecture

The data architecture for this project follows Medallion Architecture  **Bronze**,  **Silver**, and  **Gold**  layers:  ![Data Architecture](https://github.com/DataWithBaraa/sql-data-warehouse-project/raw/main/docs/data_architecture.png)

1.  **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2.  **Silver Layer**: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3.  **Gold Layer**: Houses business-ready data modeled into a star schema required for reporting and analytics.

----------

## 📖 Project Overview

This project involves:

1.  **Data Architecture**: Designing a Modern Data Warehouse Using Medallion Architecture  **Bronze**,  **Silver**, and  **Gold**  layers.
2.  **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.
3.  **Data Modeling**: Developing fact and dimension tables optimized for analytical queries.
4.  **Analytics & Reporting**: Creating SQL-based reports and dashboards for actionable insights.

🎯 This repository is an excellent resource for professionals and students looking to showcase expertise in:

-   SQL Development
-   Data Architect
-   Data Engineering
-   ETL Pipeline Developer
-   Data Modeling
-   Data Analytics

----------

## 🛠️ Important Links & Tools:

Everything is for Free!

-   **[Datasets](link):**  Access to the project dataset (csv files).
-   **[SQL Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads):**  Lightweight server for hosting your SQL database.
-   **[SQL Server Management Studio (SSMS)](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16):**  GUI for managing and interacting with databases.
-   **[Git Repository](https://github.com/):**  Set up a GitHub account and repository to manage, version, and collaborate on your code efficiently.
-   **[DrawIO](https://www.drawio.com/):**  Design data architecture, models, flows, and diagrams.
-   **[Notion](https://www.notion.com/templates/sql-data-warehouse-project):**  Get the Project Template from Notion
-   **[Notion Project Steps](https://thankful-pangolin-2ca.notion.site/SQL-Data-Warehouse-Project-16ed041640ef80489667cfe2f380b269?pvs=4):**  Access to All Project Phases and Tasks.

----------

## 🚀 Project Requirements

### Building the Data Warehouse (Data Engineering)
#### Objective

Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

#### Specifications

-   **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.
-   **Data Quality**: Cleanse and resolve data quality issues prior to analysis.
-   **Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries.
-   **Scope**: Focus on the latest dataset only; historization of data is not required.
-   **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.

----------

## BI: Analytics & Reporting (Data Analysis)

#### Objective

Develop SQL-based analytics to deliver detailed insights into:

-   **Customer Behavior**
-   **Product Performance**
-   **Sales Trends**

These insights empower stakeholders with key business metrics, enabling strategic decision-making.

For more details, refer to  [docs/requirements.md](link).

----------

## 📂 Repository Structure
```
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── etl.drawio                      # Draw.io file shows all different techniquies and methods of ETL
│   ├── data_architecture.drawio        # Draw.io file shows the project's architecture
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   ├── data_flow.drawio                # Draw.io file for the data flow diagram
│   ├── data_models.drawio              # Draw.io file for data models (star schema)
│   ├── naming-conventions.md           # Consistent naming guidelines for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality files
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository
├── .gitignore                          # Files and directories to be ignored by Git
└── requirements.txt                    # Dependencies and requirements for the project

```

----------

## 🛡️ License

This project is licensed under the  [MIT License](link). You are free to use, modify, and share this project with proper attribution.

----------

## 🌟 About Me

Hello there! My name is G Nemi Chakrawarty, and I'm passionate about data engineering. I come from a non-IT background in finance. I am on a journey to expand my knowledge of AI/DATA ENGINEERING and make dealing with data more interesting and engaging!

Let's stay in touch! Feel free to connect with me on the following platforms:

 [![LinkedIn](https://camo.githubusercontent.com/835f91c273c180e842aa0b2fb0d5ccc52def20089589abbcefceb28317c583f8/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c696e6b6564496e2d3030373742353f7374796c653d666f722d7468652d6261646765266c6f676f3d6c696e6b6564696e266c6f676f436f6c6f723d7768697465)](https://www.linkedin.com/in/gnemichakrawarty/)  
