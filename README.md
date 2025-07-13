# 🚀 Falcon 9 First Stage Landing Prediction

This project aims to **predict whether the Falcon 9 first stage will land successfully**, using historical SpaceX launch data and public APIs.

---

## 💼 Business Context

SpaceX can **reuse Falcon 9’s first stage**, significantly lowering launch costs — from $165M to $62M. Knowing whether a launch is likely to result in a successful landing provides critical insights for budgeting, bidding, and aerospace logistics.

---

## 🎯 Project Objectives

- Collect launch data using SpaceX and OpenNotify APIs
- Clean and process data using Pandas
- Perform exploratory data analysis (EDA)
- Engineer features for model input
- Train machine learning models (Logistic Regression, Random Forest, etc.)
- Evaluate models and derive business insights

---

## 🛠️ Tech Stack

| Category | Tools |
|---------|-------|
| Language | Python 3.x |
| Libraries | Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn |
| ML | Logistic Regression, Random Forest, Gradient Boosting |
| APIs | SpaceX REST API, OpenNotify |
| IDE | Jupyter Notebook |
| Deployment | GitHub |


---

## 📁 Project Structure

```text
falcon9-landing-prediction/
│
├── data/
│   ├── raw/              # API downloads
│   └── processed/        # Cleaned datasets
│
├── notebooks/
│   ├── 01_data_collection.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_eda_visualization.ipynb
│   ├── 04_feature_engineering.ipynb
│   ├── 05_modeling.ipynb
│   ├── 06_model_evaluation.ipynb
│   └── 07_business_insights.ipynb
│
├── src/
│   ├── data.py
│   ├── features.py
│   ├── train.py
│   ├── evaluate.py
│   └── utils.py
│
├── outputs/
│   ├── models/
│   ├── figures/
│   └── results/
│
├── requirements.txt
├── environment.yml        # Optional
├── LICENSE
├── .gitignore
└── report.pdf             # Final report 


