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


## 🔄 Data Pipeline
1. SQL Server

The loan dataset was imported into Microsoft SQL Server as the source layer.

2. Power BI Dataflow

A Power BI Dataflow was created to provide a reusable cloud-based data preparation layer.

3. Power Query

The dataset was inspected and prepared using Power Query, including:

Data type validation
Data profiling
Column inspection
Data preparation
Dataset understanding
4. Power BI Desktop

The prepared data was imported from the Dataflow into Power BI Desktop.

The report was developed using:

Data modeling
DAX measures
Interactive visualizations
Filters and analytical segmentation
Time-based analysis
5. Power BI Service

The completed report was published to Power BI Service and configured with:

On-premises Data Gateway
Scheduled refresh
Incremental refresh
Report sharing

## 🏗️ End-to-End Architecture

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
