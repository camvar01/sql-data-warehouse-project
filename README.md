SQL Data Warehouse Project: From Scratch to Insights
📌 Project Overview
This project demonstrates how to build a Modern SQL Data Warehouse from the ground up. Following real-world best practices, I am designing a data architecture to transform raw data into a professional analytical model.

The main goal is to implement a Medallion Architecture (Bronze, Silver, and Gold layers) to ensure data quality and provide a "Single Source of Truth" for business reporting.

🏗️ Data Architecture
The project follows a multi-layer approach to process data:

Bronze Layer: Raw data imported from source systems (CSV files).

Silver Layer: Cleaned and standardized data where transformations are applied.

Gold Layer: Final data model using a Star Schema (Fact and Dimension tables) ready for analysis.

🛠️ Tools Used
Database Engine: SQL Server Express.

Management Tool: SQL Server Management Studio (SSMS).

Language: T-SQL (Transact-SQL).

Architecture Pattern: ETL (Extract, Transform, Load).

🚀 Key Features
Data Integration: Merging multiple data sources into one system.

Data Cleansing: Removing errors and formatting data for consistency.

Data Modeling: Creating a Star Schema to improve query performance.

Quality Checks: Implementing SQL scripts to validate data integrity and accuracy.

📂 Project Structure
Scripts/: SQL scripts for creating tables, views, and stored procedures.

Tests/: Quality gate scripts to verify the Gold layer.

Docs/: Documentation regarding data flow and business requirements.

Project inspired by the "Data with Baraa" YouTube tutorial.
