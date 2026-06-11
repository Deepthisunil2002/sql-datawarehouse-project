# sql-datawarehouse-project
Building a modern data warehouse with SQL Server ,including ETL processes, data modelling and analytics

## About This Project

This project was developed as part of my Data Engineering learning journey to gain hands-on experience in data warehousing, ETL development, dimensional modeling, and SQL-based analytics.

# Data Warehouse and Analytics Project

## Overview

This project demonstrates the implementation of a modern Data Warehouse and Analytics solution using SQL Server. The objective is to build a scalable data warehouse that consolidates data from multiple source systems and transforms it into a business-ready analytical model.

The project covers the complete data lifecycle, including data ingestion, transformation, modeling, and reporting. It follows industry-standard data engineering practices and serves as a hands-on portfolio project for showcasing skills in Data Engineering and Analytics.

---

## Data Architecture

The solution is designed using the Medallion Architecture pattern, which consists of three layers:

### Bronze Layer

* Stores raw data extracted from source systems.
* Data is loaded directly from CSV files into SQL Server.
* Maintains source data in its original form.

### Silver Layer

* Performs data cleansing, transformation, and standardization.
* Resolves data quality issues.
* Prepares data for downstream analytical processing.

### Gold Layer

* Contains curated and business-ready datasets.
* Implements dimensional modeling using a Star Schema approach.
* Optimized for reporting and analytical workloads.

![Data Architecture](docs/data_architecture.png)

---

## Project Objectives

The main goals of this project are:

### 1. Data Warehouse Development

* Design and implement a modern data warehouse architecture.
* Organize data using Bronze, Silver, and Gold layers.
* Create a structured foundation for analytics and reporting.

### 2. ETL Pipeline Implementation

* Extract data from multiple source systems.
* Apply cleansing and transformation rules.
* Load processed data into analytical layers.

### 3. Data Modeling

* Build fact and dimension tables.
* Develop a Star Schema optimized for analytical queries.
* Improve reporting performance and usability.

### 4. Analytics and Reporting

* Generate SQL-based analytical reports.
* Analyze customer behavior, product performance, and sales trends.
* Deliver business insights that support decision-making.

---

## Skills Demonstrated

This project showcases practical experience in:

* SQL Development
* Data Warehousing
* Data Engineering
* ETL Pipeline Design
* Data Modeling
* Data Transformation
* Analytics and Reporting
* Database Design

---

## Tools and Technologies

The following tools were used throughout the project:

* SQL Server Express
* SQL Server Management Studio (SSMS)
* SQL
* Draw.io
* Git & GitHub
* CSV Data Sources

---

## Project Requirements

### Data Engineering

#### Objective

Develop a centralized data warehouse that integrates sales data from multiple systems and supports analytical reporting.

#### Requirements

* Import data from ERP and CRM source systems.
* Load source data provided as CSV files.
* Perform data cleansing and quality checks.
* Integrate multiple data sources into a unified analytical model.
* Focus on the most recent dataset without historization.
* Maintain clear documentation for business and technical users.

---

### Analytics and Reporting

#### Objective

Develop SQL-based analytical solutions that provide insights into:

* Customer Behavior
* Product Performance
* Sales Trends

The resulting reports and analyses support business decision-making through meaningful metrics and data-driven insights.

---

## Repository Structure

```text
data-warehouse-project/
│
├── datasets/
│   └── Raw ERP and CRM datasets
│
├── docs/
│   ├── etl.drawio
│   ├── data_architecture.drawio
│   ├── data_catalog.md
│   ├── data_flow.drawio
│   ├── data_models.drawio
│   └── naming-conventions.md
│
├── scripts/
│   ├── bronze/
│   ├── silver/
│   └── gold/
│
├── tests/
│
├── README.md
├── LICENSE
├── .gitignore
└── requirements.txt
```

---

## Key Deliverables

* Modern Data Warehouse Architecture
* ETL Pipelines
* Data Quality Validation
* Star Schema Data Model
* Business-Ready Gold Layer
* SQL Analytics Reports
* Documentation and Data Catalog

---

## License

This project is licensed under the MIT License. Feel free to use, modify, and extend it for learning and educational purposes.
