# 📈 Project 2: Advanced Exploratory Data Analysis (EDA)
**DecodeLabs Data Analytics Internship | Mathematical Analytics & Statistical Auditing**

## 🏷️ Project Title
**E-Commerce Financial Revenue Stream Variance Analysis & Statistical Outlier Identification**

## 📝 Detailed Project Overview
Data distributions within retail streams are frequently volatile and skewed due to transactional anomalies. This project executes an advanced Exploratory Data Analysis (EDA) and rigorous statistical audit across the sanitized dataset of **1,200 unique records** using Microsoft Excel. By building continuous frequency distribution models and implementing parametric boundaries, this pipeline locates systemic skewness and isolates critical revenue vectors driving our macro projections.

---

### 📊 Comprehensive Statistical Indicators & Volume Metrics

Conducted a deep computational data audit to calculate the true center, variation, and mathematical spread of our global revenue operations:
* **Operational Mean (Average Transaction Value):** \$1,053.97
* **Central Median (True Distribution Center):** \$823.62
* **Standard Deviation (Data Variation/Spread):** \$819.86
* **Minimum Order Value:** \$11.39 | **Maximum Order Value:** \$3,456.40
* **Computational Insights:** The substantial variance gap where the calculated Mean (\$1,053.97) is pulled significantly higher than the central Median (\$823.62) mathematically validates a **heavy right-skewed revenue distribution model**. The metric skewness is heavily driven by a distinct high-value transaction layer pulling the average upward.

---

### 🚨 Tukey's Interquartile Range (IQR) Outlier Isolation Framework

Rather than relying on generic percentage assumptions, this framework deploys strict parametric mathematical constraints to isolate transactional anomalies:
1. **Quartile Boundaries:** Locked the Lower Quartile (Q1) at **\$410.52** and the Upper Quartile (Q3) at **\$1,578.48**.
2. **Interquartile Range Calculation:** Evaluated the data spread to set the IQR factor at **\$1,167.96**.
3. **Threshold Boundary Limit:** Multiplied the IQR factor by the standard 1.5 threshold limit to establish a strict upper-bound baseline ceiling threshold at exactly **\$3,330.41**.
4. **Forensic VIP Discovery:** Every transaction breaching the \$3,330.41 boundary limit was flagged. The analytics engine captured exactly **8 absolute high-value positive outlier transactions** driving massive macro velocity.

---

### 🖼️ Operational Excel Analytical Visualizations
Below is the verified spreadsheet snapshot displaying our distribution histogram models, continuous monthly timeline trends, and the statistical outlier fingerprinting chart [image_DUGNuC.png]:

![Excel Statistical Dashboard](Exploratory%20Data%20Analysis.png)

---

### 📈 Strategic Corporate Takeaways & Metrics Verification
* **B2B Isolation Loop:** The 8 isolated positive outliers represent bulk enterprise B2B transactions rather than retail logging errors. Recommend separating these records into a dedicated high-margin tracking account stream.
* **Quantity vs Price Dynamics:** A positive correlation index of **0.62** confirms high operational dependency on large-volume purchasing runs across our client cycles.
* **Macro Revenue Financial Channels:** Verified a total sales accumulation of **\$263,847.63 coming strictly from Credit Card streams**.

## ⚙️ How to Run & Replicate This Project
1. Download the operational spreadsheet asset: **`Dataset for Data Analytics(EDA).xlsx`**.
2. Open the file inside Microsoft Excel to inspect the formulas embedded within the Advanced Statistics calculations worksheet.
