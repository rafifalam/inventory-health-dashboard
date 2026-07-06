# 📦 Inventory Health Dashboard — Excel + Power Query

A complete supply chain analytics project that transforms a raw ERP export 
into a scored, classified, and decision-ready inventory management dashboard.

---

## 🗂️ Project Overview

| Detail | Value |
|---|---|
| Tool | Microsoft Excel + Power Query |
| Dataset | Simulated ERP Export |
| Products | 249 unique SKUs |
| Warehouses | 5 (North, South, East, West, Central) |
| Records | 10,708 rows |
| Total Inventory Value | $366.7M |

---

## 🎯 Business Problem

A distribution company managing 249 SKUs across five warehouses had no 
structured way to evaluate inventory health. Teams relied on manual 
judgement, leading to invisible dead stock, missed reorder points, and 
no single source of truth.

---

## ✅ Solution

Built an Inventory Health Dashboard in Excel that:
- Cleans and standardises raw ERP data using **16 Power Query steps**
- Calculates a **composite Inventory Health Score** (0–100) per product
- Classifies every SKU into an actionable category
- Surfaces financial risk through interactive KPIs and charts

---

## 🧮 Inventory Health Scoring Model

The score is a **weighted average of 4 sub-scores:**

| Sub-Score | Weight | What It Measures |
|---|---|---|
| Coverage Score | 40% | Months of stock vs. monthly demand |
| Risk Score | 30% | Physical stock availability |
| Profit Importance Score | 20% | Unit cost as financial risk proxy |
| Data Quality Score | 10% | Completeness of ERP record |

**Formula:**
### Classification Thresholds

| Score | Classification | Count | % of Total |
|---|---|---|---|
| ≥ 90 | ✅ Healthy | 5,671 | 56.4% |
| 75–89 | ⚠️ Reorder Soon | 3,768 | 35.2% |
| 50–74 | 🔴 At Risk | 1,144 | 10.7% |
| < 50 | 🚨 Critical | 20 | 0.2% |
| Special | 💀 Dead Stock | 105 | 1.0% |

---

## 🔍 Key Findings

- **$14.1M** in dead stock identified across 16 products
- **$29.4M** in at-risk inventory requiring urgent attention
- **3,768** products flagged for immediate reorder action
- **1,773 records** missing receipt dates — systemic ERP data gap
- **Top 3 products** (203, 189, 102) represent **$32.4M** — high concentration risk

---

## ⚙️ Power Query Transformations

16 documented steps including:
- Date format standardisation (3 mixed formats unified)
- Null-safe inventory value calculation
- Stock and cost flagging for missing data
- Left join merge of monthly demand table
- Conditional scoring columns for all 4 sub-score components

---

## 📊 Dashboard Features

- **6 KPI cards** — total value, healthy count, reorder count, at-risk count
- **Inventory classification chart** — portfolio health at a glance
- **Top products by value** — concentration risk view
- **Category breakdown** — value by product type
- **Interactive PivotTable** — filterable reorder and at-risk queue

---

## 🛠️ Skills Demonstrated

`Excel` `Power Query` `PivotTables` `Dashboard Design` `Data Cleaning`  
`Inventory Analytics` `Supply Chain Analysis` `ERP Data` `Business Analysis`

---

## 📁 Files

| File | Description |
|---|---|
| `Project_1_Inventory_Health_Dashboard.xlsx` | Full dashboard with raw data, Power Query, PivotTables, and dashboard |
| `Portfolio_Document.docx` | 21-page written portfolio explaining methodology and insights |

---

## 👤 Author

**Supply Chain Data Analyst**  
Open to freelance projects in inventory analytics, supply chain dashboards, 
and ERP data analysis.

📧 rafif.alam@gmail.com · 💼 https://www.linkedin.com/in/rafif-ul-alam-aa013348/?locale=en
