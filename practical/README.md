<div align="center">

# -- ! Sales Performance Analysis — Excel Dashboard ! --
### *Interactive Excel Dashboard for Sales, Profit & Discount Analysis*

[![Excel](https://img.shields.io/badge/Excel-2019%2B-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)](https://www.microsoft.com/excel)
[![Formulas](https://img.shields.io/badge/Formulas-SUMIFS%2FVLOOKUP%2FINDEX--MATCH-FF6F00?style=for-the-badge&logo=microsoftexcel&logoColor=white)](https://www.microsoft.com/excel)
[![Dashboard](https://img.shields.io/badge/Dashboard-Interactive%20KPI%20%26%20Charts-4CAF50?style=for-the-badge&logo=googleanalytics&logoColor=white)](https://www.microsoft.com/excel)
[![Data](https://img.shields.io/badge/Dataset-10%2C000%20Orders-9C27B0?style=for-the-badge&logo=databricks&logoColor=white)](https://www.microsoft.com/excel)

<br/>

> *"A dashboard is only as good as the formulas quietly working underneath it."*

</div>

---

## 📋 Table of Contents

- [📌 Overview](#-overview)
- [🎯 Problem Statement](#-problem-statement)
- [✨ Key Features](#-key-features)
- [🏗️ Workbook Structure](#️-workbook-structure)
- [🔄 Project Workflow](#-project-workflow)
- [📄 Sheet-by-Sheet Guide](#-sheet-by-sheet-guide)
- [🔎 Lookup Tool — Advanced Formulas](#-lookup-tool--advanced-formulas)
- [🎨 Naming & Colour Conventions](#-naming--colour-conventions)
- [🧮 Assumptions & Notes](#-assumptions--notes)
- [🛠️ Tech Stack](#️-tech-stack)
- [📈 Results & Insights](#-results--insights)
- [🏆 Advantages](#-advantages)
- [📄 License](#-license)
- [👤 Author](#-author)
- [🙏 Acknowledgements](#-acknowledgements)

---

## 📌 Overview

The **Sales Performance Analysis — Excel Dashboard** is an end-to-end Excel project built on a **10,000-row sales dataset** spanning **January 2022 to December 2025**. It takes raw, unclean order data and turns it into a fully interactive dashboard with live KPIs, filterable charts, and a lookup tool — all powered by native Excel formulas, with **zero hardcoded results**.

This project is designed to:
- Demonstrate a real analyst workflow: import → clean → summarize → visualize → interact
- Practice formula-driven summary tables using `SUMIFS`, `COUNTIFS`, and `AVERAGEIFS`
- Apply advanced lookups (`VLOOKUP`, `INDEX`/`MATCH`) with error handling
- Build a dashboard that stays fast even as filters change, by never touching the raw 10,000-row range directly

---

## 🎯 Problem Statement

> **Objective:** Turn a raw, 10,000-row sales export into a self-service dashboard that any stakeholder can filter without touching a formula.

Starting from a CSV export with text-formatted dates, the workbook needs to be cleaned, enriched with calculated fields (margin, discount tier, year/month), summarized into pivot-style tables, and finally surfaced through an interactive dashboard with KPI cards, charts, and dropdown filters.

| 📂 Feature | 📄 Type | 🔍 Description |
|------------|---------|----------------|
| Data Cleaning | Preparation | Fixes text dates, checks duplicates/blanks, adds calculated columns |
| Pivot Summaries | Analysis | Seven SUMIFS/COUNTIFS-driven tables by Category, Region, Segment, etc. |
| Lookup Tool | Advanced Formula | VLOOKUP + INDEX/MATCH order lookup with risk classification |
| Interactive Dashboard | Visualization | KPI cards, 7 charts, Region/Category/Year filters |

The goal is to demonstrate **practical Excel analytics skills** — cleaning, formula design, and dashboarding — on a realistic sales dataset.

---

## ✨ Key Features

| Feature | Description |
|--------|-------------|
| 🔁 **Live Filtering** | Region / Category / Year dropdowns instantly update every KPI, table, and chart |
| 📊 **7 Interactive Charts** | All charts point at small Pivot_Summary tables, not the raw data range |
| 🔢 **4 KPI Cards** | Total Sales, Total Profit, Total Orders, and Average Discount |
| 🔍 **Order Lookup Card** | Type any Order ID to pull back the full record via VLOOKUP + INDEX/MATCH |
| ⚠️ **Risk Classification** | Nested IF/IFERROR logic flags margin & discount risk per order |
| 🧹 **Auditable Cleaning** | Explicit duplicate/blank check cells, not just an assumed clean dataset |
| 🎨 **Colour-Coded Cells** | Header and formula colours instantly show what's data vs. input vs. calculation |
| ⚡ **Fast Recalculation** | Filtering only recalculates the Dashboard sheet's ~30 light formulas, never the full workbook |

---

## 🏗️ Workbook Structure

```
📦 Sales_ExcelDashboard.xlsx/
│
├── 📄 README            ← Project scope, sheet guide, conventions, assumptions
├── 📄 Raw_Data           ← Dataset exactly as imported (untouched, for audit)
├── 📄 Cleaned_Data       ← Typed, cleaned table + 6 calculated columns
├── 📄 Pivot_Summary      ← 7 formula-driven summary tables
├── 📄 Lookup_Tool        ← Order ID lookup card with risk flags
└── 📄 Dashboard          ← KPI cards, filters, charts, conditional formatting
```

---

## 🔄 Project Workflow

```
Raw CSV Import
      │
      ▼
┌─────────────────────────────┐
│        Raw_Data sheet       │  ← Untouched source, for traceability
└────────────┬────────────────┘
             │
             ▼
┌─────────────────────────────┐
│       Cleaned_Data sheet    │  ← Real dates, duplicate/blank checks,
│                              │     + Profit Margin, Margin Level,
│                              │     Discount Tier, Year/Month columns
└────────────┬────────────────┘
             │
             ▼
┌─────────────────────────────┐
│      Pivot_Summary sheet    │  ← 7 SUMIFS/COUNTIFS/AVERAGEIFS tables
└──────┬───────────────┬──────┘
       │                │
       ▼                ▼
┌──────────────┐  ┌─────────────────────┐
│ Lookup_Tool  │  │   Dashboard sheet   │
│ (Order ID    │  │  KPI cards + filters │
│  VLOOKUP)    │  │  + 7 live charts     │
└──────────────┘  └─────────────────────┘
```

---

## 📄 Sheet-by-Sheet Guide

| Sheet | Purpose |
|-------|---------|
| **README** | This overview — project scope, sheet guide, naming conventions, assumptions |
| **Raw_Data** | Dataset exactly as imported from the source CSV — untouched, for audit/traceability |
| **Cleaned_Data** | Cleaned, typed table with real date fields, verified duplicates/blanks, plus 6 calculated columns (Profit Margin, Margin Level, Discount Tier, Order Year, Order Month, Order YearMonth) used everywhere else in the workbook |
| **Pivot_Summary** | Seven formula-driven summary tables (by Category, Region, Segment, Sub-Category, Month, Margin Level, and Discount Tier) built with `SUMIFS` / `COUNTIFS` / `AVERAGEIFS` — the analytical core behind every chart on the Dashboard |
| **Lookup_Tool** | A live lookup card — type any Order ID and `VLOOKUP` + `INDEX`/`MATCH` pull back the full order record; nested `IF`/`IFERROR` classify margin and discount risk |
| **Dashboard** | The interactive dashboard — KPI cards, Region/Category/Year filters, 7 charts, and conditional formatting, all recalculating live from your filter choices |

**Sample Dashboard KPIs (unfiltered, all 10,000 orders):**

| KPI | Value |
|-----|-------|
| 💰 Total Sales | ₹421,665,154.26 |
| 📈 Total Profit | ₹101,690,067.29 |
| 📦 Total Orders | 10,000 |
| 🏷️ Avg. Discount | 12.51% |

---

## 🔎 Lookup Tool — Advanced Formulas

> A single input box drives a full order lookup, with built-in error handling.

**Logic:**
```excel
=VLOOKUP(OrderID, CleanedData, column_index, FALSE)
=INDEX(CleanedData[Profit], MATCH(OrderID, CleanedData[Order ID], 0))
=IFERROR(IF(Margin>=0.3, "High", IF(Margin>=0.2, "Medium", "Low")), "Order not found")
```

**Key Concepts Used:**

| Concept | Detail |
|---------|--------|
| 🔍 `VLOOKUP` | Pulls back the full order record by Order ID |
| 🎯 `INDEX` / `MATCH` | Flexible lookup used alongside VLOOKUP for specific fields |
| 🧠 Nested `IF` | Classifies Margin Level and Discount Tier |
| ⚠️ `IFERROR` | Gracefully handles an Order ID that doesn't exist |

---

## 🎨 Naming & Colour Conventions

| Category | Convention |
|----------|-----------|
| Sheet tabs | `Title_Case_With_Underscores` (e.g. `Cleaned_Data`) so tab names stay short and formula-safe |
| Table objects | Each sheet's main range is a native Excel Table (`Ctrl+T`) — `RawData`, `CleanedData`, `LookupData` — so filters, banding, and structured references work out of the box |
| Header colour | Navy = source/base data · Teal = calculated/summary · Orange = interactive controls & KPIs |
| Formula colour | Black = calculation · Blue = an input cell you're meant to change (dropdowns, Order ID box) |

---

## 🧮 Assumptions & Notes

- Source file had 0 blank cells and 0 duplicate Order IDs on inspection — `Cleaned_Data` still carries an explicit duplicate/blank check so the cleaning step is visible and auditable, not just assumed.
- Dates arrived as text in `DD-MM-YYYY` format; `Cleaned_Data` converts both date columns to true Excel date values so `YEAR()`/`MONTH()` and date sorting work correctly.
- **Profit Margin** = Profit / Sales. **Margin Level:** High ≥ 30%, Medium 20–30%, Low < 20% (thresholds chosen from the dataset's own quartiles).
- **Discount Tier:** None = 0%, Low ≤ 10%, Medium ≤ 20%, High > 20%.
- Slicers & a Timeline can be added natively via Excel's Insert menu (click inside the `CleanedData` table → Insert → Slicer/Timeline) — the Dashboard sheet already achieves the same live-filtering effect with dropdowns wired to SUMIFS/COUNTIFS.
- All figures are formulas, not hard-typed numbers — change any row in `Cleaned_Data` and every table, KPI, and chart in the workbook updates.

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| 📊 **Microsoft Excel** | Core platform for the entire workbook |
| 🧮 **SUMIFS / COUNTIFS / AVERAGEIFS** | Formula-driven pivot summary tables |
| 🔍 **VLOOKUP / INDEX / MATCH** | Order lookup and record retrieval |
| 🧠 **Nested IF / IFERROR** | Margin and discount risk classification |
| 📈 **Native Excel Charts** | 7 charts tied to summary tables, not raw data |
| 🎛️ **Dropdown Filters + Conditional Formatting** | Interactive, self-service dashboard controls |

---

## 📈 Results & Insights

After opening the dashboard and applying filters, the workbook delivers:

- ✅ **4 Live KPI Cards** — Total Sales, Total Profit, Total Orders, Avg. Discount, all recalculating instantly
- 📊 **7 Interactive Charts** — driven by lightweight Pivot_Summary tables for speed
- 🔍 **Instant Order Lookup** — full record retrieval and risk classification from a single Order ID
- 🧹 **Traceable Cleaning** — every transformation from Raw_Data to Cleaned_Data is visible and checkable
- ⚡ **Fast Filtering** — changing a filter recalculates only the Dashboard sheet, not the whole workbook

---

## 🏆 Advantages

| Advantage | Detail |
|-----------|--------|
| 🎓 **End-to-End Workflow** | Covers import, cleaning, pivoting, lookups, and dashboarding in one file |
| ⚡ **Performance-Conscious Design** | Charts never reference the raw 10,000-row range directly |
| 📚 **Educational** | Demonstrates formula-driven analysis without a single hardcoded number |
| 🖥️ **No Add-ins Needed** | Runs in stock Excel — no external tools or plugins required |
| 🧪 **Extensible** | Easy to add native Slicers/Timeline or extra Pivot_Summary breakdowns |
| 📖 **Auditable** | Colour-coded formulas and an explicit duplicate/blank check keep the logic transparent |
| 🛡️ **Error-Safe Lookups** | IFERROR ensures a missing Order ID never breaks the sheet |

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for full details.

```
MIT License — Free to use, modify, and distribute with attribution.
```

---

## 👤 Author

<div align="center">

### Yashvi Jasani

> *"Every dashboard starts with clean data — and every insight starts with a clear formula."*

**🎓 Role:** Data Analyst | Excel Enthusiast \
**📍 Location:** India \
**🛠️ Skills:** Excel · SUMIFS/COUNTIFS · VLOOKUP/INDEX-MATCH · Dashboard Design · Data Cleaning

</div>

---

## 🙏 Acknowledgements

Special thanks to the following resources that made this project possible:

- 📚 [Microsoft Excel Support](https://support.microsoft.com/excel) — Official Excel function reference
- 🔁 [ExcelJet](https://exceljet.net/) — Formula patterns and lookup techniques
- 📐 [Chandoo.org](https://chandoo.org/) — Dashboard design inspiration
- 🧮 [Exceljet — SUMIFS Guide](https://exceljet.net/functions/sumifs-function) — Multi-criteria summing reference
- 💬 [Stack Overflow Community](https://stackoverflow.com/) — Problem-solving support

---

<div align="center">

---

*Made with 📊 and ☕ — Last updated: 17 September, 2026*

</div>
