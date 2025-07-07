# 📊 Customer Churn Prediction with Machine Learning

## 🧠 Overview

This project focuses on predicting **customer churn** in the telecom industry using machine learning models. Churn prediction allows telecom companies to proactively retain customers and reduce revenue loss.

The project compares several models, addresses class imbalance, and selects the best-performing one based on F1-score and ROC AUC.

---

## 🗂️ Dataset

- 📌 Source: [WA_Fn-UseC_-Telco-Customer-Churn.csv](https://www.kaggle.com/datasets/palashfendarkar/wa-fnusec-telcocustomerchurn)
- 💡 7,000+ customer records with features such as:
  - Demographics (e.g., gender, senior citizen)
  - Services used (e.g., internet service, phone service)
  - Account information (e.g., tenure, payment method)
  - Target: `Churn` (Yes/No)

---

## ⚙️ Project Workflow

- Exploratory Data Analysis (EDA) with visualizations
- Data cleaning and feature engineering
- Handling class imbalance using **SMOTE**
- Training and evaluating multiple classification models:
  - Logistic Regression, Random Forest, SVM, XGBoost
  - Ensemble models: Voting Classifier and Stacking Classifier
- Comparing models using:
  - F1-score
  - ROC AUC
  - Confusion matrix and classification report

---

## 📈 Results

| Model                | F1-score | ROC AUC |
|---------------------|----------|---------|
| Logistic Regression | 0.78     | 0.78    |
| Random Forest       | 0.86     | 0.86    |
| SVM                 | 0.85     | 0.85    |
| XGBoost             | **0.86** | **0.86** |
| Voting Classifier   | 0.85     | 0.846   |
| Stacking Classifier | 0.85     | 0.850   |

---

## ✅ Final Model Selection

**XGBoost** was selected as the final model due to:
- Its ability to handle mixed feature types (numeric + categorical)
- Regularization to reduce overfitting
- Strong performance on both F1-score and ROC AUC
- Interpretability through feature importance

---

## ▶️ How to Explore the Project

Since this project was developed using **Kaggle Notebooks**, you can run and explore it by:

1. Visiting the Kaggle Notebook (link below).
2. Running all cells to reproduce results.
3. Optionally downloading the notebook (`File > Download .ipynb`) to run it locally.

🔗 [Open the Kaggle Notebook](https://www.kaggle.com/code/nouryami/costumer-churn-prediction)

---

## 👤 Author

**Hosam Salah**  
📫 [Hosam.s.alsayed@gmail.com](mailto:Hosam.s.alsayed@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/your-link](https://www.linkedin.com/in/hosam-salah-0a6033207/))
📍 Cairo, Egypt
