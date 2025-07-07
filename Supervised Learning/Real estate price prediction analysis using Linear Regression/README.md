# 🏠 Real Estate Price Prediction using Linear Regression

## 📋 Project Overview

This project aims to build a simple yet effective **Linear Regression** model to predict real estate prices based on property size. The dataset used contains information about house prices and their corresponding sizes.

---

## 🧰 Libraries Used

- `pandas` – Data manipulation
- `numpy` – Numerical operations
- `matplotlib.pyplot` & `seaborn` – Visualization
- `scikit-learn` – Machine learning

---

## 📊 Data Summary

- Loaded dataset: `real_estate_price_size.csv`
- Features: `size` (independent variable), `price` (target)

Initial data visualizations:
- **Scatter plot** to view the relationship between `size` and `price`
- **Boxplot** to detect outliers in `price`

---

## 🔧 Data Preprocessing

- Split data into feature (`X = size`) and target (`y = price`)
- Train-test split with **80% training** and **20% testing** using `train_test_split`

---

## 🧠 Model: Linear Regression

- Trained a **LinearRegression** model from `sklearn.linear_model`
- Fitted on `x_train`, `y_train`
- Predicted house prices on `x_test`

---

## 📈 Evaluation

You can use `r2_score`, `mean_squared_error`, or `visual plots` to evaluate performance. (The code seems to stop before evaluation in the current notebook.)

---

## 🖼️ Visualizations Included

- 🔴 Scatter Plot of `price` vs. `size`
- 📦 Boxplot to inspect outliers in `price`

---

## ✅ Conclusion

A simple linear regression model was successfully trained to understand the relationship between house size and price. Further improvements could include:
- Feature scaling
- Outlier removal
- Adding more features like location, number of rooms, etc.

---

*Created with ❤️ using Python, Pandas, Seaborn, and scikit-learn*
