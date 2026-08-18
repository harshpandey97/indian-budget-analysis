<div align="center">

# 🇮🇳 Indian Union Budget Data Analysis

### Decoding how India taxes, spends, and borrows — one budget at a time

*A data analytics deep-dive into revenue mobilization, sector-wise expenditure, and fiscal health trends across Union Budgets*

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Wrangling-150458?style=flat-square&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![SQL](https://img.shields.io/badge/SQL-Querying-4479A1?style=flat-square&logo=postgresql&logoColor=white)](#)
[![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=flat-square&logo=powerbi&logoColor=black)](#)
[![Status](https://img.shields.io/badge/Status-In%20Progress-yellow?style=flat-square)](#-status)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](#-license)

</div>

---

## 📌 Why This Project

Every February, India's Finance Minister presents a budget spanning **tens of lakh crores of rupees** — yet most public conversation about it is headline-deep ("₹X lakh crore for defence!") with little structural analysis of *where the money actually comes from and where it actually goes*.

This project treats the Union Budget like a real analytics problem: multi-year, multi-ministry, inconsistently formatted government data that needs to be cleaned, modeled, and turned into a story a policymaker, journalist, or citizen could actually use.

> **Guiding question:** *Is India's spending pattern shifting — and is the deficit trend sustainable?*

---

## 🎯 Objectives

| # | Question | Analytical Approach |
|---|----------|---------------------|
| 1 | Which ministries/sectors get the biggest share — and how has that shifted over the years? | Sector-wise allocation trend analysis |
| 2 | How does revenue (tax vs. non-tax) stack up against total expenditure? | Revenue–expenditure gap analysis |
| 3 | Is the fiscal deficit trend improving or worsening relative to GDP? | Deficit-to-GDP time series |
| 4 | Where do Budget Estimates (BE) diverge most from Actuals? | BE vs. RE vs. Actuals variance analysis |
| 5 | Which sectors are structurally under/over-funded relative to their stated priority? | Cross-sector benchmarking |

---

## 🗂️ Repository Structure

```
indian-budget-analysis/
├── data/
│   ├── raw/              # Original, unmodified government/Kaggle budget data
│   └── processed/        # Cleaned, analysis-ready datasets
├── notebooks/            # Jupyter notebooks — cleaning, EDA, analysis
├── scripts/              # Reusable Python modules (cleaning & plotting utils)
├── reports/               # Final write-ups (PDF/Word executive summaries)
├── visuals/               # Exported charts & dashboard screenshots
├── requirements.txt
└── README.md
```

---

## 🛠️ Tech Stack

| Layer | Tools |
|-------|-------|
| **Data Wrangling** | Python — Pandas, NumPy |
| **Visualization (EDA)** | Matplotlib, Seaborn |
| **Querying** | SQL |
| **Dashboard** | Power BI / Excel |
| **Environment** | Jupyter Notebook |

---

## 🔍 Analysis Roadmap

- [ ] **Phase 1 — Data Sourcing & Cleaning**
  Standardize ministry names, unify units (₹ crore), reconcile BE/RE/Actuals across years
- [ ] **Phase 2 — Revenue vs. Expenditure EDA**
  Year-over-year trend charts, tax vs. non-tax revenue breakdown
- [ ] **Phase 3 — Sector-wise Allocation Analysis**
  Top ministries by share, fastest-growing/shrinking allocations
- [ ] **Phase 4 — Fiscal Deficit Deep-Dive**
  Deficit as % of GDP, revenue deficit vs. capital expenditure trend
- [ ] **Phase 5 — Interactive Dashboard**
  Power BI dashboard with year/ministry slicers for self-serve exploration
- [ ] **Phase 6 — Executive Summary Report**
  A policy-brief-style PDF summarizing key findings

---

## 📊 Sample Insight Preview

> *(To be populated as analysis progresses — this section will hold the headline chart + one-line takeaway, e.g.:)*
> **"Interest payments now consume ~20% of total expenditure — more than the combined allocation for Education and Health."**

---

## 📁 Data Source

Union Budget datasets sourced from public government/open-data repositories (e.g. [data.gov.in](https://data.gov.in), [Open Budgets India](https://openbudgetsindia.org), Kaggle Union Budget datasets). *Exact source(s) and citation will be pinned here once finalized.*

---

## 🚀 Status

🟡 **In Progress** — repository scaffolded, data sourcing and cleaning phase next.

---

## 👤 Author

**Harsh Pandey**
Data Analyst · BI Analyst · Aspiring AI Analyst

[![GitHub](https://img.shields.io/badge/GitHub-harshpandey97-181717?style=flat-square&logo=github)](https://github.com/harshpandey97)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

<div align="center">

*⭐ If this project helps you understand India's budget better, consider starring the repo!*

</div>
