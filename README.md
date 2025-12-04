# Data Warehouse & Financial Analytics Project

## Overview
This project demonstrates real-world data engineering and financial analytics skills using Python and SQL-style operations.  
It replicates practical industry workflows such as data ingestion, table creation, joins, transaction management, sector-level analytics, and rollback/commit operations.

The project uses 2007–2008 financial data to analyze company performance, sector risk changes, and transactional updates.  
It includes end-to-end processing: loading raw datasets, cleaning, joining, running transactional updates, and generating analytical outputs.

---

## Project Objectives
### 1. **Data Ingestion & Warehouse Setup**
- Load multiple financial datasets (2007 & 2008 data)
- Create structured tables similar to warehouse layers
- Validate schema, datatypes, and row counts

### 2. **Transaction Management Demonstration**
- Identify target financial records
- Perform controlled updates (simulated stress tests)
- Execute:
  - COMMIT
  - ROLLBACK
  - Partial rollback
- Track before-and-after values

### 3. **JOIN Operations & Financial Analytics**
- INNER JOIN, LEFT JOIN, FULL OUTER JOIN
- Combine 2007 & 2008 companies
- Handle missing data consistently
- Map industries to sectors
- Compute sector-level beta averages for both years
- Create a cross-year risk comparison table

---

## Files Included

Data-Warehouse-Financial-Analytics-Project
│── Transaction_Management_Financial_Data.ipynb
│── Financial_Sector_Analytics_and_Joins.ipynb
│── financial_data_2007.csv
│── financial_data_2008.csv
│── industry_sector_mapping.csv



**Notebooks**
- **Transaction_Management_Financial_Data.ipynb**  
  Demonstrates update operations, backup creation, rollback/commit, and transactional control.

- **Financial_Sector_Analytics_and_Joins.ipynb**  
  Performs joins, survival analysis of companies, and sector-level beta comparison across 2007–2008.

**Datasets**
- `financial_data_2007.csv` – historical financial indicators  
- `financial_data_2008.csv` – updated year dataset  
- `industry_sector_mapping.csv` – maps industries to sectors

---

## Key Insights & Results
### ✔ Company Survival Analysis (2007 → 2008)
Identified:
- companies that survived both years
- companies that disappeared in 2008

### ✔ Sector-Level Risk Comparison
Calculated **average beta per sector** for both years to observe risk shifts:
- Some sectors saw significant increases during 2008 economic volatility.
- Delivered meaningful risk insights across 13 sectors.

### ✔ Transaction Demonstration
Performed a full update cycle:
- backed up original rows  
- updated beta values  
- compared before vs after  
- executed rollback to restore the data  
- performed safe COMMIT demonstration  

This simulates **real financial system workflows**.

---

## Tech Stack
- **Python (Pandas, NumPy)**
- **Jupyter Notebook**
- **SQL-style operations using Pandas**
- **Data Engineering concepts (Joins, Transactions, Backups)**

---

## How to Run
1. Open the notebooks in Jupyter or GitHub Codespaces.
2. Ensure the CSV datasets are in the same directory.
3. Run the cells sequentially to reproduce the data transformations and analytics.

---

## Author
**Hely Shah**  
*Master of Science in Computer Science*  
Focused on Data Engineering, Machine Learning, and Financial Analytics.

---

## Notes
This project demonstrates practical data warehouse logic and financial dataset handling in a professional, industry-relevant format.  
Suitable for showcasing data analyst & data engineering capabilities on resumes and interviews.

