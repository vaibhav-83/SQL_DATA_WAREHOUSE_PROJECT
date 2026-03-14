# 📊 Data Warehouse Project

---

# 📖 Project Overview

This project involves:

* **Data Architecture:** Designing a Modern Data Warehouse using **Medallion Architecture** with **Bronze, Silver, and Gold layers**.
* **ETL Pipelines:** Extracting, transforming, and loading data from source systems into the warehouse.
* **Data Modeling:** Developing **fact and dimension tables** optimized for analytical queries.
* **Analytics & Reporting:** Creating **SQL-based reports and dashboards** for actionable insights.

# 🚀 Project Requirements

## 🏗️ Building the Data Warehouse (Data Engineering)

### 🎯 Objective

Develop a **modern data warehouse using SQL Server** to consolidate sales data and enable **analytical reporting and informed decision-making**.

### 📌 Specifications

* **📥 Data Sources:**
  Import data from **two source systems (ERP and CRM)** provided as **CSV files**.

* **🧹 Data Quality:**
  Cleanse and resolve **data quality issues** prior to analysis.

* **🔗 Integration:**
  Combine both sources into a **single, user-friendly data model** designed for **analytical queries**.

* **📊 Scope:**
  Focus on the **latest dataset only**. Historization of data is **not required**.

* **📚 Documentation:**
  Provide clear documentation of the **data model** to support both **business stakeholders and analytics teams**.

---

# 📊 BI: Analytics & Reporting (Data Analysis)

### 🎯 Objective

Develop **SQL-based analytics** to deliver detailed insights into:

* 👥 **Customer Behavior**
* 📦 **Product Performance**
* 📈 **Sales Trends**

These insights empower stakeholders with **key business metrics**, enabling **strategic decision-making**.

For more details, refer to:

```
docs/requirements.md
```

---

# 📂 Repository Structure

```
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── etl.drawio                      # Draw.io file showing different ETL techniques and methods
│   ├── data_architecture.drawio        # Draw.io file showing the project architecture
│   ├── data_catalog.md                 # Catalog of datasets with field descriptions and metadata
│   ├── data_flow.drawio                # Draw.io file for the data flow diagram
│   ├── data_models.drawio              # Draw.io file for data models (Star Schema)
│   ├── naming-conventions.md           # Naming guidelines for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality checks
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository
├── .gitignore                          # Files and directories ignored by Git
└── requirements.txt                    # Dependencies and project requirements
```
