# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀  
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights data engineering and analytics skills relevant for aspiring full-stack developers and ML enthusiasts.

---

## 🏗️ Data Architecture

The data architecture follows a Medallion Architecture with **Bronze**, **Silver**, and **Gold** layers:

![Data Architecture](docs/data_architecture.png)

1. **Bronze Layer**: Stores raw data as-is from the source systems (CSV files).
2. **Silver Layer**: Cleanses, standardizes, and normalizes data for analysis.
3. **Gold Layer**: Business-ready data modeled into a star schema for reporting and analytics.

---

## 📖 Project Overview

This project involves:

- **Data Architecture**: Designing a modern data warehouse with Bronze, Silver, and Gold layers.
- **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.
- **Data Modeling**: Creating fact and dimension tables optimized for analytical queries.
- **Analytics & Reporting**: SQL-based reports and dashboards for actionable insights.

🎯 This repository demonstrates skills in:

- SQL Development
- Data Engineering & Modeling
- ETL Pipelines
- Data Analytics & Reporting

---

## 🛠️ Tools & Resources

- **[Datasets](datasets/):** CSV files used for the project  
- **[SQL Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads):** Lightweight database server  
- **[SQL Server Management Studio (SSMS)](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16):** Database GUI  
- **[DrawIO](https://www.drawio.com/):** Designing data architecture, flows, and diagrams  
- **[Notion Template](https://www.notion.so/):** Optional project planning template  

---

## 🚀 Project Requirements

### Building the Data Warehouse

**Objective:**  
Develop a modern data warehouse using SQL Server to consolidate sales data for analytical reporting.

**Key Tasks:**  

- Import data from CSV source systems  
- Cleanse and resolve data quality issues  
- Integrate both sources into a single analytical model  
- Document the data model for stakeholders and analytics teams  

---

### Analytics & Reporting

**Objective:**  
Generate SQL-based insights on:

- Customer Behavior  
- Product Performance  
- Sales Trends  

These insights empower data-driven decisions and showcase your analytics skills.

---

## 📂 Repository Structure

```
data-warehouse-project/
├── datasets/          # Raw datasets (CSV files)
├── docs/              # Documentation, architecture diagrams
│   ├── data_architecture.png
│   ├── data_models.drawio
│   └── requirements.md
├── scripts/           # SQL scripts for ETL and transformations
│   ├── bronze/
│   ├── silver/
│   └── gold/
├── tests/             # Test scripts and data quality checks
├── README.md
├── LICENSE
├── .gitignore
└── requirements.txt   # Dependencies and project requirements
```

---

## 📫 Contact

Feel free to reach out:

- Email: [ashmeet.code@gmail.com](mailto:ashmeet.code@gmail.com)  
- LinkedIn: Coming soon  

