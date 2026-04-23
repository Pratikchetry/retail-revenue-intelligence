<div align="center">

# 🏪 Retail Revenue Intelligence & Anomaly Detection

### End-to-End Retail Analytics Project with PostgreSQL, Tableau, Power BI, and AI-Ready Extensions

<br>

![Python](https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Data%20Layer-336791?style=for-the-badge&logo=postgresql)
![Tableau](https://img.shields.io/badge/Tableau-Dashboard-E97627?style=for-the-badge&logo=tableau)
![Power%20BI](https://img.shields.io/badge/Power%20BI-DAX%20Companion-F2C811?style=for-the-badge&logo=powerbi)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-150458?style=for-the-badge&logo=pandas)
![scikit--learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?style=for-the-badge&logo=scikitlearn)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter)

</div>

---

## Project Overview

This project builds a retail analytics system from the **Online Retail II** dataset and is designed to answer four business questions:

1. **What happened?**  
   Revenue trends, country concentration, product performance, and sales structure

2. **Why did it happen?**  
   Returns, adjustments, merchandise vs non-merchandise logic, and customer concentration

3. **What should be monitored next?**  
   Customer segmentation, anomaly detection, and time-series behavior

4. **How should reporting be built correctly?**  
   Through a validated PostgreSQL data layer connected to Tableau and supported by Power BI / DAX

---

## Current Project Status

### Completed
- Raw data profiling
- Data cleaning
- Cleaning audit logging
- Exploratory data analysis
- Non-merchandise code identification
- PostgreSQL installation and initial schema work

### Current permanent data layers
- Raw source workbook
- Staging sales/returns/adjustments files
- Profiling and cleaning report artifacts

### Next
- PostgreSQL loader rewrite using staging files only
- Post-load validation against benchmark numbers
- SQL views
- RFM segmentation
- Anomaly detection
- Forecasting
- Tableau dashboard
- Power BI / DAX companion
- Later extension with Rossmann and NOAA data

---

## Dataset

### Current core dataset
- **Online Retail II**
- Two sheets:
  - `Year 2009-2010`
  - `Year 2010-2011`

### Source file fingerprint
- **MD5:** `ed54ccfc5d358481c399cc11d0a244be`

---

## Key Findings So Far

### Raw profiling
- **1,067,371** raw rows
- **34,335** exact duplicates
- **243,007** missing customer IDs
- **4,382** missing descriptions
- **22,950** negative-quantity rows
- **5** negative-price rows

### Clean staging sales dataset
- **1,007,914** valid sales rows
- **20,476,634.02** total revenue
- **11,205,149** total quantity sold
- **40,078** unique invoices
- **4,917** stock codes
- **43** countries

### Geographic concentration
- **United Kingdom revenue:** **17,410,569.69**
- **UK share of total revenue:** **85.03%**

### Seasonality
Top revenue months:
- **November** → **2,968,159.92**
- **October** → **2,313,165.95**
- **December** → **2,281,745.01**

### Product interpretation risk
Confirmed non-merchandise codes:
- `M` → Manual
- `DOT` → DOTCOM POSTAGE
- `POST` → POSTAGE

### Customer concentration
Customer-linked staging subset:
- **779,425** rows
- **5,878** identifiable customers

Top customer:
- `18102.0` → **580,987.04**

---

## Project Structure

```text
retail-revenue-intelligence/
├── data/
│   ├── raw/
│   │   └── online_retail_ii/
│   │       └── online_retail_II.xlsx
│   └── staging/
│       ├── sales_main.csv
│       ├── returns_cancellations.csv
│       ├── accounting_adjustments.csv
│       └── non_merchandise_codes.csv
│
├── docs/
│   ├── ABSTRACT.md
│   ├── ABOUT_THE_ANALYST.md
│   ├── data_findings.md
│   ├── HOW_TO_READ_NOTEBOOKS.md
│   ├── TABLEAU_GUIDE.md
│   └── validation_benchmarks.md
│
├── notebooks/
│   ├── 01_data_understanding.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_eda.ipynb
│   ├── 04_anomaly_detection.ipynb
│   ├── 05_forecasting.ipynb
│   ├── 06_rfm_segmentation.ipynb
│   └── 07_validation.ipynb
│
├── outputs/
│   └── reports/
│       ├── profiling_summary.json
│       └── cleaning_audit_log.csv
│
├── powerbi/
├── sql/
├── src/
├── tableau/
├── tests/
├── .env.example
├── .gitignore
├── README.md
└── requirements.txt
