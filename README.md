# Books-DWH-ETL-Project
An end-to-end Data Engineering pipeline transforming a 15-table OLTP source into a SQL Data Warehouse and SSAS Cube for analytical insights.


End-to-End Books BI Pipeline (DWH & ETL) Project Overview This project demonstrates a complete Data Engineering workflow, transforming a raw OLTP system into a structured Data Warehouse (DWH) and OLAP environment. The goal was to build a reliable pipeline that cleans, models, and aggregates book sales data to support business analytics.

🏗️ Data Architecture The data flows through four distinct stages to ensure integrity and performance:

Source (OLTP): A relational SQL database with 15 interconnected tables.

Staging & ETL (SSIS): Data extraction and transformation layer.

Warehouse (SQL Server): A centralized repository modeled in a Star Schema.

Semantic Layer (SSAS): Multidimensional cube for pre-calculated metrics.

🛠️ Technical Implementation

1- Data Modeling (SQL Server) Architected a Star Schema to replace the complex 15-table relational structure.
Implemented Fact and Dimension tables to optimize query performance and storage.

2- ETL Pipeline (SSIS) Developed +5 SSIS packages to automate the end-to-end data flow.
Transformations: Implemented data cleansing, lookups, and derived columns to handle data quality issues.

Automation: Ensured seamless loading from staging to production tables.

3- OLAP Modeling (SSAS) Built Multidimensional Cubes to handle complex business logic and aggregations.

4- Data Validation (Power BI) Deployed a functional dashboard as a final validation layer to verify the accuracy of the entire pipeline.


