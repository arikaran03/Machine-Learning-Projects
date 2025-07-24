# Machine Learning Projects

Welcome to the **Machine Learning Projects** repository! This collection brings together hands‑on projects illustrating core supervised and unsupervised learning techniques. Explore each project’s goal, dataset, modeling approach, and key findings below.

---

## Supervised Learning Projects

### 1. Titanic Survival Prediction (Logistic Regression)
- **Purpose**: Predict which passengers survived the RMS Titanic disaster.
- **Dataset**: Kaggle’s Titanic dataset (passenger demographics and ticket information).
- **Algorithm**: Logistic Regression
- **Key Results**: Achieved an accuracy of ~78% on the test set by engineering features such as passenger class, age ranges, and title extraction.
- **Notebook**: `Supervised Learning/Titanic survival classification using LogisticRegression/titanic_survival_classification_using_logisticRegression.ipynb`

### 2. Diabetes Prediction (Decision Tree)
- **Purpose**: Classify whether a patient has diabetes based on diagnostic measurements.
- **Dataset**: Pima Indians Diabetes Dataset.
- **Algorithm**: Decision Tree Classifier
- **Key Results**: Reached ~72% accuracy; feature importance highlighted glucose and BMI as top predictors.
- **Notebook**: `Supervised Learning/Diabetes Prediction using Decision Tree Classifier/Decision tree classifier.ipynb`

### 3. Churn Prediction (K-Nearest Neighbors)
- **Purpose**: Identify customers likely to cancel a subscription/service.
- **Dataset**: Synthetic telecom customer data (activity logs, demographics).
- **Algorithm**: K-Nearest Neighbors
- **Key Results**: Best performance with K=7 neighbors, yielding ~85% accuracy.
- **Notebook**: `Supervised Learning/Churn Prediction analysis using K nearest neighbor algorithm/churn_prediction_model.ipynb`

### 4. Lung Cancer Detection (Random Forest)
- **Purpose**: Diagnose presence of lung cancer from clinical features.
- **Dataset**: UCI Lung Cancer Dataset.
- **Algorithm**: Random Forest Classifier
- **Key Results**: Achieved ~90% accuracy with an ensemble of 100 trees.
- **Notebook**: `Supervised Learning/Lung cancer analysis using Random forest algorithm/RandomForestClassifier.ipynb`

### 5. Real Estate Price Prediction (Linear Regression)
- **Purpose**: Predict housing prices based on property attributes.
- **Dataset**: Real estate transaction data (size, location, age).
- **Algorithm**: Linear Regression
- **Key Results**: R² score of 0.76; area and location were strongest predictors.
- **Notebook**: `Supervised Learning/Real estate price prediction analysis using Linear Regression/real_estate_price_prediction_using_LinearRegression.ipynb`

---

## Unsupervised Learning Projects

### 1. Customer Segmentation (K-Means Clustering)
- **Purpose**: Group customers into segments for targeted marketing.
- **Dataset**: Retail customer purchase history (RFM metrics).
- **Algorithm**: K-Means Clustering
- **Key Results**: Identified four segments (e.g., high‑value loyalists, price‑sensitive occasional buyers).
- **Notebook**: `Unsupervised Learning/Customer Segmentation Using KMeans Clustering/Customer Segmentation Using KMeans Clustering-checkpoint.ipynb`

### 2. Market Basket Analysis (Apriori Algorithm)
- **Purpose**: Discover association rules between frequently co‑purchased items.
- **Dataset**: Transactional retail dataset.
- **Algorithm**: Apriori
- **Key Results**: Rules such as {Bread → Butter} with 0.6 support and 0.75 confidence.
- **Notebook**: `Unsupervised Learning/Market basket analysis using Apriori algorithm/Market_basket_analysis_using_apriori_algorithm-checkpoint.ipynb`

---

_For detailed dependencies and environment setup, refer to individual project README files._  
