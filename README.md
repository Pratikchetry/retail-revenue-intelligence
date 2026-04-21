<div align="center">

# 🏪 Retail Revenue Intelligence & Anomaly Detection

### End-to-End Analytics System for Revenue Monitoring, Customer Segmentation, Forecasting, and AI-Driven Insights

<br>

![Python](https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Data%20Layer-336791?style=for-the-badge&logo=postgresql)
![Tableau](https://img.shields.io/badge/Tableau-Dashboard-E97627?style=for-the-badge&logo=tableau)
![Power%20BI](https://img.shields.io/badge/Power%20BI-DAX%20Companion-F2C811?style=for-the-badge&logo=powerbi)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-150458?style=for-the-badge&logo=pandas)
![scikit--learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?style=for-the-badge&logo=scikitlearn)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter)
![EDA](https://img.shields.io/badge/EDA-Completed-4CAF50?style=for-the-badge)
![Data%20Cleaning](https://img.shields.io/badge/Data%20Cleaning-Completed-00C853?style=for-the-badge)

</div>

---

## 📌 Project Overview

This project is being built to create a retail analytics system that helps a business:

- understand revenue performance over time
- detect unusual sales patterns
- identify high-value and at-risk customers
- forecast future revenue trends
- support dashboard reporting through a central PostgreSQL data layer
- connect the same cleaned data system to Tableau and Power BI

The project currently uses the **Online Retail II** dataset as the core transaction source and is being developed step by step using a senior data analyst workflow.

---

## 🎯 Project Goals

The system is being designed to answer questions such as:

- How is revenue changing over time?
- Which countries and products contribute the most revenue?
- Where do unusual spikes or drops occur?
- Which customers are most valuable?
- Which customers may become inactive or at risk?
- How can one central data layer support both Tableau and Power BI workflows?
- How can forecasting and external enrichment improve business planning?

---

## 🧱 Tech Stack

- **Python** — data loading, cleaning, EDA, ML workflows
- **PostgreSQL** — central data layer / warehouse
- **Tableau** — dashboard and business reporting
- **Power BI / DAX** — companion KPI and semantic modeling showcase
- **Jupyter Notebooks** — step-by-step project development
- **scikit-learn** — anomaly detection
- **statsmodels** — forecasting

---

## 📂 Current Project Structure

```bash
retail-revenue-intelligence/
├── data/
│   ├── raw/
│   ├── processed/
│   └── exports/
├── docs/
├── notebooks/
├── powerbi/
├── reports/
├── sql/
├── src/
├── tableau/
├── tests/
├── .env.example
├── .gitignore
├── README.md
└── requirements.txt

## 🔄 Planned Extension After Core Dashboard Completion

After completing the main pipeline and dashboard using the **Online Retail II** dataset, the project will be extended with two additional datasets to make the solution stronger and more realistic from a senior data analyst perspective.

### 1. Rossmann Store Sales (Kaggle)
This dataset will be added as an **extension module** after the core Online Retail dashboard is complete.

#### Why it will be added
The Online Retail II dataset is strong for:
- revenue analysis
- customer segmentation
- anomaly detection
- product and country analysis

But it is limited for:
- store-level time-series forecasting
- promotion effect analysis
- holiday-driven performance analysis

Rossmann will be used to strengthen those areas.

#### What we will do with Rossmann
- build a stronger **forecasting workflow**
- perform **store-level trend modeling**
- analyze the impact of **promotions**
- analyze the effect of **holidays and seasonality**
- compare forecasting patterns with the Online Retail II core analysis

#### Why it matters
This will make the project more complete by showing both:
- transaction-level retail intelligence
- store-level retail forecasting and operational analysis

---

### 2. NOAA Climate Data
NOAA weather data will be added after the Rossmann extension if weather enrichment is needed.

#### Why it will be added
Weather can influence time-series retail behavior in some business scenarios. Adding NOAA data will help demonstrate external feature enrichment.

#### What we will do with NOAA
- enrich time-series datasets with **weather variables**
- test whether weather patterns align with **sales movement**
- support **weather-linked revenue pattern exploration**
- improve business storytelling around external drivers

#### Why it matters
This will show how external data can be blended into a retail analytics workflow, which is a strong senior-level analytics skill.

---

## 🧩 Final Project Roadmap

### Phase 1 — Core Online Retail II Pipeline
- raw data understanding
- data cleaning
- EDA
- PostgreSQL integration
- RFM segmentation
- anomaly detection
- forecasting
- validation
- Tableau dashboard
- Power BI / DAX companion

### Phase 2 — Rossmann Extension
- store-level forecasting
- promotion analysis
- holiday effect analysis
- stronger time-series modeling

### Phase 3 — NOAA Enrichment
- weather-based feature enrichment
- external-factor exploration
- weather-linked sales pattern analysis

---

## 📌 Important Note
The **Online Retail II dataset** is the main core project and will be completed first.

The **Rossmann** and **NOAA** datasets will be added afterward as advanced extension layers to strengthen forecasting, store-level analysis, and external-factor business interpretation.
