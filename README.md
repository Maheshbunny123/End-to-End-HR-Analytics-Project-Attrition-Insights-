# Employee Attrition Analysis & Prediction using Python and Power BI

## 📌 Overview
This end-to-end project analyzes employee attrition trends and predicts which employees are most likely to leave. It combines **data cleaning**, **EDA**, **visual storytelling**, and **machine learning** using **Python (Colab)** and **Power BI**.

> 🎯 This project is designed to help HR departments make smarter decisions by identifying high-risk attrition segments.

---

## 🛠️ Tools & Technologies
- Python (pandas, seaborn, matplotlib)
- Google Colab
- Power BI
- Kaggle Dataset: HR Employee Attrition

---

## 🧩 Project Workflow

### 1️⃣ Data Cleaning
- Removed irrelevant columns (`EmployeeCount`, `StandardHours`, etc.)
- Encoded categorical variables
- Created bins for Age & Income (`AgeGroup`, `IncomeLevel`)

### 2️⃣ Exploratory Data Analysis (EDA)
- Attrition vs Age Group, Department, Monthly Income
- Created custom visual features to enhance insight (bar plots, boxplots)

### 3️⃣ Machine Learning (Planned in Extension)
- AttritionFlag: Converted to 0 (No) / 1 (Yes)
- Dataset prepared for future modeling

### 4️⃣ Dashboard with Power BI
- Designed an HR dashboard with key KPIs:
  - Attrition Rate by Department
  - Monthly Income vs Attrition
  - Age Group-based attrition
  - Interactive filters for deeper analysis

---



---

## 📁 Project Structure

```bash
employee-attrition-analysis/
│
├── data/
│   └── Cleaned_Attrition_Data.csv
│
├── notebook/
│   └── Employee_Attrition_Analysis.ipynb
│
├── dashboard/
│   ├── HR_DASHBOARD.pbix
│   └── dashboard_screenshots/
│       ├── overall_view.png
│       └── attrition_by_age.png
│
├── report/
│   └── project_report.pdf
│
└── README.md
