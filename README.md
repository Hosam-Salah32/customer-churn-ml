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

# ⚙️ Project Workflow

An all-in-one machine learning pipeline for **customer churn prediction**.  
Easily configurable and designed for **single-line execution**, with options for:
- Data cleaning & preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature engineering  
- Imbalanced data handling (SMOTE)  
- Model training with cross-validation  
- Model comparison (Accuracy, Recall, AUC)  
- Voting Classifier for ensemble performance  
- Feature importance visualization  

---

## 🚀 Features
- **Plug-and-play**: run with just a CSV file path.
- **Configurable**: choose whether to use feature engineering, SMOTE, and which models to train.
- **Comprehensive EDA**: churn distributions, categorical breakdowns, correlation heatmaps.
- **Multiple Models** out of the box:
  - Logistic Regression
  - Random Forest
  - Gradient Boosting
  - Support Vector Machine
  - K-Nearest Neighbors
  - Naive Bayes
  - XGBoost *(optional, if installed)*
- **Automatic Model Selection**: highlights the best-performing model.
- **Voting Classifier**: combines models for better performance.
- **Visual Results**: comparison plots and confusion matrices.

---

## 📂 Usage

### Quick Run

```python
from churn_pipeline import ChurnPipeline

pipeline = ChurnPipeline("WA_Fn-UseC_-Telco-Customer-Churn.csv")
results = pipeline.run()
```

### Compare Configurations

```python
from churn_pipeline import compare_configurations

results = compare_configurations("WA_Fn-UseC_-Telco-Customer-Churn.csv")
```

### Example Output

* **Best Model:** Random Forest
* **Test Recall:** 0.81
* **Test AUC:** 0.85
* **Confusion Matrix & Feature Importances** plotted automatically

---

## 📊 Example Visuals

* Churn distribution pie chart
* Boxplots of tenure/monthly charges by churn
* Correlation heatmap
* Model comparison bar plots
* Confusion matrix

---

## 🔮 Roadmap

* [ ] Add hyperparameter tuning (GridSearch / Optuna)
* [ ] Add support for deep learning models (TensorFlow / PyTorch)
* [ ] Add pipeline export for deployment

---

## 👤 Author

**Hosam Salah**

📫 [Hosam.s.alsayed@gmail.com](mailto:Hosam.s.alsayed@gmail.com)

🔗 [LinkedIn](https://www.linkedin.com/in/your-link](https://www.linkedin.com/in/hosam-salah-0a6033207/))
📍 Cairo, Egypt
