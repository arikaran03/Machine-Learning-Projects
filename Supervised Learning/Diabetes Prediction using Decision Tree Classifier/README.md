# Diabetes Prediction using Decision Tree Classifier

This project performs binary classification to predict whether a patient has diabetes using a decision tree model. The dataset used is the well-known **Pima Indians Diabetes Dataset**.

## 📊 Dataset

- The dataset is loaded from a CSV file: `diabetes.csv`
- The target column is `Outcome`, where:
  - 1 = Positive for diabetes
  - 0 = Negative for diabetes

## 🔍 Data Processing

- Features (`x`) and target (`y`) are separated.
- Data is split into training and testing sets using an 80/20 ratio.

## 🧠 Model

- A `DecisionTreeClassifier` from `sklearn.tree` is used.
- The model is trained on the training set and tested on the test set.

## ✅ Evaluation

- The model’s performance is measured using `accuracy_score` from `sklearn.metrics`.

## 📈 Visualization

- The decision tree structure is exported using `export_graphviz` and visualized with `graphviz`.

## 🛠 Libraries Used

- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `sklearn.model_selection`, `sklearn.tree`, `sklearn.metrics`
- `graphviz`

