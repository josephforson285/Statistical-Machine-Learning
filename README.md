# Statistical Machine Learning Projects

This repository contains two Statistical Machine Learning (SML) projects developed as part of coursework and self-study.  
The work combines **theoretical foundations**, **data analysis**, and **empirical evaluation** of learning algorithms.

---

## 📘 Project 1: Credit Card Default Prediction

This project focuses on predicting whether a credit card client will default on their next payment using real-world financial data.

### Key aspects
- Dataset: Taiwan Credit Card Default dataset (UCI ML Repository)
- Problem type: **Binary classification**
- Strong emphasis on **probability estimation** rather than only class labels

### Methods used
- Logistic Regression (baseline and ridge-regularised)
- k-Nearest Neighbours (kNN)
- Random Forest

### Core components
- Data cleaning, scaling, and feature selection
- Handling class imbalance
- Cross-validation and hyperparameter tuning
- Model comparison using ROC–AUC, accuracy, sensitivity, and specificity
- Statistical interpretation and deployment considerations

### Key takeaway
Nonlinear models (Random Forest) outperform linear models, highlighting the importance of interaction effects in credit-risk prediction.

---

## 📗 Project 2: High-Dimensional Learning & kNN Theory

This project explores **high-dimensional statistical learning** and the behavior of learning algorithms under different data regimes.

### Part A: High-Dimensional Prostate Cancer Data
- Dataset with **p ≫ n** (500 predictors, 79 samples)
- Gene expression measurements
- Analysis includes:
  - Univariate screening (Kruskal–Wallis test)
  - Correlation and eigendecomposition
  - kNN classifiers with different k
  - Classification trees with varying pruning levels
  - ROC analysis and stochastic holdout evaluation
  - Bias–variance tradeoff interpretation

### Part B: kNN Theory and Regression
- Mathematical interpretation of kNN classifiers
- Connection between kNN classification and posterior probability estimation
- Regression simulation with known Bayes optimal function
- Comparison of kNN, linear regression, polynomial regression, and regression trees
- Empirical validation of Bayes risk

### Key takeaway
In high-dimensional settings, flexible models may overfit, and proper resampling-based evaluation is essential for reliable conclusions.

---

## 🛠️ Tools & Libraries
- R, RMarkdown
- caret, glmnet, randomForest
- class, rpart, ROCR, pROC
- ggplot2

---
