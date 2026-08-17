# 📊 Loan Default & Financial Risk Analytics

End-to-end Data Analytics project using SQL Server, Power BI Dataflows, Power Query, DAX and Power BI Service to analyze loan portfolio performance, borrower demographics and financial risk.

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
```text
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

## End-to-End Workflow
```text

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
