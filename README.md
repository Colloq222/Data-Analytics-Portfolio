# 📊 Data Analytics Portfolio
### by Colloq222

A collection of data analysis projects using Python, Pandas, 
and data visualization libraries (Matplotlib, Seaborn).

---

## 🗂️ Projects

### 1. 💰 Sales Analysis
**Tools:** Python, Pandas, Matplotlib, Seaborn  
**Dataset:** 12-month retail sales data (185,950 rows)

**Key Findings:**
- Total revenue: $34.49M across 12 months
- December had the highest sales ($4.6M) — holiday season effect
- AAA Batteries were the best-selling product by quantity
- San Francisco generated the highest city revenue ($8M+)
- Peak order hours: 12pm and 7pm — lunch and after-work shopping

📁 [View Notebook](./Sales%20Analysis/sale_pro.ipynb)

---

### 2. 🛍️ Customer Personality Analysis
**Tools:** Python, Pandas, Matplotlib, Seaborn  
**Dataset:** 2,240 customers | 29 columns | Marketing campaign data

**Key Findings:**
- Customers without children spend nearly 3x more ($1,106 vs $406)
- Higher education directly correlates with higher income
- Moderate positive correlation between Income and Total Spending
- Top spending segment: Master's degree + Widow status
- Detected data entry outlier ($666,666 income) and cleaned invalid 
  Marital Status entries ("Absurd", "YOLO")

**Business Recommendations:**
- Target educated, childless customers with premium products
- Develop child-oriented product lines for family segment
- Offer budget-friendly options for Basic education segment

📁 [View Notebook](./Customer%20Personality/customer_analysis.ipynb)

---

### 3. 🚢 Titanic Survival Analysis
**Tools:** Python, Pandas, Matplotlib, Seaborn  
**Dataset:** 891 passengers | Titanic survival records

**Key Findings:**
- Overall survival rate: 38.38%
- Female passengers survived at 74% vs male at 19%
- First class passengers survived at significantly higher rates
- Small families (1-3 members) survived more than solo travelers or large families
- Age alone was not a strong survival factor

📁 [View Notebook](./Titanic%20Analysis/titanic_analysis.ipynb)

### 4. ☕ Cafe Sales Data Cleaning
**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn  
**Dataset:** 10,000 dirty cafe transactions | 8 columns

**Project Focus:** Data Cleaning & Preprocessing  
This project focuses on cleaning an intentionally messy dataset 
rather than deep analysis — reflecting the reality that data 
cleaning accounts for 60-70% of a real data analyst's work.

**Dirty Data Found:**
- `"ERROR"` and `"UNKNOWN"` strings hiding as fake missing values
- Wrong data types across all numeric columns
- Missing values across 6 out of 8 columns after proper detection

**Key Cleaning Techniques:**
- Detected hidden dirty data via `.value_counts()` (not just `isnull()`)
- Smart imputation using math relationship: `Total Spent = Price × Quantity`
- Bidirectional dictionary mapping to fill Item ↔ Price Per Unit
- Business-driven NaN decisions — kept 477 Item NaNs to preserve revenue integrity
- Flagged Payment Method (31%) and Location (39%) as "Unknown" — 
  too high % to fill reliably without introducing bias

**Post-Cleaning Findings:**
- Best selling item by revenue: **Salad** (~$19,000)
- Best selling item by quantity: **Coffee**
- Revenue stable year-round (~$6,700–$7,350/month)
- Payment methods evenly split among known transactions
- No outliers detected in Total Spent — data internally consistent ✅

⚠️ **Data Limitation:** 31-39% missing in Payment Method and 
Location columns limits analysis of these dimensions.

📁 [View Notebook](./Cafe%20Sales%20Cleaning/cafe_cleaning.ipynb)

---

## 🛠️ Skills Demonstrated
- Data cleaning & handling missing values
- **Hidden dirty data detection** ← new!
- **Smart imputation using mathematical relationships** ← new!
- **Dictionary mapping for bidirectional filling** ← new!
- Outlier detection & treatment
- Exploratory data analysis (EDA)
- Feature engineering
- GroupBy aggregations & multi-column analysis
- Correlation analysis
- Data visualization (bar, line, scatter, histogram)
- Business insight generation & recommendations
- **Data limitation documentation** ← new!

---

## 📚 Currently Learning
- SQL (Kaggle Learn)
- Advanced Excel & Pivot Tables

---

## 🚧 Coming Soon
- SQL Analysis Project
- Excel Dashboard Project
