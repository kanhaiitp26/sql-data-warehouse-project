# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀

This project demonstrates a comprehensive **data warehousing and analytics solution**, from building a data warehouse to generating actionable business insights. Designed as a portfolio project, it highlights industry best practices in **data engineering, data modeling, ETL, and analytics**.

---

## 🏗️ Data Architecture

The data architecture for this project follows the **Medallion Architecture**, consisting of **Bronze, Silver, and Gold layers**.

### 🥉 Bronze Layer

Stores raw data **as-is** from the source systems.

* Data is ingested from CSV files.
* Source systems include **ERP and CRM**.
* Raw data is loaded into a **SQL Server database**.

### 🥈 Silver Layer

This layer focuses on **data cleansing, standardization, and transformation** to prepare the data for analysis.

* Data cleaning
* Handling data quality issues
* Standardization
* Data transformation
* Data normalization

### 🥇 Gold Layer

The Gold layer contains **business-ready data** modeled using a **Star Schema** for reporting and analytics.

* Fact tables
* Dimension tables
* Business-ready datasets
* Analytical queries

---

## 📖 Project Overview

This project involves:

* **Data Architecture:** Designing a modern data warehouse using Medallion Architecture with Bronze, Silver, and Gold layers.
* **ETL Pipelines:** Extracting, transforming, and loading data from source systems into the warehouse.
* **Data Modeling:** Developing fact and dimension tables optimized for analytical queries.
* **Analytics & Reporting:** Creating SQL-based reports and dashboards to generate actionable business insights.

### 🎯 Skills Demonstrated

This repository is an excellent resource for professionals and students looking to showcase expertise in:

* SQL Development
* Data Architecture
* Data Engineering
* ETL Pipeline Development
* Data Modeling
* Data Analytics

---

## 🛠️ Important Links & Tools

**Everything is Free!** 🎉

* **Datasets:** Access to the project datasets (CSV files).
* **SQL Server Express:** Lightweight SQL Server for hosting the database.
* **SQL Server Management Studio (SSMS):** GUI for managing and interacting with the SQL Server database.
* **Git & GitHub:** Used for version control and managing the project repository.
* **Draw.io:** Used to design data architecture, data models, data flows, and ETL diagrams.
* **Notion:** Used for project planning and documentation.
* **Project Steps:** Access to all project phases and tasks.

---

# 🚀 Project Requirements

## Building the Data Warehouse (Data Engineering)

### 🎯 Objective

Develop a modern **data warehouse using SQL Server** to consolidate sales data, enabling analytical reporting and informed decision-making.

### 📋 Specifications

#### Data Sources

Import data from **two source systems**:

* ERP
* CRM

The source data is provided in the form of **CSV files**.

#### Data Quality

Cleanse and resolve data quality issues before using the data for analysis.

This includes:

* Handling missing values
* Removing duplicates
* Standardizing data
* Resolving inconsistencies
* Validating data

#### Integration

Combine data from both source systems into a **single, user-friendly data model** designed for analytical queries.

#### Scope

The project focuses on the **latest available dataset only**.

> Historical data tracking / historization is not required for this project.

#### Documentation

Provide clear documentation of:

* Data sources
* Data fields
* Data transformations
* Data architecture
* Data models
* Naming conventions

This documentation supports both **business stakeholders and analytics teams**.

---

# 📊 BI: Analytics & Reporting (Data Analysis)

### 🎯 Objective

Develop **SQL-based analytics** to deliver detailed insights into:

### 👥 Customer Behavior

Analyze customer purchasing behavior and identify valuable customer insights.

### 📦 Product Performance

Analyze product sales and identify high-performing and low-performing products.

### 📈 Sales Trends

Analyze sales performance and trends over time.

These insights help stakeholders understand key business metrics and support **strategic decision-making**.

> For more details, refer to `docs/requirements.md`.

---

# 📂 Repository Structure

```text
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project
│                                       # ERP and CRM data
│
├── docs/                               # Project documentation
│   ├── etl.drawio                      # ETL process and techniques
│   ├── data_architecture.drawio        # Project data architecture
│   ├── data_catalog.md                 # Dataset and field descriptions
│   ├── data_flow.drawio                # Data flow diagram
│   ├── data_models.drawio              # Data models / star schema
│   └── naming-conventions.md           # Naming conventions
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Extracting and loading raw data
│   ├── silver/                         # Cleaning and transforming data
│   └── gold/                           # Creating analytical models
│
├── tests/                              # Test scripts and data quality checks
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information
├── .gitignore                          # Git ignored files
└── requirements.txt                    # Project dependencies
```

---

## 🏆 Project Goal

The overall goal of this project is to build an end-to-end **Data Warehouse and Analytics solution** that demonstrates the complete process of:

**Raw Data → ETL → Data Cleaning → Data Modeling → Analytics → Business Insights**

🚀 **From raw ERP & CRM data to actionable business insights.**
