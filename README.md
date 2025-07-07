# customer-churn-ml

# 📊 Customer Churn Prediction with Machine Learning

## 🧠 Overview

This project focuses on predicting **customer churn** in the telecom industry using various machine learning models. Churn prediction is crucial for telecom companies to proactively retain customers and reduce revenue loss.

The project compares several models, handles class imbalance, and selects the best-performing one based on F1-score and ROC AUC.

---

## 🗂️ Dataset

- 📌 Source: [WA_Fn-UseC_-Telco-Customer-Churn.csv](https://www.kaggle.com/datasets/palashfendarkar/wa-fnusec-telcocustomerchurn)
- 💡 7,000+ customer records with 21 features including:
  - Demographics (gender, age, etc.)
  - Account details (tenure, contract type)
  - Services (internet, phone)
  - Target: `Churn` (Yes/No)

---

## 📈 Models Used

| Model                | F1-score | ROC AUC |
|---------------------|----------|---------|
| Logistic Regression | 0.78     | 0.78    |
| Random Forest       | 0.86     | 0.86    |
| SVM                 | 0.85     | 0.85    |
| XGBoost             | **0.86** | **0.86** |
| Voting Classifier   | 0.85     | 0.846   |
| Stacking Classifier | 0.85     | 0.850   |

📌 **Best Model**: `XGBoost` due to its high performance, generalization ability, and interpretability.

---

## ⚙️ Features of the Project

- Exploratory Data Analysis (EDA) and visualization
- Handling missing data and categorical encoding
- Addressing class imbalance using **SMOTE**
- Model training, evaluation, and comparison
- Ensemble methods: Voting and Stacking classifiers
- Evaluation using:
  - F1-score
  - ROC AUC
  - Confusion Matrix

---

## 🧪 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/customer-churn-ml.git
   cd customer-churn-ml
````

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Launch the notebook:

   ```bash
   jupyter notebook churn-prediction.ipynb
   ```

---

## 🧠 Why XGBoost?

Due to the dataset's mix of numeric and categorical variables, potential outliers, and non-linear relationships, XGBoost stood out as the best choice. It offers:

* High performance (F1: 0.86, ROC AUC: 0.86)
* Regularization to prevent overfitting
* Compatibility with class-imbalanced datasets
* Feature importance analysis for business insights

---

## ✅ Conclusion

This project demonstrates how ML can empower customer retention efforts. By accurately predicting which users are likely to churn, businesses can design proactive strategies to improve satisfaction and reduce loss.

---

## 🔮 Next Steps

* Add SHAP values for interpretability
* Deploy using Streamlit or Flask
* Train on a larger, more recent dataset

---

## 📌 Author

**Hosam Salah**
📫 [Hosam.s.alsayed@gmail.com](mailto:Hosam.s.alsayed@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com) | 🧠 Aspiring Data Scientist | 📍 Cairo, Egypt

```

---

Let me know if:
- You want a `requirements.txt` file created from your notebook.
- You want this as a downloadable `.md` file.
- You’re ready to upload to GitHub and want a checklist for that.

You're right at the finish line, Sam 👏
```
