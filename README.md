# Bank-Marketing-Data-Analysis-EDA-and-Visualization-Using-Python

# 🏦 Bank Marketing Campaign Analysis

Exploratory Data Analysis (EDA) of a bank’s direct marketing campaigns to understand **term deposit subscription behavior** and identify **high-impact customer segments** using demographic, behavioral, historical, and economic signals.

---

## 🎯 Objective
- Identify customer segments with high subscription propensity  
- Evaluate contact channels and campaign intensity  
- Measure the impact of previous campaign outcomes  
- Assess macroeconomic influence on customer decisions  
- Provide actionable recommendations for campaign optimization  

---

## 🧱 Segmentation Framework

### Customer Profile
- Age Group: Young / Mid / Senior  
- Job Group: Professional, Service / Blue Collar, Student / Retired, Unemployed  
- Education Level: Low / Medium / High  
- Financial Risk: Low / Medium  

### Contact Strategy
- Contact Type: Cellular vs Telephone  
- Campaign Intensity:
  - 0–10 → Optimal  
  - 10–20 → Declining  
  - 20–30 → Very low  
  - 30+ → Over-contacting  

### Previous Campaign History
- Previous contacts count  
- Previous outcome: Success / Failure / None  

### Macroeconomic Context
- Employment growth  
- Interest rate (euribor3m)  
- Consumer price index  
- Consumer confidence  
- Employment level  

---

## 📊 Dataset
- **Records:** 41,188  
- **Target:** `y` (Term deposit subscription: Yes / No)  
- **Source:** Bank Marketing Dataset  

---

## 🔍 Key Insights
- **Cellular contact is ~3× more effective** than telephone  
- Conversion drops sharply after **10+ contacts**  
- Customers with **previous success convert ~65%**  
- Seniors, students, and retired customers perform best  
- Subscriptions are **counter-cyclical** (higher in weak economic periods)

---

## 🚀 Recommendations
- Retarget customers with previous successful outcomes  
- Cap contact attempts to avoid fatigue  
- Prioritize cellular outreach  
- Align campaigns with low-interest or weak employment periods  
- Shift from mass marketing to precision targeting  

---

## 🛠 Tools
- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Jupyter Notebook  
- Power BI  

---

## 📂 Structure
