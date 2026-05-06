# 🚲 Bike Sales Analysis — Excel Data Analytics Project

**Tool:** Microsoft Excel &nbsp;|&nbsp; **Type:** Walkthrough Project &nbsp;|&nbsp; **Domain:** Consumer & Retail Analytics

---

## 📌 Project Overview

This project analyzes a dataset of **1,026 customers** across North America, Europe, and the Pacific to identify the key demographic and behavioral factors that drive bike purchase decisions.

The goal mirrors a real consulting brief: *given customer-level data, which segments are most likely to convert — and what does that mean for targeting strategy?*

The full workflow covers **data cleaning → feature engineering → pivot table analysis → interactive dashboard** — built entirely in Excel.

---

## 🗂️ Dataset

| Field | Description |
|---|---|
| **Records** | 1,026 customers |
| **Variables** | 14 (demographic, financial, behavioral) |
| **Target Variable** | Purchased Bike (Yes / No) |
| **Key Features** | Income, Age, Commute Distance, Occupation, Region, Marital Status, Education |

---

## 🔧 What Was Done

### 1. Data Cleaning
- Standardized categorical fields (e.g., `M/S` → `Married/Single`, `M/F` → `Male/Female`) for clarity and pivot compatibility
- Removed duplicate records to ensure analytical integrity
- Verified no nulls or inconsistencies across 14 columns

### 2. Feature Engineering
- Created **Age Bracket** column segmenting customers into `Adult (25–34)`, `Middle Age (35–54)`, and `Old (55+)` — enabling age-based cohort analysis

### 3. Pivot Table Analysis
- Built multiple pivot tables to cross-tabulate purchase behavior against income, gender, age bracket, commute distance, and region
- Used pivot tables as the analytical layer feeding directly into the dashboard

### 4. Interactive Dashboard
- Built a dynamic dashboard with **slicers** for Region, Marital Status, and Education
- Visualized purchase patterns across income brackets, commute distance, and age groups
- Designed for a non-technical stakeholder audience — findings navigable without touching raw data

---

## 📊 Key Findings

| Insight | Data |
|---|---|
| **Middle Age customers convert at the highest rate** | 54.7% purchase rate vs. 36.6% (Adults) and 31.3% (Older) |
| **Buyers earn more on average** | Avg. income $57,474 (buyers) vs. $55,028 (non-buyers) |
| **Short commuters are the largest segment** | 37% of customers commute 0–1 miles — highest purchase likelihood |
| **Gender has minimal impact on conversion** | Males: 48.0% purchase rate / Females: 48.5% — near-identical |
| **North America dominates the dataset** | 508 of 1,026 customers (49.5%) — largest regional segment |

---

## 💡 Business Implication

If this were a real client engagement, the recommendation would be straightforward:

> *Prioritize marketing spend toward Middle Age professionals with mid-to-high income and short commutes. Gender-based targeting offers minimal incremental value — reallocate that budget toward age and commute-distance segmentation.*

This kind of insight — moving from raw data to a clear, actionable recommendation — is the core of what analytics delivers in a consulting context.

---

## 🛠️ Skills Demonstrated

`Data Cleaning` &nbsp;`Feature Engineering` &nbsp;`Pivot Tables` &nbsp;`Dashboard Design` &nbsp;`Slicer Interactivity` &nbsp;`Stakeholder Communication`

---

## 📁 Repository Structure

```
Excel-DataAnalysis-BikeSales/
│
├── Excel_Project_Dataset.xlsx   # Raw data + cleaned worksheet + pivot tables + dashboard
└── README.md                    # Project documentation
```

---

## 🔗 Connect

**LinkedIn:** [linkedin.com/in/rohitkhot-analyst](https://linkedin.com/in/rohitkhot-analyst)  
**GitHub:** [github.com/RohitKhot-47](https://github.com/RohitKhot-47)  

---

*Part of an ongoing analytics portfolio built across SQL, Excel, Tableau, and Python — targeting business consulting and data analytics roles.*
