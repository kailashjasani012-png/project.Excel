<div align="center">

# 📊 DATA INTELLIGENCE DASHBOARD

### *Executive Sales Analytics, Pivot Tables, Advanced Excel Formulas & Business Intelligence*

[![Microsoft Excel](https://img.shields.io/badge/Microsoft%20Excel-2007%2B-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/microsoft-365/excel)
[![Dashboard](https://img.shields.io/badge/Dashboard-Executive%20KPI-1F4E78?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/microsoft-365/excel)
[![Pivot Tables](https://img.shields.io/badge/Pivot%20Tables-Summary%20Reports-4472C4?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/microsoft-365/excel)
[![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)]

<br/>

> *"Turn raw transactions into clear business insights with Excel."*

</div>

---

## 📋 Table of Contents

- [📌 Overview](#-overview)
- [🎯 Problem Statement](#-problem-statement)
- [✨ Key Features](#-key-features)
- [🏗️ Project Structure](#️-project-structure)
- [🔄 Project Workflow](#-project-workflow)
- [📊 Part A — Executive Dashboard](#-part-a--executive-dashboard)
- [📈 Part B — Pivot Tables & Summary Reports](#-part-b--pivot-tables--summary-reports)
- [🧮 Part C — Advanced Analysis & Formulas](#-part-c--advanced-analysis--formulas)
- [🗃️ Dataset Used](#️-dataset-used)
- [🛠️ Tech Stack](#️-tech-stack)
- [📈 Results & Insights](#-results--insights)
- [🏆 Advantages](#-advantages)
- [📄 License](#-license)
- [👤 Author](#-author)
- [🙏 Acknowledgements](#-acknowledgements)

---

## 📌 Overview

The **Data Intelligence Dashboard** is an Excel-based business analytics project designed to transform transaction-level sales data into an executive-friendly dashboard and structured analytical reports.

The workbook combines **KPI reporting, regional performance analysis, product analysis, pivot-style summaries, advanced Excel formulas, What-If scenario analysis, text functions, and regression analysis** in one integrated project.

The project contains four main worksheets:

- **Dashboard** — Executive KPI summary and visualizations
- **Final Project Dataset** — Raw transaction-level sales data
- **Pivot Tables** — Regional and product performance summaries
- **Analysis & Formulas** — Advanced Excel functions and business-rule implementations

---

## 🎯 Problem Statement

> **Objective:** Build an Excel-based data intelligence system that converts raw sales transactions into meaningful business reports and visual insights.

The workbook is designed to answer questions such as:

- What is the overall revenue?
- How many transactions were recorded?
- How many units were sold?
- How does sales performance vary by region?
- Which products contribute to sales volume and revenue?
- How can Excel formulas be used for advanced analysis?
- How can different discount scenarios be modelled?
- How can customer and transaction information be extracted dynamically?

| 📂 Feature | 📄 Type | 🔍 Description |
|------------|---------|----------------|
| Executive Dashboard | Visualization | KPI cards and sales charts |
| Regional Analysis | Summary | Transaction count, quantity and revenue by region |
| Product Analysis | Summary | Units sold and revenue by product |
| Advanced Formulas | Excel Analysis | Date, FILTER, text and lookup functions |
| What-If Analysis | Scenario Modelling | Discount-based scenario comparison |
| Regression Analysis | Statistical Analysis | Sales trend prediction using Regression ToolPak |

---

## ✨ Key Features

| Feature | Description |
|--------|-------------|
| 📊 **Executive Dashboard** | Presents key performance indicators and visual summaries |
| 💰 **Revenue KPI** | Calculates total transaction revenue |
| 🧾 **Transaction KPI** | Counts the total number of transactions |
| 📦 **Units Sold KPI** | Calculates total quantity sold |
| 🧮 **Average Order Value** | Calculates revenue per transaction |
| 🌍 **Regional Performance** | Summarizes sales activity across Central, East, North, South and West |
| 🛍️ **Product Performance** | Compares units sold and revenue across products |
| 🔎 **FILTER Analysis** | Dynamically extracts matching transaction records |
| 👥 **High-Value Customer Analysis** | Aggregates customer spending to identify high-value accounts |
| 🧪 **What-If Analysis** | Compares baseline, lower-discount and higher-discount scenarios |
| 📅 **Date & Time Functions** | Uses TODAY, NOW, DATEDIF and EOMONTH |
| 🔤 **Text Functions** | Demonstrates customer abbreviations and text-based analysis |
| 🔍 **Lookup / Matching** | Uses XLOOKUP / MATCH concepts for record matching |
| 📈 **Regression Analysis** | Uses Excel Data Analysis Regression ToolPak |

---

## 🏗️ Project Structure

```text
📦 Data-Intelligence-Dashboard/
│
├── 📄 Data_Intelligence_Dashboard_Final_Project_v3.xlsx
├── 📄 README.md
│
└── 📁 images/
    ├── 🖼️ dashboard.png
    ├── 🖼️ sales-dataset.png
    ├── 🖼️ pivot-tables.png
    └── 🖼️ advanced-analysis-formulas.png
```

---

## 🔄 Project Workflow

```text
Raw Transaction Data
        │
        ▼
┌─────────────────────────────┐
│ Final Project Dataset       │
│ 220 Transactions            │
└──────────────┬──────────────┘
               │
       ┌───────┴────────┐
       ▼                ▼
┌──────────────┐   ┌────────────────────┐
│ Pivot Tables │   │ Advanced Analysis  │
│ Regional &   │   │ Formulas &         │
│ Product Data │   │ Business Rules     │
└──────┬───────┘   └─────────┬──────────┘
       │                     │
       └──────────┬──────────┘
                  ▼
       ┌────────────────────────┐
       │ Executive Dashboard    │
       │ KPIs + Visualizations  │
       └────────────────────────┘
```

---

## 📊 Part A — Executive Dashboard

The **Dashboard** worksheet provides an executive-level view of the project with KPI indicators and visualizations.

### KPI Indicators

| KPI | Project Value |
|---|---:|
| 💰 Total Revenue | **$120,868.25** |
| 🧾 Total Transactions | **220** |
| 📦 Units Sold | **416** |
| 💵 Average Order Value | **≈ $549.40** |

### Dashboard Visualizations

- **Regional Sales Revenue** — compares revenue across regions
- **Revenue Share by Product Category** — visualizes product-level revenue contribution

### Dashboard Preview

![Executive Data Intelligence Dashboard](./images/dashboard.png)

---

## 📈 Part B — Pivot Tables & Summary Reports

The **Pivot Tables** worksheet contains structured summary reports for regional and product performance.

### Pivot Table 1 — Regional Performance & Sales Summary

The regional report includes:

- Region
- Transaction Count
- Total Quantity
- Total Revenue
- Average Order Value

Regions included:

- Central
- East
- North
- South
- West

### Pivot Table 2 — Product Category Performance

The product summary includes:

- Product Name
- Category
- Units Sold
- Total Revenue
- Revenue Share %

Products include:

- Ergonomic Keyboard
- External SSD 1TB
- Laptop Pro
- Noise-Canceling Headphones
- Smart Tablet
- USB-C Hub
- Ultra HD Monitor
- Wireless Mouse

### Pivot Tables Preview

![Pivot Tables and Summary Reports](./images/pivot-tables.png)

---

## 🧮 Part C — Advanced Analysis & Formulas

The **Analysis & Formulas** worksheet demonstrates advanced Excel functions and business rules.

### 1. Date & Time Functions

The project demonstrates:

- `TODAY()`
- `NOW()`
- `DATEDIF()`
- `EOMONTH()`

Example:

```excel
=EOMONTH(TODAY(),0)
```

This calculates the last day of the current month.

### 2. FILTER Function & High-Value Customers

The analysis includes:

- Dynamic `FILTER`-based extraction
- High-value customer aggregation
- Most frequently purchased product analysis

### 3. What-If Analysis & Scenario Manager

Three scenarios are included:

| Scenario | Discount Adjustment Rate |
|---|---:|
| Baseline Scenario | **8%** |
| Optimistic Scenario (Lower Discounts) | **3%** |
| Conservative Scenario (Higher Discounts) | **12%** |

The scenarios are used to compare projected revenue against the baseline.

### 4. Text Functions & Abbreviations

The worksheet also demonstrates:

- Customer abbreviation logic
- XLOOKUP / MATCH concepts
- Matching transaction information

### 5. Linear Regression

The project includes a **Data Analysis → Regression ToolPak** implementation for analysing sales trends over time periods.

### Advanced Analysis Preview

![Advanced Analysis, Formulas and Business Rules](./images/advanced-analysis-formulas.png)

---

## 🗃️ Dataset Used

The **Final Project Dataset** contains **220 transaction records**.

### Dataset Columns

| Column | Description |
|---|---|
| Transaction ID | Unique transaction identifier |
| Customer ID | Customer identifier |
| Customer Name | Customer name |
| Region | Sales region |
| Product Name | Product purchased |
| Category | Product category |
| Quantity | Units purchased |
| Unit Price | Price per unit |
| Discount % | Applied discount |
| Total Amount | Final transaction amount |
| Transaction Date | Date of transaction |
| Status | Transaction status |

### Dataset Preview

![Final Project Dataset](./images/sales-dataset.png)

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| 📊 **Microsoft Excel** | Main analytics and dashboard platform |
| 📋 **Excel Formulas** | Calculations and business rules |
| 🔎 **FILTER / XLOOKUP / MATCH** | Dynamic extraction and lookup analysis |
| 📅 **Date & Time Functions** | Date-based calculations |
| 🧪 **What-If Analysis** | Scenario modelling |
| 📈 **Regression ToolPak** | Statistical analysis and trend modelling |
| 📊 **Charts** | Data visualization |
| 📑 **Pivot-style Summary Tables** | Regional and product reporting |

---

## 📈 Results & Insights

After building the workbook, the project provides:

- ✅ **220 transaction records** for analysis
- 💰 **$120,868.25 total revenue**
- 📦 **416 total units sold**
- 🧾 **220 total transactions**
- 💵 **Approximately $549.40 average order value**
- 🌍 **Regional sales comparison**
- 🛍️ **Product-level performance analysis**
- 🔎 **Dynamic customer and transaction analysis**
- 🧪 **Three discount scenarios for What-If analysis**
- 📈 **Regression-based trend analysis**
- 📊 **Executive dashboard with charts and KPI indicators**

---

## 🏆 Advantages

| Advantage | Detail |
|-----------|--------|
| 🎓 **Practical Learning** | Combines multiple Excel concepts in one project |
| 📊 **Business Focused** | Converts raw transactions into management-friendly reports |
| 🔄 **Integrated Workbook** | Dataset, summaries, formulas and dashboard are connected |
| 🧮 **Advanced Excel Skills** | Covers formulas beyond basic SUM and AVERAGE |
| 🧪 **Scenario Modelling** | Helps demonstrate What-If analysis |
| 📈 **Visualization** | Uses charts to communicate sales information |
| 🔍 **Analytical Thinking** | Encourages customer, regional and product analysis |
| 📚 **Portfolio Ready** | Demonstrates practical Excel data-analysis skills |

---

## 📄 License

This project is created for **educational and practice purposes**.

The transaction data is used as a project dataset for Excel analysis and dashboard practice.

---

## 👤 Author

<div align="center">

### **Yashvi Jasani**

*Excel Data Analytics Project — Data Intelligence Dashboard*

**🎓 Role:** Data Analytics Learner | Excel Enthusiast  
**📍 Location:** India  
**🛠️ Skills:** Microsoft Excel · Dashboards · Data Analysis · Formulas · Pivot Tables · Data Visualization

</div>

---

## 🙏 Acknowledgements

This project was created as part of practical Excel and data analytics learning.

Special thanks to the learning resources and Excel community that support the development of skills in:

- 📊 Excel Dashboard Design
- 🧮 Advanced Excel Formulas
- 📑 Pivot Tables and Summary Reporting
- 🧪 What-If Analysis
- 📈 Data Visualization
- 📊 Statistical and Regression Analysis

---

<div align="center">

---

*Made with ❤️ for Excel learning and data analytics.*

</div>
