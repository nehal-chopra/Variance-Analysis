# Variance-Analysis

# 📊 Financial Variance Analysis — Bark & Barnacle (Q1 2024)

> ⚠️ **Disclaimer**: The company name **Bark & Barnacle** and all associated financial data in this repository are entirely **hypothetical** and created strictly for demonstration and project modeling purposes.

---

## 🏢 Business Context

Bark & Barnacle is a hypothetical suburban pet care store offering retail supplies, grooming services, and pet insurance facilitation. This project models Q1 2024 financial variance, tracking marketing campaign pushes, winter utility surges, and initial rebranding overheads.

---

## 🛠️ Data Architecture & Workbook Structure

The model (`variance analysis.xlsx`) integrates baseline projections with a transaction ledger across three key sheets:

| Sheet Name | Function | Focus Areas |
| --- | --- | --- |
| **`Dashboard`** | Dynamic Monthly Variance Reporting | Monthly Selector, Income & Expense Breakdown, Absolute ($) and Percentage (%) Variances. |
| **`Budget`** | Q1–Q4 Baseline Projections | Fixed monthly baseline targets ($16,500 Income / $17,700 Expenses). |
| **`Actual`** | Transactional General Ledger | Detailed itemized logs including dates, categories, descriptions, and transactional amounts. |

---
## Tool Used:
Microsoft Excel
>Dynamic Drop-Down in cell: Interactive feature which allows users to select month for which they would like to see variance analysis >(Actuals vs Budget).
>INDEX() function/formula
>MATCH() function/formula
>SUMIFS() function/formula
>Conditional Formatting: “Highlight Cell Rules” with custom formatting for easier understanding for business users to see data insights in this variance analysis data. * Dynamic and extendibility features: This model allows business users to add new data (data row in actual workbook) which will be inputted in the calculation automatically. This makes this model very dynamic, interactive, extendable and useful.
>Charts for Income Data: “Clustered Column Chart” with custom formatting – series, chart area, etc.
>Charts for Actual Expenses Data: “Pie Chart” with custom formatting – series, chart area, etc.

---
## 🧮 Calculation Logic & Formulas

* **Absolute Variance**: $\text{Actual} - \text{Budget}$
* **Percentage Variance**: $\frac{\text{Actual} - \text{Budget}}{\text{Budget}} \times 100$

> **Variance Interpretation**:
> * **Revenue Lines**: A positive outcome ($\text{Actual} > \text{Budget}$) represents a **Favorable** result (+).
> * **Expense Lines**: A positive outcome ($\text{Actual} > \text{Budget}$) represents an **Unfavorable** cost overrun (-).
> 
>
