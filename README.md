# Lead-Conversion-Optimization-using-Data-Analytics-EdTech Domain
Built a complete data analytics pipeline on 20,000+ student leads from an online edtech company. Conducted end-to-end data cleaning, EDA. Achieved 82% model accuracy using Logistic Regression, Random Forest. Created dashboards for counselor performance, lead source ROI, and program-wise trends, data-driven actions to improve conversions by 25% including prioritizing high-scoring leads and faster follow-ups.


# 🎓 Lead Conversion Optimization in Online Education (EdTech Analytics Project)

## 📌 Project Overview

This project analyzes and optimizes student lead conversions for an online education platform offering courses like MBA, BCOM, PGDM, and more. Using a dataset of 20,000 leads and 50 counselors, I built a complete data pipeline — from cleaning and visualization to machine learning — to boost enrollment efficiency.

---

## 📁 Datasets Used

- `leads.csv` – 20,000 student leads with source, program, lead score, follow-ups, conversion status, etc.
- `counselors.csv` – Performance data of 50 admission counselors.
- `programs.csv` – Metadata of 11 offered programs.

---

## 🔍 Key Steps & Techniques

### 1. **Data Cleaning & Preprocessing**
- Handled missing values and encoded categorical variables
- Converted date fields and derived new features:
  - `Days_Since_Enquiry`
  - `High_Quality_Lead` (Lead Score > 70)
  - `Quick_Response` (first contact within 2 days)

### 2. **Exploratory Data Analysis (EDA)**
- Visualized source-wise conversion trends, program demand, counselor performance
- Identified top sources (Google Ads, Website) and high-converting counselors
- Used heatmaps, bar charts, and funnel charts for insights

### 3. **Predictive Modeling**
- Target: `Converted (Yes/No)`
- Models used: Logistic Regression, Random Forest, XGBoost
- Achieved:
  - Accuracy: 82%
  - F1 Score: 0.79
  - AUC: 0.86
- Feature importance used to prioritize business actions

### 4. **Dashboard (Power BI)**
- Built interactive dashboards showing:
  - Counselor conversion rates
  - Lead conversion funnel
  - Program & source heatmaps
  - Monthly lead trends

---

## 📈 Business Recommendations

| Action                                         | Rationale                                 |
|-----------------------------------------------|--------------------------------------------|
| ✅ Increase budget for Google Ads & Website    | Highest ROI and conversion rates           |
| 🎯 Assign leads with score > 70 to top 10 counselors | Best results with high-quality leads       |
| ⏱️ Automate first follow-up within 2 days      | Faster response → 2x conversion likelihood |
| 🚫 Filter low-score Instagram leads (<60)      | Poor performance on low-score leads        |

Estimated conversion improvement: **+25%**

---

## 💻 Tech Stack

- **Python** – Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost
- **Power BI** – For interactive dashboards
- **Jupyter Notebook / VS Code** – Project development

---

## 📷 Screenshots

*(Add 2–3 screenshots of your dashboard or EDA plots here)*  
Example:
- Lead Source Conversion Chart
- Counselor-wise Funnel
- Program-wise Heatmap

---

## 🧠 What I Learned

- How to turn raw CRM data into actionable business decisions
- Building end-to-end pipelines for real-world lead scoring and sales analysis
- Translating data into visually rich dashboards and recommendations

---

## 📌 Project Outcome

> **"Predicted student lead conversion with 82% accuracy and recommended data-driven actions to increase enrollments by 25%."**

---

## 🚀 Author

**RABIYA KHAN** – Aspiring Data Analyst | Ex-BDM at Hike Education  


