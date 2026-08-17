# 📊 Loan Default & Financial Risk Analytics

End-to-end Data Analytics project using SQL Server, Power BI Dataflows, Power Query, DAX and Power BI Service to analyze loan portfolio performance, borrower demographics and financial risk


## 🎯 Business Problem

A financial organization needs to understand its loan portfolio, borrower characteristics and potential financial risk.

The objective of this project was to build an interactive analytics solution that answers questions around:

- Loan portfolio performance
- Default behavior
- Borrower demographics
- Credit-score segments
- Employment and education
- Loan purpose
- Mortgage and dependent status
- Year-over-Year performance
- Year-to-Date loan exposure

The solution was developed as an **end-to-end BI workflow**, from data ingestion and preparation to analysis, visualization, validation and deployment.

---
# 📊 Loan Default & Financial Risk Analytics

> **End-to-end Data Analytics project using SQL Server, Power BI Dataflows, Power Query, DAX and Power BI Service to analyze loan portfolio performance, borrower demographics and financial risk.**

---

## 🎯 Business Problem

A financial organization needs to understand its loan portfolio, borrower characteristics and potential financial risk.

The objective of this project was to build an interactive analytics solution that answers questions around:

- Loan portfolio performance
- Default behavior
- Borrower demographics
- Credit-score segments
- Employment and education
- Loan purpose
- Mortgage and dependent status
- Year-over-Year performance
- Year-to-Date loan exposure

The solution was developed as an **end-to-end BI workflow**, from data ingestion and preparation to analysis, visualization, validation and deployment.

## 🏗️ End-to-End Architecture

SQL Server
    ↓
Power BI Dataflow
    ↓
Power Query
    ↓
Data Profiling & Transformation
    ↓
Power BI Data Model
    ↓
DAX Measures & Analysis
    ↓
Interactive Power BI Report
    ↓
Power BI Service
    ↓
Scheduled Refresh + Incremental Refresh

---

---
📥 Data Pipeline
1. SQL Server

The loan dataset was imported into Microsoft SQL Server as the source layer.

2. Power BI Dataflow

Created a Power BI Dataflow to provide a reusable cloud-based data preparation layer.

3. Power Query

Performed:

Data type validation
Data profiling
Column inspection
Data preparation
Dataset understanding
4. Power BI Desktop

Imported the prepared data from the Dataflow and developed the analytical report using DAX and interactive visualizations.

5. Power BI Service

Published the report and configured:

Gateway
Scheduled refresh
Incremental refresh
Report sharing

---

---
📊 Dashboard
1. Loan Default Overview

Provides a high-level view of the loan portfolio.

Analysis included:
Loan Amount by Purpose
Average Income by Employment Type
Average Loan Amount by Age Group
Average Income by Education
Average Loan Amount by Purpose
Average Income by Age Group

2. Applicant Demographics & Financial Profile

Analyzes how borrower characteristics relate to loan exposure.

Analysis included:
Median Loan Amount by Credit Score Category
Average Loan Amount by Age Group & Marital Status
Total Adult Loan Amount by Credit Score
Middle-Age Adult Loans by Mortgage / Dependents
Number of Loans by Education Type

3. Financial Risk Metrics

Provides deeper financial and time-based analysis.

Analysis included:
YoY Loan Amount Change by Year
YoY Loan Amount Change by Age Group
YoY Loan Amount Change by Credit Score & Marital Status
YTD Loan Amount
Decomposition Tree analysis
---

---
## DAX concepts applied

CALCULATE
SUM
SUMX
AVERAGE
AVERAGEX
MEDIANX
FILTER
ALL
ALLEXCEPT
COUNTROWS
DIVIDE
VALUES
SWITCH
ISBLANK
NOT
---

## 🔄 Power BI Service & Refresh

The project was published to Power BI Service and configured for repeatable reporting.

Implemented:
On-premises Data Gateway
Dataflow Scheduled Refresh
Incremental Refresh
Report Publishing
Report Sharing

## 📈 Business Value

The dashboard enables stakeholders to:

Monitor overall loan portfolio performance
Identify borrower segments with different loan exposure
Track default-related trends
Compare financial performance across time
Investigate loan exposure through credit and demographic dimensions
Drill into contributing factors using decomposition analysis
Monitor reporting metrics through Power BI Service


## End-to-End Workflow

This project demonstrates the complete journey from raw data to a business-ready analytics solution:

             RAW DATA
                 │
                 ▼
           SQL SERVER
                 │
                 ▼
        POWER BI DATAFLOW
                 │
                 ▼
          POWER QUERY
                 │
       Data Profiling
       Data Preparation
                 │
                 ▼
        POWER BI MODEL
                 │
                 ▼
          DAX ANALYSIS
                 │
       ┌─────────┼─────────┐
       ▼         ▼         ▼
   Portfolio  Applicant   Risk
    Analysis  Analysis  Analysis
       │         │         │
       └─────────┼─────────┘
                 ▼
          POWER BI REPORT
                 │
                 ▼
          POWER BI SERVICE
                 │
       ┌─────────┴─────────┐
       ▼                   ▼
Scheduled Refresh    Incremental Refresh
