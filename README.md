# 🏦 Credit Risk Modeling (Give Me Some Credit)

## 📌 Objective

Build a machine learning model to predict loan default risk and help financial institutions minimize losses while maintaining a balance between risk detection and customer approval.

---

## 📊 Dataset

* Source: Kaggle – Give Me Some Credit
* Problem Type: Binary Classification
* Target: `SeriousDlqin2yrs` (1 = Default, 0 = No Default)

---

## ⚙️ Workflow

### 1. Data Preprocessing

* Handled missing values (median imputation)
* Treated outliers (income capping, invalid values fixed)
* Feature scaling using StandardScaler

### 2. Handling Class Imbalance

* Used class weighting
* Applied SMOTE (Synthetic Minority Oversampling)

### 3. Models Used

* Logistic Regression
* Decision Tree
* Random Forest (Best Model)

---

## 📈 Model Performance

* **Best Model:** Random Forest
* **AUC Score:** ~0.85
* **Recall (Defaulters):** ~80%

---

## 🔍 Key Insights

* Past repayment behavior is the strongest predictor of default
* High credit utilization indicates financial stress
* Income alone is not a strong indicator of risk

---

## 🧠 Learnings

* Accuracy is misleading for imbalanced datasets
* Recall is critical in credit risk modeling
* Threshold tuning significantly impacts business outcomes

---

## 🛠 Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Imbalanced-learn

---

## 🚀 Future Improvements

* Hyperparameter tuning
* Feature engineering
* Deployment as a simple API

---
