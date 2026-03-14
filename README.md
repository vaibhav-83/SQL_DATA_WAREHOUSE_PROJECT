📊 Data Warehouse Project
📖 Project Overview

This project demonstrates how to design and build a Modern Data Warehouse using SQL Server and Medallion Architecture.

The project covers the complete data lifecycle from raw data ingestion to analytical reporting.

🔹 Key Components

🧱 Data Architecture
Designing a Modern Data Warehouse using Medallion Architecture:

🟤 Bronze Layer – Raw data ingestion

⚪ Silver Layer – Cleaned and transformed data

🟡 Gold Layer – Analytical data models

⚙️ ETL Pipelines
Extracting, transforming, and loading data from multiple source systems into the warehouse.

🧩 Data Modeling
Creating Fact and Dimension tables optimized for analytical queries using Star Schema.

📈 Analytics & Reporting
Developing SQL-based reports and dashboards to generate actionable insights.

🎯 Who This Project Is For

This repository is an excellent resource for professionals and students who want to showcase skills in:

💻 SQL Development

🏗️ Data Architecture

⚙️ Data Engineering

🔄 ETL Pipeline Development

📊 Data Modeling

📈 Data Analytics

🛠️ Tools & Important Resources

Everything used in this project is free.

Tool	Purpose
📁 Datasets	Project datasets in CSV format
🗄️ SQL Server Express	Lightweight SQL Server database
🧑‍💻 SQL Server Management Studio (SSMS)	GUI for database development
🌐 GitHub	Version control and collaboration
🧩 DrawIO	Design architecture diagrams and data models
📝 Notion	Project documentation and task management
🚀 Project Requirements
🏗️ Building the Data Warehouse (Data Engineering)
🎯 Objective

Develop a modern data warehouse using SQL Server to consolidate sales data and enable analytical reporting and decision-making.

📌 Specifications

📥 Data Sources

Import data from two source systems

ERP System

CRM System

Data provided as CSV files

🧹 Data Quality

Clean and resolve data quality issues

Handle missing values, duplicates, and inconsistencies.

🔗 Integration

Combine ERP and CRM data into a single unified data model

📊 Scope

Focus only on the latest dataset

Historical data tracking not required

📚 Documentation

Provide documentation for:

Data models

Table descriptions

Business definitions

📊 BI: Analytics & Reporting (Data Analysis)
🎯 Objective

Develop SQL-based analytics to provide insights into:

👥 Customer Behavior

📦 Product Performance

📈 Sales Trends

These insights help stakeholders make data-driven business decisions.

📄 For detailed requirements see:
docs/requirements.md

📂 Repository Structure
data-warehouse-project/
│
├── 📁 datasets/                        
│   └── Raw datasets used in the project (ERP & CRM)
│
├── 📁 docs/                            
│   ├── etl.drawio                      
│   ├── data_architecture.drawio        
│   ├── data_catalog.md                 
│   ├── data_flow.drawio                
│   ├── data_models.drawio              
│   ├── naming-conventions.md           
│
├── 📁 scripts/                         
│   ├── bronze/                         
│   ├── silver/                         
│   ├── gold/                           
│
├── 📁 tests/                           
│   └── Data validation and testing scripts
│
├── 📄 README.md                        
├── 📄 LICENSE                          
├── 📄 .gitignore                       
└── 📄 requirements.txt                 
