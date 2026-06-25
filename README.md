# Loan Approval Prediction Case Study

## 📌 Project Overview

This project aims to predict whether a loan application will be approved based on borrower characteristics using supervised machine learning techniques. The analysis focuses on data preprocessing, handling class imbalance, model comparison, and business interpretation of results.

## 🎯 Objectives

* Clean and preprocess loan application data.
* Handle missing values and categorical variables.
* Address class imbalance using resampling techniques.
* Build and compare multiple classification models.
* Evaluate model performance using business-relevant metrics.
* Provide deployment recommendations based on model outputs.

## 📂 Dataset

Dataset Source: Kaggle Loan Approval Prediction Case Study

Dataset Link:
https://www.kaggle.com/datasets/bhanupratapbiswas/loan-approval-prediction-case-study

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Imbalanced-learn (SMOTE)
* Jupyter Notebook

## 🔄 Data Preprocessing

### Missing Value Treatment

* Numerical features filled using median values.
* Categorical features filled using mode values.

### Feature Engineering

* Label Encoding
* One-Hot Encoding

### Feature Scaling

* StandardScaler applied to numerical variables.

### Class Imbalance Handling

* SMOTE Oversampling
* Class Weight Adjustment
* Comparison with Original Dataset

## 🤖 Models Implemented

### 1. Logistic Regression

* Baseline model
* Easy interpretation

### 2. Decision Tree Classifier

* Handles non-linear relationships
* Feature importance analysis

### 3. Random Forest Classifier

* Ensemble learning
* Improved generalization

## 📊 Evaluation Metrics

The following metrics were used:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score

## 📈 Visualizations

* Loan Approval Distribution
* Correlation Heatmap
* Feature Importance Plot
* Confusion Matrix
* ROC Curve Comparison
* Class Imbalance Visualization

## 🔍 Key Findings

* Income and credit history strongly influence loan approval.
* Handling class imbalance improves recall.
* Random Forest generally achieves better ROC-AUC scores.
* Logistic Regression provides better interpretability.

## 💼 Business Interpretation

* High recall reduces rejection of eligible applicants.
* High precision reduces risk of approving risky loans.
* Threshold tuning can balance business risk and customer acquisition.

## 🚀 Deployment Recommendation

Suggested Model: Random Forest Classifier

Suggested Threshold: 0.60

Reason:

* Good balance between precision and recall.
* Lower risk of approving high-risk borrowers.
* Better business performance than default threshold (0.50).

## 📁 Repository Structure

├── Loan_Approval_Prediction.ipynb

├── dataset(link provided above)/

├── report.pdf

└── README.md

## ▶️ How to Run

1. Clone the repository.
2. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
```

3. Open Jupyter Notebook.
4. Run all cells sequentially.

## 📌 Author

Santhosh R

B.Tech – Information Science & Engineering

Presidency University
