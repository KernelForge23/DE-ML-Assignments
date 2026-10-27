# Data Engineering & Machine Learning Assignments

This repository contains three machine learning assignments completed as part of my **Data Engineering coursework at COEP Technological University**.

The assignments explore three major machine learning approaches: **Classification, Clustering, and Regression**, using Python and popular data science libraries.

## 📂 Assignments Overview

| Assignment | Topic | Algorithms |
|---|---|---|
| 01 | Bank Term Deposit Prediction | Logistic Regression, Decision Tree, KNN, Random Forest, SVM |
| 02 | Customer Segmentation | K-Means, Hierarchical Clustering, DBSCAN |
| 03 | Retail Product Demand Prediction | Linear Regression, Decision Tree, Random Forest, KNN Regressor |

---

## 1. Bank Term Deposit Prediction — Classification

### Objective

Predict whether a customer will subscribe to a bank term deposit based on demographic, financial, and marketing-related attributes.

### Algorithms

- Logistic Regression
- Decision Tree Classifier
- K-Nearest Neighbors (KNN)
- Random Forest Classifier
- Support Vector Machine (SVM)

### Implementation

- Data exploration and preprocessing
- Handling categorical variables using One-Hot Encoding
- Feature scaling using StandardScaler
- Training and testing multiple classification models
- Comparing model performance

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 2. Customer Segmentation — Clustering

### Objective

Segment shopping mall customers into meaningful groups based on demographic characteristics and purchasing behavior.

### Features

- Age
- Annual Income
- Spending Score

### Algorithms

- K-Means Clustering
- Hierarchical (Agglomerative) Clustering
- DBSCAN

### Implementation

- Exploratory Data Analysis (EDA)
- Feature selection and standardization
- Determining cluster count using the Elbow Method
- Evaluating clustering using the Silhouette Score
- Visualizing hierarchical clustering through dendrograms
- Identifying clusters and noise points with DBSCAN
- Analyzing and comparing customer segments

### Evaluation Techniques

- Elbow Method
- Silhouette Score
- Cluster Visualization
- Cluster Characteristics Analysis

---

## 3. Retail Product Demand Prediction — Regression

### Objective

Predict monthly product demand using regression techniques, compare model performance, and analyze the impact of outliers on evaluation metrics.

### Features

- Product Price
- Promotion Status
- Advertising Expenditure

**Target Variable:** Product Demand

### Algorithms

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- K-Nearest Neighbors Regressor

### Implementation

- Generating and preprocessing a synthetic retail demand dataset
- Splitting data into training and testing sets
- Training and evaluating regression models
- Visualizing actual versus predicted demand
- Introducing an artificial outlier into predicted values
- Analyzing the effect of outliers on model performance

### Evaluation Metrics

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Programming language |
| NumPy | Numerical computations |
| Pandas | Data manipulation and analysis |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Machine learning models and evaluation |
| SciPy | Hierarchical clustering and dendrograms |
| Jupyter Notebook | Implementation and experimentation |

## 📚 Key Learning Outcomes

- Data cleaning, preprocessing, and feature selection
- Supervised and unsupervised machine learning
- Implementing classification, clustering, and regression algorithms
- Feature scaling and categorical encoding
- Evaluating and comparing machine learning models
- Visualizing and interpreting model predictions and clusters
- Understanding the sensitivity of regression metrics to outliers

---

## 📌 Note

These assignments were developed for academic learning and experimentation. The regression assignment uses synthetically generated data, while the classification and clustering assignments use publicly available datasets.

The primary focus is on understanding machine learning workflows, implementing algorithms, and interpreting their performance.
