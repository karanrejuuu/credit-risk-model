# 📊 Credit Risk Prediction Model

A machine learning project to predict the probability of loan default using real-world financial data.

---

## 🚀 Overview

This project focuses on building a credit risk model that helps identify whether a borrower is likely to default on a loan.

The goal is not just accuracy, but **detecting high-risk customers effectively**, which is critical in real-world financial decision-making.

---

## 📂 Dataset

This project uses the **"Give Me Some Credit"** dataset from Kaggle.

**Download:** https://www.kaggle.com/c/GiveMeSomeCredit/data

### Setup Instructions:

1. Download the dataset from the link above
2. Place `cs-training.csv` inside the `data/` folder
3. Run the notebook

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib / Seaborn

---

## ⚙️ Project Workflow

### 1. Data Preprocessing

* Handled missing values (`MonthlyIncome`, `NumberOfDependents`)
* Treated outliers (income capping, invalid age fixes)
* Feature scaling using StandardScaler

### 2. Exploratory Data Analysis (EDA)

* Checked class imbalance (~93% non-default, ~7% default)
* Visualized feature distributions and correlations

### 3. Model Building

* Logistic Regression (primary model)
* Linear models for baseline comparison

### 4. Model Evaluation

* Confusion Matrix
* Precision & Recall
* Focus on **recall for defaulters** (business-critical metric)

---

## 📈 Key Insight

In credit risk problems, **recall is more important than accuracy**.

Missing a defaulter can lead to financial loss, so the model prioritizes identifying high-risk customers even if it slightly increases false positives.

---

## 📊 Results

* Successfully handled class imbalance
* Built a baseline risk prediction model
* Improved understanding of real-world ML trade-offs

---

## 📁 Project Structure

```
credit-risk-model/
│
├── data/
│   └── cs-training.csv
│
├── notebooks/
│   └── credit-risk.ipynb
│
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

```bash
git clone https://github.com/your-username/credit-risk-model.git
cd credit-risk-model
pip install -r requirements.txt
jupyter notebook
```

---

## 🔗 Future Improvements

* Handle imbalance using SMOTE / undersampling
* Try advanced models (Random Forest, XGBoost)
* Hyperparameter tuning
* Deploy as a simple web app

---

## 🤝 Connect

If you have feedback or suggestions, feel free to connect or open an issue.

---

## ⭐ If you found this useful, consider giving it a star!
