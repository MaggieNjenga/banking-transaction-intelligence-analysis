# Banking Transaction Intelligence & Performance Analysis

**Client:** Meridian Commercial Bank (Fictional)  
**Project type:** End-to-end banking data analytics and business intelligence  
**Status:** In Progress  
**Tools:** SQL Server, Python, Power BI  
**Project period:** November 2026

## 1. Project Overview

This project simulates an end-to-end banking analytics engagement for Meridian Commercial Bank, a fictional financial institution seeking improved visibility into transaction performance, customer behaviour, merchant activity and potential transaction risks.

Using a publicly available synthetic banking transaction dataset, the project demonstrates how transaction-level data can be transformed into actionable business intelligence through data engineering, exploratory analysis, SQL, Python and interactive Power BI reporting.

The objective is to develop a reproducible analytical solution that supports evidence-based business decisions while demonstrating the technical and analytical capabilities required of a data analyst.

**Important:** The dataset is synthetic and does not represent actual bank customers, transactions or financial performance. Findings must therefore be interpreted within the limitations of the simulated data.

## 2. Business Problem

Meridian Commercial Bank requires a consolidated analytical view of transaction activity to understand customer and merchant behaviour, identify transaction concentrations, monitor activity trends and investigate unusual patterns.

Without structured analysis, management may overlook important customer segments, misinterpret transaction performance and fail to identify patterns that warrant further investigation.

This project addresses the problem by developing a structured analytical workflow that converts transaction records into meaningful performance indicators, visual insights and management recommendations.

## 3. Analytical Objectives

The investigation focuses on five areas:

1. **Customer Behaviour Analysis:** Examine transaction frequency, values, customer activity and transaction concentration.
2. **Merchant Performance Analysis:** Evaluate transaction volumes, values and spending patterns across merchant categories.
3. **Temporal Analysis:** Investigate transaction trends, peak periods and changes in activity over time.
4. **Risk and Anomaly Analysis:** Examine unusual transaction patterns and assess the dataset's existing synthetic fraud labels.
5. **Transaction Concentration Analysis:** Identify segments and categories responsible for disproportionately large shares of transaction activity.

## 4. Dataset

**Dataset:** BankSim — Synthetic data from a financial payment system.

The dataset contains approximately 594,643 transaction records and 10 fields, including:

- Customer identifiers
- Merchant identifiers
- Transaction amounts
- Merchant categories
- Time-step information
- Encoded customer attributes
- Synthetic fraud labels

The dataset is publicly available through Kaggle.

**Source:** https://www.kaggle.com/datasets/ealaxi/banksim1

The dataset will be assessed and validated before analytical use. Refer to the data dictionary and data quality documentation for field definitions and validation results.

## 5. Technology Stack

| Technology | Application |
|---|---|
| SQL Server | Data storage, transformation, validation and querying |
| Python | Exploratory data analysis, statistical analysis and anomaly investigation |
| Power BI | Interactive dashboards and business intelligence reporting |
| Git / GitHub | Version control, collaboration and project documentation |

## 6. Project Workflow

The project follows an end-to-end analytical workflow:

1. Business understanding and requirements definition.
2. Data acquisition and initial assessment.
3. Data profiling, cleaning and validation.
4. SQL database development and analytical querying.
5. Exploratory and statistical analysis using Python.
6. KPI development and analytical validation.
7. Power BI data modelling and dashboard development.
8. Interpretation of findings and management recommendations.
9. Executive reporting and project documentation.

## 7. Repository Structure

```text
banking-transaction-intelligence-analysis/
│
├── 01_project_documentation/
│   ├── project_charter.md
│   ├── business_requirements.md
│   ├── analytical_objectives.md
│   └── investigative_questions.md
│
├── 02_data/
│   ├── raw/
│   ├── processed/
│   └── README.md
│
├── 03_sql/
│   ├── database_setup/
│   ├── data_cleaning/
│   ├── data_validation/
│   └── analysis/
│
├── 04_python/
│   ├── notebooks/
│   ├── scripts/
│   └── outputs/
│
├── 05_power_bi/
│   ├── dashboard/
│   └── documentation/
│
├── 06_reports/
│   ├── data_quality_report.md
│   ├── analytical_findings.md
│   └── management_recommendations.md
│
├── 07_documentation/
│   ├── data_dictionary.md
│   ├── methodology.md
│   └── kpi_definitions.md
│
├── README.md
└── .gitignore
```

## 8. Important Dataset Limitations

The following limitations have been identified during the initial assessment:

- The dataset does not distinguish completed, reversed, cancelled and failed transactions.
- Geographic fields contain only one unique origin postcode and one unique merchant postcode, preventing meaningful regional comparisons.
- The dataset includes synthetic fraud labels, not independently verified real-world fraud cases.
- Bank revenue, transaction fees, operating costs and customer profitability information have not been established.
- Customer age and gender values are encoded and require verification.
- The time-step field requires interpretation before calendar-based reporting can be undertaken.

These limitations will guide the analysis and prevent unsupported business conclusions.

## 9. Expected Deliverables

- Business requirements and project charter.
- Dataset documentation and data dictionary.
- Data quality assessment.
- SQL Server database and analytical scripts.
- Python analytical notebook.
- Validated KPIs and analytical findings.
- Interactive Power BI dashboard.
- Management recommendations.
- Executive report and presentation.

## 10. Project Status

| Workstream | Status |
|---|---|
| Business investigation | Completed |
| Dataset selection | Completed |
| Initial dataset assessment | Completed |
| Project charter | Prepared |
| Detailed data dictionary | Pending |
| SQL database development | Pending |
| Data cleaning and validation | Pending |
| Analytical investigation | Pending |
| Power BI dashboard | Pending |
| Final reporting | Pending |

## 11. Reproducibility

The repository will contain the scripts, notebooks, documentation and instructions required to understand and reproduce the analytical workflow.

Raw datasets may be excluded from version control where file size or licensing considerations make redistribution inappropriate. Instructions for obtaining the original dataset will be provided.

---

**Project Analyst:** Margaret Njenga  
**Repository:** banking-transaction-intelligence-analysis
