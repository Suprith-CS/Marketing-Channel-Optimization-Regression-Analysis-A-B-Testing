# 📈 Marketing Channel Optimization: Regression Analysis & A/B Testing

## 🎯 Business Objective
This project performs a high-level statistical evaluation of 365 days of marketing data (2025) to compare the efficiency of **Facebook Ads** vs. **Google AdWords**. Using predictive modeling and hypothesis testing, the goal is to identify which platform delivers superior ROI and provide data-driven recommendations for budget reallocation.



## 🚀 Key Insights & Performance Benchmarks
* **Conversion Dominance:** Facebook generated **2.43x more conversions** on average than AdWords (13.30 vs 5.46 daily).
* **Efficiency Gap:** Facebook achieved a **20.12% conversion rate**, nearly double the **10.88%** seen on AdWords.
* **Cost Advantage:** Facebook provided higher volume while costing **15.7% less** per day on average ($35.42 vs $42.04).
* **Reliability:** Facebook maintained a high performance floor with **zero days** in the low-conversion (0-5) range, whereas AdWords underperformed for **51% of the year**.

## 🧪 Statistical Validation (A/B Testing)
To ensure the performance gap wasn't due to random variance, an **Independent T-Test** was conducted:
* **T-Statistic:** 36.31
* **P-Value:** 1.46e-165
* **Result:** The difference is **extremely significant**. We reject the null hypothesis, confirming Facebook is objectively the more effective channel for this audience.

## 📉 Regression & Predictive Modeling
A Linear Regression model was built to test if "Click Volume" accurately predicts "Conversions":
* **Weak Predictive Power:** The model returned an **R² of 0.153**, meaning clicks only explain 15% of conversion success.
* **The Scale Paradox:** Increasing clicks from 50 to 80 on Facebook only predicted a negligible conversion rise (13.14 to 13.37).
* **Traffic Quality:** The near-zero correlation (FB: 0.04 | AdWords: -0.05) indicates that **buying more traffic is not the solution**—optimizing for traffic quality and intent is required.



## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scipy, Statsmodels
* **Analysis:** Linear Regression, Hypothesis Testing (T-Tests), Data Binning, Correlation Matrices

## 📂 Project Structure
* `Regression Analysis.ipynb`: Core technical notebook containing data cleaning, T-tests, and regression modeling.
* `Dataset.ipynb`: The script used to generate the 2025 marketing logs.
* `marketing_campaign_2025.csv`: The master dataset containing 365 days of performance logs.
* `Regression analysis report.docx`: An industrial-level summary of findings for stakeholders.

## 💡 Strategic Recommendations
1. **Immediate Pivot:** Shift 30-50% of the Google AdWords budget to Facebook to maximize total conversion volume at a lower CPA.
2. **Quality over Volume:** Since clicks are weak predictors of sales, move away from "Click-Optimization" toward "Conversion-Intent" targeting.
3. **AdWords Audit:** The negative correlation suggests "spend leakage." A total keyword audit is required to eliminate non-converting broad-match traffic.



---
**Contact:** www.linkedin.com/in/suprithcs
