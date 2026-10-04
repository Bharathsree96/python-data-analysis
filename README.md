# python-data-analysis 🐍

## What is this project?
A Python-based data analysis project that cleans, merges, and enriches 
employee and project cost data from multiple disconnected sources to 
support cost tracking, bonus calculations, and designation-level adjustments.

---

## Problem it solves
Three separate datasets — project costs, employee details, and seniority 
data — had missing values, inconsistent formatting, and no common structure. 
Manual tracking was error-prone and time-consuming. This project automates 
the entire pipeline from raw messy data to clean, enriched output.

---

## Tools Used
| Tool | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data cleaning, merging, group-by aggregation |
| NumPy | Missing value imputation using running averages |

---

## Key Results
- ✅ Processed all 14 records across 5 employees
- ✅ Imputed 14.3% missing cost values using running averages
- ✅ Automated bonus calculations for 7 completed projects (50%) 
  totalling ~₹6,32,625
- ✅ Calculated employee costs ranging from ₹2.68M to ₹9.5M
- ✅ Standardised names, merged 14 records, applied 
  bonus/designation rules using group-by logic

---

## Project Structure
├── Capstone Project Notebook.ipynb
├── Capstone_Project_Bharath.ipynb
└── README.md


---

## Key Steps
1. Loaded 3 disconnected datasets with missing values 
   and inconsistent formatting
2. Standardised employee names and merged records 
   across all datasets
3. Imputed missing costs using running averages
4. Applied bonus rules for completed projects
5. Applied designation-level cost adjustments
6. Aggregated final employee costs using group-by logic

---

*Capstone Project — SkilloVilla Python Fundamentals (Jul 2026)*
