# SQL Data Warehouse Project: From Scratch to Insights

## 📌 Project Overview
This project demonstrates how to build a **Modern SQL Data Warehouse** from the ground up. Following real-world best practices, I am designing a data architecture to transform raw data into a professional analytical model. 

The main goal is to implement a **Medallion Architecture** (Bronze, Silver, and Gold layers) to ensure data quality and provide a **"Single Source of Truth"** for business reporting.

---

## 🏗️ Data Architecture
The project follows a multi-layer approach to process and refine data:

| Layer | Description |
| :--- | :--- |
| **Bronze** | **Raw Data:** Direct import from source systems (CSV files). |
| **Silver** | **Cleansed Data:** Cleaned and standardized data where transformations are applied. |
| **Gold** | **Curated Data:** Final data model using a **Star Schema** (Fact and Dimension tables) ready for analysis. |

---

## 🛠️ Tools Used
* **Database Engine:** SQL Server Express.
* **Management Tool:** SQL Server Management Studio (SSMS).
* **Language:** T-SQL (Transact-SQL).
* **Architecture Pattern:** ETL (Extract, Transform, Load).

---

## 🚀 Key Features
* **Data Integration:** Merging multiple data sources into a centralized system.
* **Data Cleansing:** Removing errors and formatting data for business consistency.
* **Data Modeling:** Designing a **Star Schema** to optimize query performance and reporting.
* **Quality Checks:** Implementing automated SQL scripts to validate data integrity and accuracy in the Gold layer.

---

## 📂 Project Structure
```bash
├── Scripts/          # SQL scripts for tables, views, and stored procedures
├── Tests/            # Quality gate scripts to verify the Gold layer
├── Docs/             # Documentation regarding data flow and requirements
└── README.md         # Project documentation

---

## Project inspired by the "Data with Baraa" YouTube tutorial.
