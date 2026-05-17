# 📉 Customer Churn Prediction

A machine learning project to predict whether a telecom customer is likely to churn, using the IBM Telco Customer Churn dataset. Four classification models are built, evaluated, and compared to identify the best performer.

---

## 📌 Project Overview

Customer churn is one of the biggest challenges in the telecom industry. This project builds a predictive model that identifies at-risk customers before they leave, enabling businesses to take proactive retention steps.

---

## 🗂️ Dataset

- **Source:** IBM Sample Dataset — Telco Customer Churn (`WA_Fn-UseC_-Telco-Customer-Churn.csv`)
- **Features:** Customer demographics, account information, and services subscribed
- **Target:** `Churn` (Yes / No)

---

## 🔧 Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core language |
| Pandas & NumPy | Data manipulation |
| Matplotlib & Seaborn | Data visualization |
| Scikit-learn | Model building & evaluation |

---

## 🚀 Workflow

1. **Data Loading & Exploration** — Shape, info, and first look at the data
2. **Data Cleaning** — Handle missing values in `TotalCharges`, drop `customerID`
3. **EDA** — Visualize churn distribution across features
4. **Preprocessing** — Label encoding for categorical variables, StandardScaler for feature scaling
5. **Model Building** — Train four classifiers:
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - Support Vector Machine (RBF kernel)
6. **Evaluation** — Compare models on Accuracy, Precision, Recall, and F1-Score
7. **Prediction** — Predict churn for a sample customer using the best model

---

## 📊 Model Comparison

| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------|-----------|--------|----------|
| Logistic Regression | - | - | - | - |
| Decision Tree | - | - | - | - |
| Random Forest | - | - | - | - |
| SVM | - | - | - | - |

> 📝 Run the notebook to populate the results table with actual values.

---

## ✅ Results

The best model is selected based on **F1-Score**, which balances precision and recall — important in churn prediction where both false positives and false negatives matter.

---

## 📁 Project Structure

```
customer-churn-prediction/
│
├── Cusromer_churn_prediction_project.ipynb   # Main notebook
├── WA_Fn-UseC_-Telco-Customer-Churn.csv      # Dataset
└── README.md
```

---

## 🏃 How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/hemanthtangudu94-oss/customer-churn-prediction.git
   ```
2. Install dependencies
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Open the notebook
   ```bash
   jupyter notebook Cusromer_churn_prediction_project.ipynb
   ```

---

## 👤 Author

**Hemanth Tangudu** — [GitHub](https://github.com/hemanthtangudu94-oss)
