# 📊 Market Type Classification

A machine learning project developed for the PR 2021 Kaggle competition to predict retail product market types using product and outlet characteristics. The project covers the complete data science pipeline, including data preprocessing, feature engineering, model evaluation, and prediction generation.

## 📖 Overview

The objective of this project is to classify retail products into one of four market types using historical product and outlet data. Multiple machine learning models were evaluated, with CatBoost achieving the best performance through its native handling of categorical features and class imbalance.

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* CatBoost
* Matplotlib
* Jupyter Notebook

## 🚀 Key Features

* Performed Exploratory Data Analysis (EDA) to identify missing values, class imbalance, and feature distributions.
* Applied data preprocessing techniques including missing value handling, label standardization, outlier treatment, and Box-Cox transformation.
* Evaluated multiple machine learning models including Gaussian Naïve Bayes, Random Forest, and CatBoost.
* Addressed class imbalance using model weighting techniques.
* Utilized 5-Fold Cross Validation for model evaluation and selection.
* Generated competition-ready predictions for Kaggle submission.

## 📈 Results

* Gaussian Naïve Bayes: Macro F1 Score ≈ 70%
* Random Forest: Macro F1 Score ≈ 85%
* CatBoost: 5-Fold CV Macro F1 Score ≈ 98.9%
* Kaggle Submission Score: **0.99251**

## 🔍 Key Insight

Analysis revealed that Outlet ID was the most influential feature, strongly correlating with market type and significantly improving classification performance.

## 👨‍💻 Team Project

Developed as part of the PR 2021 Product Market Type Classification competition, demonstrating practical applications of machine learning, feature engineering, and predictive analytics.
