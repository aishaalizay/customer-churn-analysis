# 📊 Customer Churn Prediction & Analysis

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python) ![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange?logo=scikit-learn) ![pandas](https://img.shields.io/badge/pandas-Data%20Analysis-lightblue?logo=pandas) ![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

> Predicting which telecom customers are likely to cancel their subscription — and why.

---

## 📌 Project Overview

Customer churn is one of the most costly problems for telecom companies. This project builds a **machine learning pipeline** to predict churn using the IBM Telco Customer Churn dataset, identifies the key business drivers, and provides actionable retention recommendations.

---

## 🎯 Objectives

- Perform exploratory data analysis (EDA) on 7,000+ customer records
- Identify patterns and features that most influence churn
- Train and compare ML models (Logistic Regression vs Random Forest)
- Visualize results and translate findings into business recommendations

---

## 🛠️ Tools & Technologies

| Category | Tools |
|---|---|
| Language | Python 3.10 |
| Data Analysis | pandas, NumPy |
| Visualization | matplotlib, seaborn |
| Machine Learning | scikit-learn |
| Environment | Jupyter Notebook |

---

## 📁 Project Structure

```
customer-churn-analysis/
│
├── customer_churn_analysis.ipynb   # Main notebook (EDA + ML)
├── WA_Fn-UseC_-Telco-Customer-Churn.csv  # Dataset (download from Kaggle)
├── README.md                       # Project documentation
│
└── outputs/                        # Generated plots
    ├── churn_distribution.png
    ├── tenure_charges.png
    ├── contract_internet.png
    ├── correlation_heatmap.png
    ├── model_evaluation.png
    └── feature_importance.png
```

---

## 📊 Key Results

| Model | Accuracy | AUC Score |
|---|---|---|
| Logistic Regression | ~80% | ~0.84 |
| **Random Forest** ✅ | **~84%** | **~0.88** |

---

## 🔑 Key Findings

1. **Month-to-month contracts** have the highest churn rate
2. **New customers (first 12 months)** are at the highest risk
3. **High monthly charges** strongly correlate with churn
4. **Fiber optic users** churn significantly more than DSL users

---

## 💼 Business Recommendations

- Offer loyalty discounts to customers in their first 6 months
- Incentivize annual contract sign-ups over month-to-month plans
- Review Fiber optic pricing and service quality
- Flag high-risk customers and assign to a proactive retention team

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/aishaalizay/customer-churn-analysis.git
   cd customer-churn-analysis
   ```

2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) and place the CSV in the project folder

4. Launch Jupyter:
   ```bash
   jupyter notebook customer_churn_analysis.ipynb
   ```

---

## 👩‍💻 About Me

**Ayesha Munir** — Data Analytics Graduate  
🔗 [LinkedIn](https://www.linkedin.com/in/ayesha-munir22) · [GitHub](https://github.com/aishaalizay)
