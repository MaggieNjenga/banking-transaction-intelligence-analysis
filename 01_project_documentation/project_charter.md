# Project Charter
## Banking Transaction Intelligence & Performance Analysis

**Client:** Meridian Commercial Bank (Fictional)  
**Project type:** Banking transaction analytics and business intelligence  
**Project duration:** Five working days  
**Project start:** 4 November 2026  
**Project deadline:** 8 November 2026  
**Version:** 1.0

---

## 1. Project Background

Meridian Commercial Bank requires improved visibility into its transaction activity, customer behaviour, merchant activity and potential transaction risks.

Management needs an evidence-based assessment of transaction patterns to understand where activity is concentrated, identify important customer and merchant segments, monitor changes in transaction behaviour and identify patterns that may warrant further investigation.

The project will simulate an internal banking analytics engagement using publicly available synthetic transaction data from BankSim.

The dataset does not represent actual Meridian customers or transactions. All findings and recommendations will therefore be presented as simulated analytical findings rather than actual bank performance.

## 2. Business Problem Statement

Meridian Commercial Bank lacks a consolidated analytical view of transaction activity that enables management to assess transaction performance, understand customer and merchant behaviour, identify activity concentrations and investigate unusual transaction patterns.

Without structured analysis, management may overlook important customer segments, fail to recognise changes in transaction behaviour, misinterpret transaction performance or miss patterns that warrant further investigation.

The project will develop a reproducible analytical solution that transforms transaction-level data into meaningful performance indicators, visual insights and actionable management recommendations.

## 3. Project Goal

To develop an end-to-end banking transaction intelligence and performance analysis solution that demonstrates how transaction data can support business performance monitoring, customer intelligence, operational planning and risk investigation.

## 4. Project Objectives

The project will pursue five analytical objectives:

**Objective 1: Customer Behaviour Analysis**
- Analyse transaction frequency and value by customer.
- Identify customers contributing the highest transaction volumes and values.
- Examine customer activity concentration and behavioural patterns.
- Explore potential customer segmentation and engagement opportunities.

**Objective 2: Merchant Performance Analysis**
- Analyse transaction volumes and values across merchant categories.
- Identify categories with the highest transaction activity.
- Examine average transaction values and spending patterns.
- Identify potential merchant partnership and customer engagement opportunities.

**Objective 3: Temporal Analysis**
- Analyse transaction activity over the available time period.
- Identify peak transaction periods and changes in activity.
- Examine transaction value and volume trends.
- Identify patterns that may inform operational planning.

**Objective 4: Risk and Anomaly Analysis**
- Examine the distribution of the dataset's existing synthetic fraud labels.
- Investigate unusual transaction amounts and behavioural patterns.
- Examine fraud-label concentrations across customers and merchant categories.
- Identify patterns that may warrant further investigation.
- Distinguish unusual activity, model predictions and existing fraud labels.

**Objective 5: Transaction Concentration Analysis**
- Identify concentrations of transaction volumes and values across customers and merchant categories.
- Examine whether overall activity is disproportionately driven by particular segments.
- Assess potential business opportunities and concentration-related monitoring considerations.

Geographic comparison is excluded as a primary analytical objective because the selected dataset contains only one unique origin postcode and one unique merchant postcode.

## 5. Dataset and Data Source

**Selected dataset:** BankSim — Synthetic data from a financial payment system.

**Source:** Publicly available Kaggle dataset.

**Dataset characteristics established during initial inspection:**
- 594,643 transaction records.
- 10 columns.
- 4,112 unique customer identifiers.
- 50 unique merchant identifiers.
- 180 time-step values.
- 7,200 records labelled as fraudulent.

**Available fields:**
- step
- customer
- age
- gender
- zipcodeOri
- merchant
- zipMerchant
- category
- amount
- fraud

The data dictionary and field definitions will be documented and verified before analytical use.

## 6. Project Scope

### In Scope
- Dataset acquisition and documentation.
- Data profiling and quality assessment.
- Data cleaning and validation.
- SQL Server database development.
- SQL-based transaction analysis.
- Python-based exploratory and statistical analysis.
- Customer and merchant analysis.
- Transaction trends and concentration analysis.
- Anomaly investigation and synthetic fraud-label analysis.
- Power BI dashboard development.
- Management recommendations.
- Executive reporting and GitHub documentation.

### Out of Scope
- Analysis of actual bank customer accounts.
- Actual credit scoring or lending decisions.
- Confirming real-world fraudulent activity.
- Establishing money laundering or regulatory violations.
- Geographic expansion decisions based solely on this dataset.
- Actual bank profitability or customer lifetime value calculations.
- Building a production fraud detection or banking transaction processing system.

