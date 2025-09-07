# 🚰 Predicting Water Potability with Machine Learning

## 📖 Project Overview
This project uses machine learning to predict whether water is safe to drink, based on 9 chemical/physical features (pH, hardness, solids, sulfate, etc.). Dataset: [Kaggle Water Potability](https://www.kaggle.com/datasets/adityakadiwal/water-potability).

## ⚙️ Methods
- Exploratory Data Analysis (EDA): distributions, correlations, class imbalance
- Data preprocessing: imputation, scaling
- Models: Logistic Regression (baseline), Random Forest
- Evaluation: Accuracy, Precision, Recall, F1, ROC AUC

## 📊 Results
- Logistic Regression: **52% accuracy** (balanced but weak overall)
- Random Forest: **67% accuracy**, high precision (70%) but low recall (29%) for potable water
- Key predictors: pH, Sulfate, Solids

## 🔮 Insights & Next Steps
- Predicting potability is challenging due to class imbalance
- Random Forest is better at avoiding false positives
- Future work: SMOTE oversampling, hyperparameter tuning, try Gradient Boosting

## 🛠️ Tech Stack
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
