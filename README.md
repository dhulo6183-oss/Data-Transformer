
---

# 🧬 SQL LAB: DATA STORY ENGINE

### *Turning raw tables into meaningful insights*

---

![SQL](https://img.shields.io/badge/SQL-MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)
![Steps](https://img.shields.io/badge/Steps-17-orange?style=for-the-badge)
![Author](https://img.shields.io/badge/Author-Dhruv%20Prajapati-blueviolet?style=for-the-badge)






## 🎯 What is this?

This is not just a SQL project.

This is a **data story system** where:

* 👤 Customers → People
* 🛒 Orders → Behavior
* 👨‍💼 Employees → Organization

And SQL is used as a **tool to uncover patterns**.

---
## ◈ Data Universe

```
┌─────────────────────────────────────────────────────┐
│                   THE DATA MODEL                    │
│                                                     │
│   ┌────────────┐         ┌────────────┐             │
│   │  customers │ ──────► │   orders   │             │
│   │            │  1 : N  │            │             │
│   │ • id       │         │ • id       │             │
│   │ • name     │         │ • cust_id  │             │
│   │ • email    │         │ • amount   │             │
│   └────────────┘         │ • date     │             │
│                          └────────────┘             │
│   ┌────────────┐                                    │
│   │  employees │  (standalone analytics)            │
│   │            │                                    │
│   │ • id       │                                    │
│   │ • name     │                                    │
│   │ • salary   │                                    │
│   │ • dept     │                                    │
│   └────────────┘                                    │
└─────────────────────────────────────────────────────┘
```

---









## 🧩 Data Model Snapshot

```
customers ─────┐
               ├──▶ orders
employees ─────┘
```

📌 Relationships:

* One customer → many orders
* Employees → independent analysis

---

# 🎥 VISUAL OUTPUT WALKTHROUGH

---

## 🟢 Step 1 — Raw Relationship View

👉 “Who ordered what?”

![Step1](sc1.png)

---

## 🔵 Step 2 — Inclusive Customer View

👉 “Show all customers (even silent ones)”

![Step2](sc2.png)

---

## 🔴 Step 3 — Order-Centric View

👉 “Every order must appear”

![Step3](sc3.png)

---

## 🟣 Step 4 — Complete Universe (FULL JOIN)

👉 “Nothing should be missed”

![Step4](sc4.png)

---

## 🟡 Step 5 — Smart Filtering

👉 “Who spends above average?”

![Step5](sc5.png)

---

## 🟠 Step 6 — Salary Intelligence

👉 “Who earns more than average?”

![Step6](sc6.png)

---

## 🟤 Step 7 — Time Breakdown

👉 “Understand data in time dimension”

![Step7](sc7.png)

---

## ⚫ Step 8 — Time Distance

👉 “How old is each order?”

![Step8](sc8.png)

---

## ⚪ Step 9 — Human Friendly Dates

👉 “Readable format”

![Step9](sc9.png)

---

## 🔷 Step 10 — Identity Building

👉 “Create full names”

![Step10](sc10.png)

---

## 🔶 Step 11 — Data Cleaning

👉 “Fix inconsistent values”

![Step11](sc11.png)

---

## 🔺 Step 12 — Case Conversion

👉 “Standardize format”

![Step12](sc12.png)

---

## 🔻 Step 13 — Remove Noise

👉 “Trim unwanted spaces”

![Step13](sc13.png)

---

## 🔳 Step 14 — Running Total

👉 “Track growth over time”

![Step14](sc14.png)

---

## 🔲 Step 15 — Ranking Engine

👉 “Top vs Bottom orders”

![Step15](sc15.png)

---

## 🟩 Step 16 — Business Logic

👉 “Apply discount rules”

![Step16](sc16.png)

---

## 🟥 Step 17 — Salary Classification

👉 “Segment employees”

![Step17](sc17.png)

---

# ⚙️ CORE SQL LOGIC (SIMPLIFIED)

---

## 🔗 Joins = Data Connection

* INNER → Only matches
* LEFT → Keep all customers
* RIGHT → Keep all orders
* FULL → Combine everything

---

## 🧠 Subqueries = Smart Filters

Used when:

* Comparing with average
* Dynamic conditions

---

## 🕒 Date Functions = Time Intelligence

* YEAR(), MONTH()
* DATEDIFF()
* DATE_FORMAT()

---

## 🔤 String Functions = Data Cleaning

* CONCAT → Merge text
* REPLACE → Fix values
* TRIM → Remove spaces
* UPPER/LOWER → Standardize

---

## 📊 Window Functions = Advanced Analytics

* Running Total
* Ranking

---

## 🧮 CASE = Decision Making

Used for:

* Discounts
* Salary category

---

# 🚀 WHY THIS PROJECT IS POWERFUL

This project shows:

✔ Real-world SQL thinking
✔ Data transformation skills
✔ Business logic implementation
✔ Analytical mindset

---

# 🧠 WHAT YOU LEARN

After this project you understand:

* How data is connected
* How to filter meaningful insights
* How to format raw data
* How to apply logic like real companies

---

## ◈ Skills You Walk Away With

```
After completing this project, you can:

  ✦  Connect multiple tables with the right JOIN for the job
  ✦  Write subqueries that dynamically filter with AVG / MAX / MIN
  ✦  Work with dates — extract, format, calculate distance
  ✦  Clean dirty data with TRIM, REPLACE, UPPER / LOWER
  ✦  Build window functions for running totals and rankings
  ✦  Encode business rules directly into SQL with CASE logic
  ✦  Think in terms of "what question does this query answer?"
```


## ◈ What Makes This Different

| Typical SQL Tutorial | This Project |
|----------------------|--------------|
| "Here's SELECT syntax" | "Here's a real business question" |
| Isolated examples | Connected 17-step narrative |
| Memorize functions | Understand when and why to use each |
| Just gets it working | Thinks about data quality & cleaning |
| No business context | Discounts, salary bands, rankings |

---





# 📁 DATA SOURCE

SQL file used:
📄 

---

# 🔥 FINAL NOTE

This is not just SQL practice.

This is:

> 💡 “From data → to decision → to understanding”

---
## 👨‍💻 Author
** Dhruv Prajapati **

![Made with SQL](https://img.shields.io/badge/Made%20with-SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Love](https://img.shields.io/badge/Made%20with-%E2%9D%A4-red?style=flat-square)

</div>




