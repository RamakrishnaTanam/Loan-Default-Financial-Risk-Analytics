# 📋 Business Requirements

## Project: Loan Default & Financial Risk Analytics

### 1. Business Objective

The objective of this project is to analyze loan portfolio data and provide stakeholders with insights into loan amounts, borrower characteristics, default behavior and financial risk.

The solution should enable users to explore loan performance across different borrower and financial attributes and identify patterns that can support data-driven decision-making.

---

## 2. Business Questions

The analysis focuses on the following key questions:

### Loan Portfolio Analysis

1. What is the total loan amount across different loan purposes?
2. How does the average loan amount vary across different age groups?
3. How does loan exposure differ across credit-score categories?
4. How does loan amount vary across borrower demographics?

### Borrower Analysis

5. How does average income vary by employment type?
6. How does average income vary across education levels?
7. How does loan amount differ by age group and marital status?
8. How do mortgage and dependent status relate to loan exposure?
9. How does the number of loans vary by education type?

### Default & Risk Analysis

10. What is the default rate by employment type?
11. How does the default rate change across years?
12. How does loan performance vary across credit-score segments?
13. Which borrower segments contribute to higher loan exposure?

### Time-Based Analysis

14. How has loan amount changed year over year?
15. How has default-related performance changed year over year?
16. What is the Year-to-Date (YTD) loan amount?
17. How do loan trends vary across different borrower segments?

---
# 3. Data Preparation Requirements

Before analysis, the dataset was reviewed and prepared using Power Query.

The preparation workflow included:

- Reviewing column definitions
- Inspecting dataset structure
- Data profiling
- Validating data types
- Preparing fields for analysis
- Ensuring analytical fields were available for Power BI reporting

---

# 4. Data Pipeline Requirements

The project uses an end-to-end BI workflow:

```text
SQL Server
    ↓
Power BI Dataflow
    ↓
Power BI Desktop
    ↓
Power Query
    ↓
DAX Measures
    ↓
Power BI Report
    ↓
Power BI Service