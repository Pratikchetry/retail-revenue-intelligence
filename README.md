<div align="center">

# 🏪 Retail Revenue Intelligence & Anomaly Detection

### End-to-End Analytics System for Revenue Monitoring, Customer Segmentation, and AI-Driven Insights

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
- support dashboard reporting through a central PostgreSQL data layer
- connect the same cleaned data system to Tableau and Power BI

The project uses the **Online Retail II** dataset as the core transaction source and is being developed step by step using a senior data analyst workflow.

---

## 🎯 Project Goals

The system is being designed to answer questions such as:

- How is revenue changing over time?
- Which countries and products contribute the most revenue?
- Where do unusual spikes or drops occur?
- Which customers are most valuable?
- Which customers may become inactive or at risk?
- How can one central data layer support both Tableau and Power BI workflows?

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
