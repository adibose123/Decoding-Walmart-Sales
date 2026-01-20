# Walmart Retail Intelligence: End-to-End SQL & Python Analytics Project

## Project Summary
This project delivers a comprehensive data engineering and analytics solution designed to extract actionable business insights from massive Walmart sales datasets. By architecting a pipeline that spans from automated data ingestion via the Kaggle API to advanced querying in MySQL and PostgreSQL, this project demonstrates the ability to transform raw, unstructured data into a strategic business asset.

---

## Technical Ecosystem

**Languages:**  
Python 3.8+ (Data Engineering), SQL (Business Logic)

**Data Tools:**  
Pandas, NumPy (Data Manipulation)

**Database Systems:**  
MySQL, PostgreSQL

**Infrastructure:**  
SQLAlchemy (ORM), Kaggle API (Data Sourcing)

**Development Environment:**  
Visual Studio Code

---

## The Analytical Pipeline

### 1. Automated Ingestion & Environment Setup
**Workspace Configuration:**  
Established a structured directory for data, SQL scripts, and Python notebooks.

**Kaggle API Integration:**  
Automated the retrieval of the Walmart 10k Sales Dataset directly into the project environment, ensuring a reproducible data sourcing process.

---

### 2. Sophisticated Data Cleaning & Transformation
Before analysis, the raw data underwent a rigorous cleaning process to ensure integrity:

**Integrity Checks:**  
Identified and removed duplicate records and handled missing values to prevent skewed reporting.

**Type Standardization:**  
Validated and cast data types, specifically ensuring currency values and dates were formatted for computational accuracy.

**Feature Engineering:**  
Created a Total Amount field (unit_price × quantity) within the pipeline to streamline high-level SQL aggregations.

---

### 3. Database Architecture & Loading
**Automated Schema Mapping:**  
Leveraged SQLAlchemy to automate table creation and data insertion across both MySQL and PostgreSQL environments.

**Multi-Database Support:**  
Ensured the pipeline is compatible with various relational database management systems (RDBMS).

---

### 4. Advanced SQL Business Logic
The core of the project involves executing complex queries to address critical retail KPIs, including:

**Revenue Optimization:**  
Analyzing trends across different branches and product categories.

**Operational Efficiency:**  
Identifying peak shopping hours and preferred payment methods to optimize staffing and checkout flows.

**Profitability Analysis:**  
Determining the highest-margin categories and locations to inform inventory and marketing strategies.

---

## Key Business Questions Addressed

| Objective | Analysis Focus |
|--------|----------------|
| Sales Performance | Which branches outperform others in total revenue? |
| Product Strategy | What are the best-selling categories by volume and value? |
| Consumer Insights | What are the peak sales periods and most common payment methods? |
| Profitability | Which specific product lines yield the highest profit margins? |

---

## Project Structure

```plaintext
|-- data/                 # Raw and processed datasets
|-- sql_queries/          # Advanced SQL scripts for business logic
|-- notebooks/            # Python EDA and ETL scripts
|-- main.py               # Central execution script for cleaning & loading
|-- requirements.txt      # Project dependencies
