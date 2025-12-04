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
