<div align="center">

# 📈 PR.2 — Sales Performance Analyzer

### An Advanced Excel Analytics Project Covering Dashboards, Statistics & What-If Modelling

![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=for-the-badge&logo=googlesheets&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![Sheets](https://img.shields.io/badge/Sheets-10-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-Educational-blue?style=for-the-badge)

*One live dataset, one interactive dashboard, ten analytical sheets.*

</div>

---

## 📖 Table of Contents

- [About the Project](#-about-the-project)
- [Why This Project Exists](#-why-this-project-exists)
- [Workbook Structure](#️-workbook-structure)
- [Preview](#-preview)
- [Topics Covered](#-topics-covered)
- [Dashboard Highlights](#-dashboard-highlights)
- [Datasets Used](#-datasets-used)
- [How to Use](#-how-to-use)
- [Skills You'll Practice](#-skills-youll-practice)
- [Tech Notes](#-tech-notes)
- [Author](#-author)

---

## 📌 About the Project

**PR.2 Sales Performance Analyzer** is a self-practice Excel workbook built to move beyond individual formulas and into **full analytical workflows** — the kind used in real reporting and BI work. Starting from one raw sales transactions table, the workbook builds outward into a summary dashboard, a customer ranking system, a regression model, descriptive statistics, and a what-if simulator.

Each analytical sheet is **live-linked** back to the raw `Sales Data` sheet, so every number recalculates automatically as the underlying data changes.

---

## 🎯 Why This Project Exists

Where **PR.1** focused on mastering individual formulas, **PR.2** focuses on **combining them into a working analytics system** — the kind of workbook a business analyst would actually hand over to a manager:

- Summarize raw transactions into KPIs a leadership team can scan in seconds
- Rank and segment customers by value
- Model the statistical relationship between sales and profit
- Simulate "what-if" scenarios before making a pricing decision
- Track growth trends month over month

---

## 🗂️ Workbook Structure

| Sheet | Description |
|---|---|
| **Dashboard** | KPI summary — Total Sales, Total Profit, Total Orders, Average Discount, Top Customer |
| **Sales Data** | Raw transaction log — OrderID, Customer, Region, Product, Date, Quantity, Price, Cost, Discount, Sales, Profit |
| **Customer Summary** | Total purchase & profit per customer |
| **WHAT-IF Analysis** | Discount-impact simulation on total profit |
| **Regression Analysis** | Linear regression of Profit vs Sales (Multiple R, R², coefficients) |
| **Descriptive Statistics** | Mean, standard error, and other summary stats for Sales & Profit |
| **Monthly Growth** | Month-over-month sales totals and % growth |
| **High-Value Customers** | Top 10 customers ranked by total purchase, with region |
| **Pivot Summary** | Cross-tab of Total Sales by Region × Product (SUMIFS-based) |
| **Charts** | KPI visualizations — Sales by Region, Monthly Sales Trend |

---

## 🖼️ Preview

**Raw Sales Data** — the live transaction log every other sheet pulls from:

![Sales Data sheet](./sales-data-sheet.png)

**Pivot Summary** — Total Sales cross-tabbed by Region and Product:

![Pivot Summary sheet](./pivot-summary-sheet.png)

**Dashboard** — KPI cards, key insights, and charts in one view:

![Dashboard sheet](./dashboard-sheet.png)

---

## 🧠 Topics Covered

- ✅ KPI Dashboard design — Total Sales, Profit, Orders, Avg. Discount, Top Customer
- ✅ SUMIFS-based Pivot-style cross-tabulation (Region × Product)
- ✅ Customer segmentation & ranking (Top/High-Value Customers)
- ✅ Descriptive Statistics — Mean, Standard Error, and more
- ✅ Linear Regression — Profit vs Sales, with Multiple R and R²
- ✅ WHAT-IF discount-impact modelling
- ✅ Month-over-month growth calculations
- ✅ Chart building — bar chart (Sales by Region), trend line (Monthly Sales)
- ✅ Live `=NOW()` timestamping for recalculation tracking

---

## 📊 Dashboard Highlights

| KPI | Value |
|---|---|
| Total Sales | $1,20,894 |
| Total Profit | $49,078 |
| Total Orders | 81 |
| Average Discount | 9.6% |
| Top Customer | Sanjay Desai |
| Strongest Region | South ($53,850) |
| Best Month | May-26 ($26,702) |
| Sales–Profit Correlation (R) | 0.99 |

---

## 🗃️ Datasets Used

| Dataset | Records | Key Fields |
|---|---|---|
| 💼 Sales Data | 81 transactions | OrderID, CustomerName, Region, Product, OrderDate, Quantity, UnitPrice, UnitCost, Discount, Sales, Profit, MonthLabel |

All data is **fictional and used purely for practice purposes**.

---

## 🚀 How to Use

1. **📥 Download** the workbook — `PR2_Analyzer.xlsx`
2. **📂 Open** it in Microsoft Excel or Google Sheets
3. **📊 Start** at the `Dashboard` sheet for the KPI overview
4. **🔎 Explore** each analytical sheet — Customer Summary, Regression, Descriptive Statistics, Monthly Growth, High-Value Customers, Pivot Summary
5. **🧪 Try** the `WHAT-IF Analysis` sheet to see how changing discounts affects total profit
6. **📈 Check** the `Charts` sheet for the visual summary

---

## 🧩 Skills You'll Practice

- 📊 **Dashboard building** — turning raw rows into scannable KPIs
- 🧮 **SUMIFS pivoting** — cross-tab summaries without the PivotTable UI
- 📉 **Statistical analysis** — regression, mean, standard error
- 🔮 **Scenario modelling** — WHAT-IF discount simulations
- 🏆 **Ranking & segmentation** — top and high-value customer lists
- 📅 **Trend analysis** — month-over-month growth tracking
- 📈 **Chart design** — bar and trend-line visualizations

---

## ⚙️ Tech Notes

- 📄 File format: `.xlsx` (Excel 2007+)
- 🖥️ Compatible with Microsoft Excel and Google Sheets
- 🔄 All analytical sheets are formula-linked to `Sales Data`, so edits there flow through everywhere
- ⏱️ `Timestamp` column uses `=NOW()` and updates on every recalculation

---

## 👩‍💻 Author

<div align="center">

### **Yashvi Jasani**

*Excel Practice Project — PR.2 Sales Performance Analyzer*

</div>

---

<p align="center">
Made with 💛 for Excel learners, one dashboard at a time.
</p>

<p align="center">
⭐ If this helped you, consider revisiting it whenever you need an analytics refresher!
</p>
