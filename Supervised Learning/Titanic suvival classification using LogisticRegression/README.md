# 🚢 Titanic Survival Prediction using Logistic Regression

## 📋 Project Overview

This notebook performs binary classification on the **Titanic dataset** to predict whether a passenger survived based on features like age, fare, class, sex, and more.

The primary machine learning algorithm used is **Logistic Regression**, suitable for binary outcome problems.

---

## 📦 Libraries Used

- **Pandas** & **NumPy** for data handling
- **Matplotlib** & **Seaborn** for data visualization
- **Scikit-learn** for machine learning

---

## 📊 Dataset: Titanic (`titanic.csv`)

### Initial Observations:
- Dropped irrelevant or sparse columns like `Cabin`
- Checked data types and null values using `.info()`

---

## 🧼 Data Preprocessing

Steps (some done, some commented for optional use):
- Dropping unnecessary columns: `Cabin`, `Name`, `Ticket`
- Label Encoding for categorical columns: `Sex`, `Embarked`, `Ticket`
- Missing value imputation (e.g., `Age`, `Embarked`) — optional

---

## 🧠 Model Training

- Target Variable: `Survived`
- Features: All other relevant numeric and encoded categorical features
- Split: 80% training, 20% testing using `train_test_split`
- Model: `LogisticRegression` from `sklearn.linear_model`
- Training: `.fit(x_train, y_train)`

---

## 📈 Evaluation

Used:
- `accuracy_score` from `sklearn.metrics`

Sample output:
```python
accuracy_score(y_test, y_pred)
# Output: e.g., 78.21% (actual may vary)
