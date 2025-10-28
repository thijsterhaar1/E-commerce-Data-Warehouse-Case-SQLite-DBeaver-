# 🛒 E-commerce Data Warehouse Case (SQLite & DBeaver)

This project was completed as part of a SQL / data warehouse exercise.  
The goal was to set up a small e-commerce database, perform data quality checks, and build reporting views for analysis.

---

## 📚 Overview

- Importing and exploring raw CSV data in DBeaver (SQLite)
- Performing data quality checks (duplicates and nulls)
- Creating analytical SQL views for reporting and validation

---

## 🧠 Tools & Technologies

- **SQLite** – lightweight database engine  
- **DBeaver** – SQL client and data management tool  
- **SQL** – for data cleaning, validation, and view creation  

---

## 🧩 Project Steps & Screenshots

All screenshots can be found in the [`/screenshots`](./screenshots) folder.  
Below is the process flow with matching files:

### 🧱 1. Data Import & Setup
| Step | Description | Screenshot |
|------|--------------|-------------|
| 1a | Table structure of `DimCampaign` verified after import | `1a_TableStructure_DimCampaign_SQL.png` |
| 1b | Data preview of `DimCampaign` | `1b_DataPreview_DimCampaign_SQL.png` |
| 1c | Import check of `DimProduct` | `1c_DataImport_DimProduct_SQL.png` |
| 1d | Import check of `FactOrders` | `1d_DataImport_FactOrders_SQL.png` |
| 2 | Verification of all loaded tables in DBeaver | `2_CheckExistingTables_SQL.png` |

---

### 🔍 2. Data Quality Checks
| Step | Description | Screenshot |
|------|--------------|-------------|
| 4a | Duplicate record check on key columns | `4a_DQ_Check_Duplicates_SQL.png` |
| 4b | Null value check across key attributes | `4b_DQ_Check_Nulls_SQL.png` |

---

### 📊 3. View Creation
| Step | Description | Screenshot |
|------|--------------|-------------|
| 5a | `vw_fact_orders_clean` – cleaned orders view | `5a_View_FactOrdersClean_SQL.png` |
| 5b | `vw_sales_summary` – sales summary with customer and product details | `5b_View_SalesSummary_SQL.png` |
| 5c | `vw_fact_marketing_summary` – marketing spend per campaign and channel | `5c_View_FactMarketingSummary_SQL.png` |

---

## 📈 Results

The final database structure provides:
- Cleaned and validated sales order data  
- Aggregated sales insights per customer and product  
- Marketing spend analysis per campaign and channel  

These SQL views can be directly used for Power BI or Tableau dashboards.

---

🧑‍💻 **Author:** Thijs ter Haar
📅 **Date:** October 2025
