<p align="center">
  <img src="online_fraud.jpeg" alt="Online Payment Fraud Detection" width="420"/>
</p>

<h1 align="center">💳 Online Payment Fraud Detection using Machine Learning</h1>

<p align="center">
  Detecting fraudulent online transactions with precision — leveraging data science to protect digital payments.
</p>

---

## 🔍 Project Overview

* **Objective:** Predict whether a given transaction is fraudulent.
* **Dataset:** [Online Payments Fraud Detection Dataset](https://www.kaggle.com/datasets/rupakroy/online-payments-fraud-detection-dataset)
* **Records:** 6,362 transactions
* **Challenge:** High class imbalance (very few fraud cases)

---

## ✨ Key Features

* 📊 **Exploratory Data Analysis (EDA)** to understand transaction patterns
* ⚖️ **Imbalance Handling** using SMOTE & undersampling techniques
* 🤖 **ML Models:** Logistic Regression, Random Forest, Support Vector Machine
* 🧠 **Model Evaluation:** ROC-AUC, Precision, Recall, F1-score
* 📈 **Visual Insights** into feature importance & model performance

---

## 🧰 Tech Stack

| Purpose            | Tools / Libraries                        |
| ------------------ | ---------------------------------------- |
| Programming        | Python 3.x                               |
| Data Processing    | `pandas`, `numpy`                        |
| Visualization      | `matplotlib`, `seaborn`                  |
| Machine Learning   | `scikit-learn`                           |
| Evaluation Metrics | `classification_report`, `roc_auc_score` |

---

## ⚙️ Workflow Summary

```text
1. Import & explore dataset
2. Clean data & analyze imbalance
3. Preprocess data (scaling, encoding)
4. Train models: Logistic Regression, Random Forest, SVM
5. Evaluate using precision, recall, F1, ROC-AUC
6. Visualize metrics & feature importance
```

---

## 📈 Evaluation Metrics

| Metric    | Why It Matters                                      |
| --------- | --------------------------------------------------- |
| Accuracy  | General performance, but not reliable for imbalance |
| Precision | Ensures minimal false fraud alerts                  |
| Recall    | Detects maximum actual frauds (priority!)           |
| F1-Score  | Balances precision and recall                       |
| ROC-AUC   | Measures class separability                         |

---

## 🏆 Results

* Successfully detected **fraud patterns** from imbalanced data
* Achieved **high recall**, crucial in fraud detection scenarios
* **Random Forest** outperformed other models
* Plotted ROC curves and confusion matrices for better explainability

---

## 🚀 Future Improvements

* 🔔 Integrate **real-time fraud alerts** using Flask or Streamlit
* 🔄 Use **ensemble learning** (Bagging, Boosting) for improved performance
* 📊 Develop **interactive dashboards** for business use
* 🧠 Apply **deep learning** for large-scale fraud detection

---

## 📂 Dataset Reference

📎 [Online Payments Fraud Detection Dataset – Kaggle](https://www.kaggle.com/datasets/rupakroy/online-payments-fraud-detection-dataset)

---
