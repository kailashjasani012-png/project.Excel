<div align="center">

# 📊 PR.1 — Fundamental Booster

### A Hands-On Excel Practice Project Covering Core-to-Intermediate Spreadsheet Skills

![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=for-the-badge&logo=googlesheets&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![Tasks](https://img.shields.io/badge/Tasks-22%2F22-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-Educational-blue?style=for-the-badge)

*A single workbook, three real-world datasets, twenty-two formulas mastered.*

</div>

---

## 📖 Table of Contents

- [About the Project](#-about-the-project)
- [Why This Project Exists](#-why-this-project-exists)
- [Workbook Structure](#️-workbook-structure)
- [Colour Legend](#-colour-legend)
- [Topics Covered](#-topics-covered)
- [Full Task Index](#-full-task-index-all-22-tasks)
- [Datasets Used](#-datasets-used)
- [How to Use](#-how-to-use)
- [Skills You'll Practice](#-skills-youll-practice)
- [Deliverable](#-deliverable)
- [Tech Notes](#-tech-notes)
- [Author](#-author)

---

## 📌 About the Project

**PR.1 Fundamental Booster** is a self-practice Excel workbook built to strengthen **core-to-intermediate spreadsheet skills** through real, working examples rather than dry theory. Instead of isolated exercises, every formula is applied directly to **realistic data** — student report cards, sales transactions, and employee records — so the learning sticks.

Each data sheet contains:
- 📥 A clean, raw dataset
- 🧩 A numbered set of **Task boxes** that mirror the project brief
- 🔁 Live, interactive input cells that let you test formulas by simply changing a value

The result is a workbook that behaves less like a worksheet and more like a **mini formula playground**.

---

## 🎯 Why This Project Exists

Spreadsheets are one of the most powerful — and most underused — analytical tools available. Most people only ever learn `SUM()` and `AVERAGE()`. This project pushes further, covering the formulas that separate a **casual Excel user** from someone who can confidently:

- Classify and score data with logic-based formulas
- Pull information across large datasets in milliseconds
- Build dynamic, self-updating dashboards and lookups
- Work fluently with dates, text, and conditional math

Every task was chosen because it reflects a **real workplace scenario** — grading systems, sales commissions, payroll dashboards — not abstract textbook problems.

---

## 🗂️ Workbook Structure

| Sheet | Emoji | Description |
|---|---|---|
| **Instructions** | 📘 | Project overview, colour legend, topics covered, and the full 22-task index |
| **Student_Data** | 🎓 | Grades, nested IFs, COUNTIFS/AVERAGEIFS, VLOOKUP, TEXT functions, FILTER |
| **Sales_Data** | 💼 | Discounts, SUMIFS, INDEX/MATCH, XLOOKUP, XMATCH, INDIRECT, OFFSET, ROUND/CEILING/FLOOR |
| **Employee_Data** | 🧑‍💼 | Dynamic lookups, date & age calculations, days-since-joining |

---

## 🎨 Colour Legend

A consistent colour system is used throughout the workbook so you always know what you're looking at:

| Style | Meaning |
|---|---|
| ⚫ **Black text** | Data or a completed example formula — study these closely |
| 🟡 **Blue text on yellow fill** | Input cell **you** should edit to test each formula live |
| *Italic grey notes* | The "modern Excel" equivalent (`XLOOKUP` / `XMATCH` / `FILTER`) shown as reference text, alongside a fully working, compatible formula already built into the file |

> 💡 **Tip:** Start by editing the yellow input cells first — watching the linked black formulas react is the fastest way to understand how each function actually works.

---

## 🧠 Topics Covered

- ✅ Relative & Absolute Cell References, Formatting, Data Input
- ✅ IF Formulas, Nested IFs, IF combined with AND / OR
- ✅ COUNTIFS, SUMIFS, AVERAGEIFS — conditional aggregation
- ✅ Lookup Functions — VLOOKUP, XLOOKUP\*, XMATCH\*
- ✅ INDEX/MATCH for flexible, dynamic searches
- ✅ TEXT Functions for string manipulation (LEFT, FIND, UPPER, LOWER)
- ✅ INDIRECT and OFFSET for dynamic cell references
- ✅ Date/Time functions, Math functions, and the FILTER\* function

> \* `XLOOKUP`, `XMATCH`, and `FILTER` are shown as reference/text formulas meant for Excel 365 or Google Sheets. A fully compatible `INDEX`/`MATCH`/`TEXTJOIN`-based equivalent is **already built and working** in this file, so it stays functional in any Excel version.

---

## 📋 Full Task Index (All 22 Tasks)

<details>
<summary><strong>Click to expand the complete task list</strong></summary>

| Task | Function(s) | Description | Sheet |
|---|---|---|---|
| 1 | `IF` | Classify students' grades based on their scores | Student_Data |
| 2 | `IF` | Compute discounts for sales based on price thresholds | Sales_Data |
| 3 | `IF(AND)` | Students scoring above 80 in both Math & Science | Student_Data |
| 4 | `IF(OR)` | Whether a product is eligible for discount | Sales_Data |
| 5 | `COUNTIFS` | Students who scored above 50 in Math | Student_Data |
| 6 | `SUMIFS` | Total sales for a specific region and product | Sales_Data |
| 7 | `AVERAGEIFS` | Average score for students who scored above 60 | Student_Data |
| 8 | `VLOOKUP` | Fetch student names based on ID from a separate dataset | Student_Data |
| 9 | `VLOOKUP` | Retrieve product prices based on product codes | Sales_Data |
| 10 | `INDEX`/`MATCH` | Sales value for a specific salesperson in a specific month | Sales_Data |
| 11 | `INDEX`/`MATCH` | Employee details dynamically, no column restriction | Employee_Data |
| 12 | `LEFT`/`FIND` | Extract first name from full names | Student_Data |
| 13 | `UPPER`/`LOWER` | Convert names to uppercase/lowercase | Student_Data |
| 14 | `XLOOKUP` | Salesperson performance, flexible search criteria | Sales_Data |
| 15 | `XLOOKUP` | Employee salaries without worrying about sorted data | Employee_Data |
| 16 | `XMATCH` | Position of a product in a sales list | Sales_Data |
| 17 | `INDIRECT` | Dynamically reference a cell range | Sales_Data |
| 18 | `OFFSET` | Create dynamic ranges for sales trends | Sales_Data |
| 19 | `DATE`/`DATEDIF` | Calculate age from date of birth | Employee_Data |
| 20 | `DATE` | Find the difference in days between two dates | Employee_Data |
| 21 | `ROUND`/`CEILING`/`FLOOR` | Financial calculations | Sales_Data |
| 22 | `FILTER` | Extract a list of top-performing students based on scores | Student_Data |

</details>

---

## 🗃️ Datasets Used

| Dataset | Records | Key Fields |
|---|---|---|
| 🎓 Student_Data | 10 students | ID, Name, Math, Science, Grade, First Name, Top Performer |
| 💼 Sales_Data | 15 transactions | SaleID, Salesperson, Region, Product, Price, Units Sold, Commission |
| 🧑‍💼 Employee_Data | 10 employees | EmpID, Name, Department, DOB, Date of Joining, Salary, Age |

All data is **fictional and used purely for practice purposes**.

---

## 🚀 How to Use

1. **📥 Download** the workbook — `PR1_Fundamental_Booster.xlsx`
2. **📂 Open** it in Microsoft Excel or Google Sheets
3. **📘 Read** the `Instructions` sheet first for the colour legend and task index
4. **🎯 Navigate** to each data sheet and locate the numbered Task boxes
5. **✏️ Edit** the blue/yellow input cells and watch the linked formulas update instantly
6. **🧪 Experiment** — try writing the "modern Excel" equivalents (`XLOOKUP`, `XMATCH`, `FILTER`) yourself in Excel 365 or Google Sheets

---

## 🧩 Skills You'll Practice

By working through this workbook, you'll build practical fluency in:

- 🔍 **Data lookups** — pulling exact information from large tables in seconds
- 🧮 **Conditional logic** — building formulas that think and branch
- 📊 **Aggregation** — summarizing data by multiple conditions at once
- ✂️ **Text manipulation** — cleaning and reshaping messy string data
- 📅 **Date arithmetic** — calculating ages, tenures, and date differences
- 🎛️ **Dynamic referencing** — building flexible, self-adjusting formulas

---

## ✅ Deliverable

Complete each worksheet by applying the required formulas in their respective sections. Validate your understanding by:

- Testing every interactive input cell
- Confirming that linked formulas update correctly
- Comparing your own attempts against the working examples provided

---

## ⚙️ Tech Notes

- 📄 File format: `.xlsx` (Excel 2007+)
- 🖥️ Compatible with Microsoft Excel and Google Sheets
- 🔄 Formulas prioritize **broad compatibility** (INDEX/MATCH-based) with modern equivalents (XLOOKUP/XMATCH/FILTER) noted for reference
- 🎨 Colour-coded cells make the workbook self-explanatory without extra documentation

---

## 👩‍💻 Author

<div align="center">

### **Yashvi Jasani**

*Excel Practice Project — PR.1 Fundamental Booster*

</div>

---

<p align="center">
Made with 💛 for Excel learners, one formula at a time.
</p>

<p align="center">
⭐ If this helped you, consider revisiting it whenever you need a formula refresher!
</p>
