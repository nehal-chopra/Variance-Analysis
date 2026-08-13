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
🧮 Excel Formulas & Core Analytical Functions
INDEX() & MATCH(): Used in tandem for dynamic, multi-criteria matrix lookups across monthly budget targets and dashboard summaries.

SUMIFS(): Evaluates general ledger entries to aggregate actual inflows and outflows by category and selected period.
---
⚙️ Interactive Features & Dynamic Automation
Dynamic Drop-Down Selection: Data validation list allowing business users to switch between months and instantly update all variance calculations (Actuals vs. Budget).

Automated Month Selection: Automatically sets the drop-down to the current active month upon opening for immediate executive visibility.

Dynamic Data Extendibility: Built with dynamic range references—adding new general ledger transaction rows into the Actual sheet automatically updates all dashboard calculations without modifying formulas.

Conditional Formatting: Customized "Highlight Cell Rules" visually flag favorable vs. unfavorable financial deviations for faster executive decision-making.

📉 Data Visualizations & Analytics
Income Analysis Chart: Custom-formatted Clustered Column Chart comparing budgeted revenue targets against actual earnings per category.

Actual Expenses Breakdown: Custom-styled Pie Chart mapping operational expenditure distribution to highlight primary cost drivers.

---
## 🧮 Calculation Logic & Formulas

* **Absolute Variance**: $\text{Actual} - \text{Budget}$
* **Percentage Variance**: $\frac{\text{Actual} - \text{Budget}}{\text{Budget}} \times 100$

> **Variance Interpretation**:
> * **Revenue Lines**: A positive outcome ($\text{Actual} > \text{Budget}$) represents a **Favorable** result (+).
> * **Expense Lines**: A positive outcome ($\text{Actual} > \text{Budget}$) represents an **Unfavorable** cost overrun (-).
> 
>
