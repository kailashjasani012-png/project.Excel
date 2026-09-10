 <div align="center">

# 📈 PR.2 — Sales Performance Analyzer

### An Advanced Excel Analytics Project — Dashboards, Statistics & Data-Driven Insights

![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=for-the-badge&logo=googlesheets&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![Sheets](https://img.shields.io/badge/Sheets-10-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-Educational-blue?style=for-the-badge)

*One workbook, 81 real-world sales transactions, a full analytics pipeline — from raw data to dashboard.*

</div>

---

## 📖 Table of Contents

- [About the Project](#-about-the-project)
- [Why This Project Exists](#-why-this-project-exists)
- [Workbook Structure](#️-workbook-structure)
- [Topics Covered](#-topics-covered)
- [Sheet-by-Sheet Breakdown](#-sheet-by-sheet-breakdown)
- [Dataset Used](#-dataset-used)
- [How to Use](#-how-to-use)
- [Skills You'll Practice](#-skills-youll-practice)
- [Deliverable](#-deliverable)
- [Tech Notes](#-tech-notes)
- [Author](#-author)

---

## 📌 About the Project

**PR.2 Sales Performance Analyzer** is a self-practice Excel workbook built to go beyond basic formulas and into **real analytical workflows** — the kind used in business reporting, sales analytics, and performance dashboards. Built on a single 81-row transactional sales dataset, the workbook layers on:

- 📊 A live **KPI Dashboard** summarizing the entire dataset
- 🧮 Statistical analysis (mean, median, mode, standard deviation, skewness, kurtosis, and more)
- 📉 A full **linear regression model** (Profit vs Sales) built with native formulas
- 🔮 A **What-If discount sensitivity analysis**
- 🧾 A formula-built **pivot-style cross-tab** (Region × Product)
- 🏆 Dynamic **Top-10 customer ranking** and **month-over-month growth tracking**

Every sheet pulls live from the same source data, so the whole workbook recalculates together — change one transaction and watch the dashboard, regression, and rankings all update.

---

## 🎯 Why This Project Exists

Formulas alone don't make an analyst — knowing how to **turn raw transactions into a decision-ready dashboard** does. This project was built to practice exactly that pipeline:

- Structuring raw transactional data for analysis
- Summarizing performance with SUMIFS/SUMIF-based aggregation
- Building statistical summaries without the Data Analysis Toolpak
- Running regression analysis using native functions (`SLOPE`, `INTERCEPT`, `CORREL`, `RSQ`, `STEYX`)
- Creating "what-if" models to test business scenarios
- Assembling everything into a single, self-updating executive dashboard

Every task mirrors a **real workplace scenario** — a sales manager's monthly report, not an abstract textbook exercise.

---

## 🗂️ Workbook Structure

| Sheet | Emoji | Description |
|---|---|---|
| **Dashboard** | 📊 | Executive KPI summary + auto-generated key insights |
| **Sales Data** | 🧾 | Raw transactional dataset (81 orders) driving the whole workbook |
| **Customer Summary** | 👥 | Total purchases & profit per customer (SUMIF) |
| **WHAT-IF Analysis** | 🔮 | Discount lever + sensitivity table (profit vs discount %) |
| **Regression Analysis** | 📉 | Linear regression: Profit vs Sales (R, R², slope, intercept) |
| **Descriptive Statistics** | 📐 | Full statistical summary of Sales & Profit |
| **Monthly Growth** | 📅 | Month-over-month sales trend and % growth |
| **High-Value Customers** | 🏆 | Top 10 customers ranked by total purchase |
| **Pivot Summary** | 🧮 | Region × Product cross-tab built with SUMIFS |
| **Charts** | 📈 | Visual charts built on the analysis sheets |

---

## 🧠 Topics Covered

- ✅ KPI Dashboards with linked, auto-updating summary cards
- ✅ `SUM`, `COUNT`, `AVERAGE` across large ranges
- ✅ `SUMIF` / `SUMIFS` — single & multi-condition aggregation
- ✅ `INDEX` / `MATCH` / `LARGE` for dynamic ranking
- ✅ `TEXT` for dynamic, narrative insight strings
- ✅ Descriptive Statistics — mean, median, mode, std. dev, variance, kurtosis, skewness
- ✅ Linear Regression — `SLOPE`, `INTERCEPT`, `CORREL`, `RSQ`, `STEYX`
- ✅ What-If / Sensitivity Analysis with a single input lever
- ✅ Formula-built Pivot Table equivalent (`SUMIFS` cross-tab)
- ✅ Date logic with `TEXT(date,"mmm-yy")` for month grouping
- ✅ `NOW()` for live timestamping

---

## 📋 Sheet-by-Sheet Breakdown

<details>
<summary><strong>Click to expand the full breakdown</strong></summary>

| Sheet | Key Formulas | What It Shows |
|---|---|---|
| Dashboard | `SUM`, `COUNT`, `AVERAGE`, `INDEX`/`MATCH`, `TEXT` | Total Sales, Total Profit, Total Orders, Average Discount, Top Customer + narrative insights |
| Sales Data | `*`, `TEXT`, `NOW` | Order-level Sales & Profit calculation from Quantity, Unit Price, Unit Cost & Discount |
| Customer Summary | `SUMIF` | Total purchase & profit per customer |
| WHAT-IF Analysis | `SUMPRODUCT` | Base sales/cost, adjustable discount lever, and a 7-point sensitivity table |
| Regression Analysis | `CORREL`, `RSQ`, `SLOPE`, `INTERCEPT`, `STEYX` | Full regression stats for Profit vs Sales |
| Descriptive Statistics | `AVERAGE`, `MEDIAN`, `MODE`, `STDEV`, `VAR`, `KURT`, `SKEW` | Complete statistical profile of Sales & Profit |
| Monthly Growth | `SUMIF`, growth % formula | Sales by month + month-over-month growth rate |
| High-Value Customers | `INDEX`/`MATCH`, `LARGE`, `COUNTIF` | Top 10 customers by purchase + count above average |
| Pivot Summary | `SUMIFS` | Sales cross-tabulated by Region and Product with grand totals |
| Charts | — | Visual representation of the above analyses |

</details>

---

## 🗃️ Dataset Used

| Dataset | Records | Key Fields |
|---|---|---|
| 🧾 Sales Data | 81 transactions | OrderID, CustomerName, Region, Product, OrderDate, Quantity, UnitPrice, UnitCost, Discount, Sales, Profit |

**Regions:** North, South, East, West
**Products:** Product A, Product B, Product C, Product D

All data is **fictional and used purely for practice purposes**.

---

## 🚀 How to Use

1. **📥 Download** the workbook — `PR2_Analyzer.xlsx`
2. **📂 Open** it in Microsoft Excel or Google Sheets
3. **📊 Start** on the `Dashboard` sheet for the executive summary
4. **🔍 Explore** each analysis sheet to see how the numbers are built
5. **🎛️ Try the lever** — change the discount value on `WHAT-IF Analysis` and watch profit recalculate
6. **✏️ Experiment** — edit a row in `Sales Data` and watch the Dashboard, Regression, Pivot Summary and rankings all update together

---

## 🧩 Skills You'll Practice

By working through this workbook, you'll build practical fluency in:

- 📊 **Dashboard building** — linking KPIs and insights back to raw data
- 🧮 **Multi-condition aggregation** — summarizing data by customer, region, product & month
- 📉 **Statistical analysis** — computing full descriptive statistics without add-ins
- 📈 **Regression modelling** — measuring correlation and predictive strength between variables
- 🔮 **Scenario/what-if modelling** — testing business decisions with a single input lever
- 🧾 **Pivot-style reporting** — building cross-tab summaries with pure formulas

---

## ✅ Deliverable

Complete each worksheet by tracing how the formulas connect the raw `Sales Data` sheet to every downstream analysis. Validate your understanding by:

- Verifying the Dashboard KPIs match the underlying data
- Testing the What-If discount lever and confirming the sensitivity table updates
- Comparing your own regression/statistics formulas against the working examples provided

---

## ⚙️ Tech Notes

- 📄 File format: `.xlsx` (Excel 2007+)
- 🖥️ Compatible with Microsoft Excel and Google Sheets
- 🔄 All analysis is built with native formulas — no Data Analysis Toolpak or add-ins required
- ⏱️ The `Timestamp` column in `Sales Data` uses `=NOW()` and updates on every recalculation
- 🎨 Every summary sheet stays linked live to the raw `Sales Data` sheet

---

## 👩‍💻 Author

<div align="center">

### **Yashvi Jasani**

*Excel Practice Project — PR.2 Sales Performance Analyzer*

</div>

---

<p align="center">
Made with 💛 for Excel learners, one formula at a time.
</p>

<p align="center">
⭐ If this helped you, consider revisiting it whenever you need an analytics refresher!
</p>
