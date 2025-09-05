Paisabazaar Banking Fraud Analysis
📌 Project Overview

This project focuses on Exploratory Data Analysis (EDA) of Paisabazaar’s customer dataset to understand patterns that influence credit scores and identify potential fraud or risky behaviors.
Credit scores are a critical measure of financial health, impacting loan approvals, interest rates, and repayment monitoring. The dataset includes demographic, financial, and behavioral attributes such as income, spending, loans, payment history, and credit utilization.

The main goal of this project is to extract actionable insights that can help reduce default risk, improve lending strategies, and strengthen fraud detection mechanisms.

🎯 Problem Statement

Paisabazaar, a leading financial services platform, aims to:

Understand the distribution of credit scores (Good, Standard, Poor).

Identify key financial behaviors that separate high- and low-credit customers.

Detect patterns, anomalies, and correlations in the data.

Generate insights to support predictive modeling and customer profiling for better loan decisions.

📊 Steps & Approach

Data Understanding

Checked dataset size, structure, and data types.

Explored categorical & numerical features.

Data Wrangling

Handled missing values, duplicates, and outliers.

Cleaned categorical variables like Payment_Behaviour, Credit_Mix.

Exploratory Data Analysis (EDA)

Distribution plots (Income, Age, Utilization, Loans).

Relationship charts (Credit Score vs Income, Age, Loans, Delayed Payments, Utilization).

Correlation heatmap to find linked financial metrics.

Insights Extraction

High utilization ratio (>50%) strongly correlates with Poor scores.

Customers skipping minimum payments are at high risk.

Occupations like Engineers, Doctors, Managers → mostly Good scores.

Multiple loans and delayed payments → mostly Poor scores.

Age >35 tends to have better repayment discipline.

📈 Key Visualizations

Credit Utilization Ratio Distribution (Histogram)

Credit Score vs Annual Income (Boxplot)

Credit Score vs Age (Boxplot)

Credit Score vs Number of Loans (Bar Plot)

Credit Score vs Payment Behavior (Stacked Bar)

Correlation Heatmap of numerical features

Occupation vs Income vs Credit Score (Violin Plot)

💡 Business Impact & Recommendations

Customer Segmentation:

Good: Premium offers & high-value loans.

Standard: Credit improvement programs.

Poor: Limited credit, stricter monitoring.

Risk Monitoring:

Focus on repayment delays, high utilization, and skipped minimum dues.

Trigger alerts for risky behaviors.

Targeted Marketing:

Offer premium products to high-income, low-risk customers.

Provide credit-building tools for younger customers.

Revenue Growth:

Safer lending reduces default risk.

Personalized offers improve customer loyalty.

📂 Project Files

Paisabazaar_Banking_Fraud_Analysis.ipynb → Google Colab / Jupyter Notebook with step-by-step EDA and visualizations.

Paisabazaar_Banking_Fraud_Analysis.py → Python script version of the analysis for quick execution.

dataset(2).csv (Dataset) → https://drive.google.com/file/d/1KNocQ0B26rPlclgDEvb4Fz_klwUqfmrG/view?usp=sharing

README.md → Project documentation.

🛠️ Tech Stack

Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn

Platform: Google Colab

✅ Conclusion

The analysis highlights that credit score is not just income-driven, but heavily influenced by repayment discipline, loan behavior, and credit utilization.

Paisabazaar can strengthen its fraud detection & credit assessment models by focusing on these behavioral patterns, improving both profitability and customer trust.
