# 📈 Project 2: Advanced Exploratory Data Analysis (EDA)
**DecodeLabs Data Analytics Internship | Mathematical Analytics & Statistical Auditing**

## 🏷️ Project Title
**E-Commerce Revenue Distribution Optimization & Parametric Outlier Profiling Model**

## 📝 Detailed Project Overview
Moving beyond basic data cleaning, this milestone implements comprehensive descriptive statistics, continuous frequency distribution auditing, and parametric boundary limits on the sanitized database of **1,200 unique transactional records** using Microsoft Excel. The core business intelligence goal is to model structural revenue metrics, track database skewness, and isolate financial anomalies pulling our macro projections.

---

### 📊 Comprehensive Statistical Indicators & Volume Metrics

Conducted a deep computational data audit to locate the true center, variation, and mathematical spread of our global revenue operations:
* **Operational Mean (Average Transaction Value):** \$1,053.97
* **Central Median (True Distribution Center):** \$823.62
* **Standard Deviation (Data Variation/Spread):** \$819.86
* **Minimum Order Value:** \$11.39 | **Maximum Order Value:** \$3,456.40
* **Computational Insights:** The massive variance gap where the calculated Mean (\$1,053.97) is pulled significantly higher than the central Median (\$823.62) mathematically validates a **heavy right-skewed revenue distribution model**. The metric skewness is heavily driven by a distinct high-value transaction layer.

---

### 🚨 Tukey's Interquartile Range (IQR) Outlier Isolation Framework

Rather than relying on generic percentage assumptions, this framework deploys strict parametric mathematical constraints to isolate transactional anomalies:
1. **Quartile Boundaries:** Locked the Lower Quartile (Q1) at **\$410.52** and the Upper Quartile (Q3) at **\$1,578.48**.
2. **Interquartile Range Calculation:** Evaluated the data spread to set the IQR factor at **\$1,167.96**.
3. **Threshold Boundary Limit:** Multiplied the IQR factor by the standard 1.5 threshold limit to establish a strict upper-bound baseline ceiling threshold at exactly **\$3,330.41**.
4. **Forensic VIP Discovery:** Every transaction breaching the \$3,330.41 boundary limit was flagged. The analytics engine captured exactly **8 absolute high-value positive outliers** driving massive macro velocity.

---

### 🖼️ Operational Excel Analytical Visualizations
Below is the verified spreadsheet snapshot displaying our distribution histogram models, continuous monthly timeline trends, and the statistical outlier fingerprinting chart [image_DUGNuC.png]:

![Excel Statistical Dashboard](Exploratory%20Data%20Analysis.png)

---

### 📈 Strategic Corporate Recommendations & Takeaways
* **B2B Isolation Loop:** The 8 isolated positive outliers represent bulk enterprise B2B transactions rather than retail errors. Recommend immediate segregation into a separate premium corporate tracking system.
* **Correlation Awareness:** A positive correlation index of **0.62** between transaction quantity and pricing confirms high operational dependency on large-volume client loops.

## ⚙️ How to Run & Replicate This Project
1. Download the operational spreadsheet asset: **`Dataset for Data Analytics(EDA).xlsx`** [image_2eP6MQ.png].
2. Open the file inside Microsoft Excel to inspect the formulas embedded within the Advanced Statistics calculations worksheet.
