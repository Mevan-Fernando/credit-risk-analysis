# Credit Risk Analysis — Geldium Project

## 📌 Problem
Predict customer delinquency risk using financial and behavioral data.

## 📊 Dataset
- 500 customers
- Financial + demographic features
- 6-month payment history

## 🔍 Key Findings
- No significant relationship between features and target
- Dataset lacks predictive signal
- Logistic Regression ROC-AUC ≈ 0.5 (random performance)

## ⚙️ What I Did
- Exploratory Data Analysis (EDA)
- Statistical testing (Mann-Whitney U, Chi-square)
- Feature engineering (payment risk score, trends)
- Class imbalance handling
- Machine Learning (Logistic Regression)

## 🤖 GenAI Approach
- Used CTGAN to generate synthetic data
- Improved model performance (AUC ~0.3 → ~0.8)
- Evaluated risks of assumption-driven bias

## 💡 Key Insight
> Data quality is more important than model complexity

## 🏗️ Recommendation
- Improve data collection
- Capture real customer behavior
- Use richer financial signals

## 📊 Results
- Baseline Model: ROC-AUC ≈ 0.5
- After CTGAN: AUC ≈ 0.8 (synthetic data)

## 🚀 Tech Stack
- Python (Pandas, NumPy)
- Scikit-learn
- Seaborn / Matplotlib
- CTGAN