## 7. Technology and Tools

| Technology | Purpose |
|---|---|
| SQL Server / SSMS | Data storage, cleaning, validation and analytical queries |
| Python | Exploratory analysis, statistical analysis and anomaly investigation |
| Power BI | Interactive dashboard and business intelligence reporting |
| Excel | Supporting inspection and documentation where necessary |
| GitHub | Version control and portfolio presentation |

## 8. Key Stakeholders

The following are proposed stakeholders within the fictional client organisation.

| Stakeholder | Interest |
|---|---|
| Head of Data & BI | Analytical quality and business insights |
| Head of Risk Management | Unusual activity and potential risk indicators |
| Compliance / AML Team | Patterns requiring further review |
| Head of Marketing & Customer Experience | Customer behaviour and engagement opportunities |
| Head of Finance | Financial performance, subject to available financial data |
| Head of Operations | Transaction trends and operational demand |
| Head of Strategy & Business Development | Business opportunities and activity concentration |

## 9. Project Deliverables

1. Business problem definition and analytical objectives.
2. Dataset source documentation and data dictionary.
3. Data quality assessment and cleaning report.
4. SQL Server database with reproducible scripts.
5. Python analytical notebook.
6. Validated transaction KPIs and analytical findings.
7. Interactive Power BI dashboard.
8. Management recommendations.
9. Executive report and presentation.
10. Documented GitHub portfolio repository.

## 10. Five-Day Execution Plan

| Day | Main activity | Expected output |
|---|---|---|
| Day 1 | Business investigation and dataset assessment | Project charter, requirements and data dictionary |
| Day 2 | Data engineering and quality assessment | Clean, validated dataset and SQL database |
| Day 3 | Analytical investigation | SQL/Python analysis, KPIs and findings |
| Day 4 | Business intelligence development | Power BI dashboard and validation |
| Day 5 | Reporting and presentation | Executive report, recommendations and portfolio documentation |

## 11. Assumptions and Constraints

The following assumptions and constraints apply:

1. BankSim is synthetic data and does not represent actual banking operations or customers.
2. The dataset does not contain a transaction-status field distinguishing completed, reversed, cancelled and failed transactions.
3. Transaction records will be analysed as supplied; we will not assume that every record represents a successfully completed transaction.
4. The geographic fields contain only one unique postcode each, limiting geographic analysis.
5. The dataset contains an existing synthetic fraud label. This label will be treated as a reference classification, not independently verified evidence of real-world fraud.
6. No bank fee, revenue, operating cost or customer profitability fields have been established. Profitability and actual bank revenue contribution cannot therefore be calculated without additional data.
7. Age and gender fields are coded and require verification against the dataset documentation.
8. The meaning of the time-step field must be established before translating it into calendar dates or reporting periods.
9. Findings will be limited to what the available data can support.

## 12. Success Criteria

The project will be considered successful when:

- All five analytical objectives have been assessed against available data.
- Data-quality checks are documented and reproducible.
- SQL and Python analyses produce consistent, validated results where applicable.
- Key performance indicators have clear definitions and calculation logic.
- The Power BI dashboard communicates meaningful findings accurately.
- Recommendations are supported by evidence and acknowledge limitations.
- The final report clearly distinguishes observed findings, interpretations and recommendations.
- The project can be reproduced and reviewed through its GitHub documentation.

## 13. Project Risks

| Risk | Mitigation |
|---|---|
| Dataset limitations | Document exclusions and avoid unsupported conclusions |
| Incorrect field interpretation | Verify dataset documentation and test assumptions |
| Data-quality problems | Perform systematic validation before analysis |
| Misinterpretation of fraud labels | Separate labelled outcomes from anomaly indicators |
| Time constraints | Prioritise core analytical objectives and deliverables |
| Inconsistent calculations | Validate SQL and Python results against each other |

## 14. Project Governance and Reporting

The project will be executed as a simulated consulting engagement.

The project analyst is responsible for:
- Data acquisition and preparation.
- Analytical methodology.
- Quality assurance.
- Dashboard and report development.
- Documentation of assumptions and limitations.

The fictional management stakeholders will be represented through the business requirements and reporting outputs defined in this charter.

## 15. Project Approval

**Prepared by:** Project Analyst  
**Client:** Meridian Commercial Bank (Fictional)  
**Status:** Proposed project baseline

This charter establishes the agreed scope, objectives, deliverables, assumptions and execution plan for the Banking Transaction Intelligence & Performance Analysis project.
