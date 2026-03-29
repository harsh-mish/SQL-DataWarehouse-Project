## 🏗️ Medallion Architecture (Bronze → Silver → Gold)

This diagram illustrates the layered data pipeline used in this project, where raw data is ingested into the Bronze layer, transformed in the Silver layer, and modeled into analytics-ready data in the Gold layer.

<img src="Medallion Architecture.png" width="700">



##  SQL-DataWarehouse-Project
Building a Modern Data Warehouse with SQL Server, including ETL process, data modelling and analytics.

# 📊 SQL Data Warehouse Project

## 🚀 Overview

This project demonstrates the end-to-end implementation of a **Modern Data Warehouse** using SQL Server. It covers the complete data engineering lifecycle including **data ingestion, transformation, modeling, and analytics**.

The goal of this project is to transform raw data into meaningful insights that can support **business decision-making**.



## 🏗️ Architecture

This project follows the **Medallion Architecture**:

* **Bronze Layer**
  Raw data ingestion from source systems (CSV / external data)

* **Silver Layer**
  Data cleaning, transformation, and standardization

* **Gold Layer**
  Business-ready data modeled into **Fact and Dimension tables (Star Schema)**



## 🔧 Tech Stack

* SQL Server
* SQL (T-SQL)
* SSMS (SQL Server Management Studio)
* Git & GitHub
* Draw.io (for architecture diagrams)



 📂 Project Structure

SQL-DataWarehouse-Project/
│
├── datasets/        # Raw data files
├── scripts/
│   ├── bronze/      # Data ingestion scripts
│   ├── silver/      # Data cleaning & transformation
│   ├── gold/        # Data modeling (fact & dimension tables)
│
├── docs/            # Architecture diagrams & documentation
├── tests/           # Data validation & testing scripts
└── README.md



 ⚙️ ETL Pipeline

1. **Extract**

   * Data is loaded from CSV files into Bronze tables

2. **Transform**

   * Cleaned and standardized in Silver layer
   * Handled null values, duplicates, and inconsistencies

3. **Load**

   * Transformed into analytical models (Gold layer)
   * Star schema implemented for reporting



 📊 Data Modeling

* Fact Tables → store transactional data
* Dimension Tables → store descriptive attributes
* Implemented **Star Schema** for efficient querying



 📈 Key Features

* End-to-end data pipeline using SQL
* Medallion Architecture implementation
* Data cleaning & transformation logic
* Scalable and modular design
* Optimized queries for analytics



 🧠 Learnings

* Hands-on experience in **Data Engineering concepts**
* Understanding of **ETL pipelines**
* Practical implementation of **Data Warehousing**
* Writing optimized SQL queries
* Data modeling techniques (Star Schema)



 ▶️ How to Run

1. Clone the repository:

   git clone https://github.com/harsh-mish/SQL-DataWarehouse-Project
   

2. Open SQL Server Management Studio

3. Run scripts in order:

   * Bronze layer
   * Silver layer
   * Gold layer

4. Query the Gold layer for analysis


📌 Future Improvements

* Add Power BI / Tableau dashboard
* Automate ETL using scheduling tools
* Add incremental data loading
* Implement data quality checks


 🤝 Contributing

Feel free to fork this repository and improve it.


 📜 License

This project is open-source and available under the MIT License.

