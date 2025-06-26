#  Modern SQL Data Warehouse Project (Bronze/Silver/Gold ETL Pipeline)

This project demonstrates the design and implementation of a **modern data warehouse** using SQL Server and the **Medallion Architecture** (Bronze → Silver → Gold layers). It includes data ingestion, transformation, modeling, and analytical querying – a complete ETL pipeline built for performance and clarity.

---

##  Project Overview

- **Architecture Used**: Medallion Architecture (Bronze, Silver, Gold)
- **Goal**: To simulate a real-world data warehousing process from source data → clean model → business insights
- **Use Case**: Retail/CRM analytics using customer, product, and sales datasets

---

##  Tech Stack

| Layer       | Technology Used       |
|-------------|------------------------|
| Database    | Microsoft SQL Server   |
| Language    | T-SQL                  |
| ETL         | Procedural SQL Scripts |
| Data Format | CSV (CRM, ERP sources) |
| Tools       | SSMS, Excel (optional) |

---

## Layer-wise Breakdown

###  Bronze Layer – Raw Data Ingestion
- Source: ERP & CRM data (CSV files)
- Tables: `raw_customers`, `raw_products`, `raw_sales`
- Goal: Load raw data without transformation

###  Silver Layer – Data Cleaning & Validation
- Standardization, deduplication, null checks
- Tables: `clean_customers`, `clean_products`, `clean_sales`

###  Gold Layer – Business-Ready Models
- Fact-Dimension Modeling (Star Schema)
- Tables: `fact_sales`, `dim_customer`, `dim_product`
- Optimized for analytics and reporting

---

## License (MIT)
MIT License © 2025 sinchana  
Free to use, modify, and distribute with attribution.  
No warranty provided.


