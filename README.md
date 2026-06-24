# 📊 Data Analytics Portfolio
### by Colloq222

A collection of data analysis projects using Python, Pandas, and data visualization libraries.

---

## 🗂️ Projects

### 1. Sales Analysis
**Tools:** Python, Pandas, Matplotlib, Seaborn  
**Dataset:** 12-month retail sales data (185,950 rows)

**Key findings:**
- Total revenue: $34.49M across 12 months
- December had the highest sales ($4.6M) — holiday season effect
- AAA Batteries were the best-selling product by quantity
- San Francisco generated the highest revenue by city ($8M+)
- Peak order hours: 12pm and 7pm — lunch and after-work shopping

📁 [View Notebook](./Sales%20Analysis/sale_pro.ipynb)

---

## 🛠️ Skills
- Data cleaning & handling missing values
- Exploratory data analysis (EDA)
- GroupBy aggregations & multi-column analysis
- Data visualization (bar charts, line charts)
- Python (Pandas, Matplotlib, Seaborn)

---

## 🚧 Coming Soon
- Customer Personality Analysis
- Titanic Survival Analysis
- SQL Projects

## 2. Customer Personality Analysis
**Tools:** Python, Pandas, Matplotlib, Seaborn  
**Dataset:** 2,240 customers | 29 columns | Marketing campaign data

### 🎯 Objective
Analyze customer demographics and spending behavior to identify 
key segments for targeted marketing strategies.

### 🧹 Data Cleaning
- Found and filled 24 missing `Income` values with column mean
- Detected income outlier ($666,666) — flagged as likely data entry error
- Cleaned invalid `Marital_Status` entries (`"Absurd"`, `"YOLO"`) → replaced with `"Unknown"`

### 🔍 Key Findings
- **Higher education = Higher income** — PhD holders earn the most, 
  Basic education earns significantly less
- **Children reduce spending by ~63%** — customers without children 
  spend nearly 3x more ($1,106 vs $406)
- **Moderate positive correlation** between Income and Total Spending
- **Top segment:** Educated Widows (Master/PhD) spend the most across all groups
- **Peak spending combo:** Master's degree + Widow status = highest average spending

### 💡 Business Recommendations
1. Target **educated, childless customers** with premium product offerings
2. Develop **child-oriented product lines** to capture family segment spending
3. Deprioritize or offer **budget-friendly options** for Basic education segment

### 📊 Visualizations
- Average Income by Education Level
- Wine Spending by Marital Status  
- Spending: Children vs No Children
- Income vs Total Spending (Scatter)
- Top Spending by Education + Marital Status

📁 [View Notebook](./Customer%20Personality/customer_analysis.ipynb)

---
