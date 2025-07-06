# Random Forest Classifier for Lung Cancer Survey Analysis

This project uses a **Random Forest Classifier** to analyze data from a lung cancer survey and predict whether an individual is likely to be affected based on various medical and lifestyle factors.

## 📁 Project Structure

- `RandomForestClassifier.ipynb`: File containing data preprocessing, model training, and evaluation steps using the Random Forest algorithm.

## 📊 Dataset

The dataset contains medical and behavioral information such as:
- Age
- Smoking habits
- Anxiety and chronic disease history
- Fatigue levels
- Wheezing and coughing patterns

(You can update this section with a dataset link or description if available.)

## 🔍 Model

The model uses **Random Forest**, an ensemble machine learning method:
- Handles classification tasks efficiently.
- Reduces overfitting compared to individual decision trees.
- Provides feature importance.

## ✅ Features

- Data loading and preprocessing
- Label encoding for categorical features
- Train-test split
- Model training using `RandomForestClassifier` from `sklearn`
- Evaluation using accuracy score, confusion matrix, and classification report

## 🛠️ Requirements

To run this notebook, install the following:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
