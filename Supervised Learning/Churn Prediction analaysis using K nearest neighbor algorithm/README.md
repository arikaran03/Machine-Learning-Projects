# KNN Churn Prediction Analysis

This project uses the **K-Nearest Neighbors (KNN)** algorithm to analyze customer behavior and predict churn. It helps businesses identify at-risk customers and take proactive measures to retain them.

## 📁 Project Structure

- `chrun_prediction_model.ipynb`: Main Jupyter notebook containing the entire workflow — from data preprocessing to model evaluation.

## 📊 Dataset

The dataset typically includes customer information such as:
- Demographics
- Subscription plan
- Tenure
- Usage patterns
- Support interactions

(You can update this section with your actual dataset or a link to it.)

## 🔍 Model Overview

- **KNN Classifier** is used to classify whether a customer is likely to churn.
- Distance metric: Euclidean
- Scikit-learn's `KNeighborsClassifier` is used.

## ✅ Features

- Data cleaning and preprocessing
- Encoding categorical variables
- Feature scaling using `StandardScaler`
- Model training with KNN
- Evaluation using:
  - Confusion Matrix
  - Accuracy Score
  - Classification Report

## 🛠️ Requirements

Install dependencies with:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
