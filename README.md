# Iris Species Classification

This repository contains a comprehensive machine learning study on the classic **Iris Dataset**. I implemented and compared multiple classification algorithms to achieve perfect accuracy in predicting flower species.

## Project Overview
The goal is to classify Iris flowers into three species (**Setosa**, **Versicolor**, and **Virginica**) based on their physical measurements (sepal and petal dimensions).

## Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn
- **Visualization:** Matplotlib, Seaborn

## Machine Learning Pipeline
1. **Data Preprocessing:** Handled features and encoded target labels using `LabelEncoder`.
2. **Feature Scaling:** Applied `StandardScaler` to normalize data for sensitive models like SVM and Logistic Regression.
3. **Modeling:** Implemented and evaluated three different approaches:
   - **Gaussian Naive Bayes** (Probabilistic)
   - **Logistic Regression** (Linear)
   - **Support Vector Machines - SVC** (Margin-based)
4. **Evaluation:** Used Confusion Matrix and Classification Report (Precision, Recall, F1-Score).

## Results
All models achieved **100% accuracy** on the test set, demonstrating that the features (especially petal width/length) provide clear boundaries between species.

| Model | Accuracy |
| :--- | :--- |
| GaussianNB | 1.00 |
| Logistic Regression | 1.00 |
| SVM (SVC) | 1.00 |

## 🔗 Dataset Source
The data is sourced from the [UCI Machine Learning Repository / Kaggle](https://www.kaggle.com/datasets/uciml/iris).

---
*Created by Mehmet Cem Ediboglu
