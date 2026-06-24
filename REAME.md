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
