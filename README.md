## 📌1.Project Overview

This project aims to predict whether a customer is likely to purchase a holiday package based on demographic and behavioral attributes. By analyzing customer data, we can help travel companies optimize their marketing strategies and target potential buyers more effectively.

The dataset comes from Kaggle.

---

## 📊2. ## Dataset

Target Variable: ProdTaken (1 = customer purchased package, 0 = did not purchase)

Features Include:Age, Gender, Marital Status, Income, Number of Trips, Passport, Own Car, Preferred Property Star Rating, Number of Children, Designation Monthly Income, Duration of Pitch, etc.

The dataset is moderately imbalanced, with fewer positive cases (ProdTaken = 1).

---

## ⚙️3. ##Methodology

- **Data Preprocessing**: Handling missing values; Encoding categorical features; Addressing class imbalance using SMOTE

- **Modeling**:Logistic Regression, SVM, Decision Tree, Random Forest, KNN, XGBoost, Gradient Boosting / AdaBoost

- **Hyperparameter Tuning**: Used RandomizedSearchCV with cross-validation

- **Evaluation metrics**: Accuracy, Precision, Recall, F1-score, ROC AUC

---

## 📈4. Results

- **Best models**: Random Forest, KNN, XGBoost

- **ROC AUC**: ~0.94–0.95 (depending on tuned parameters)

Confusion matrices and ROC curves are included in results
