# Support Vector Machines (SVM) - Breast Cancer Classification

## Overview

This project demonstrates the use of Support Vector Machines (SVM) for binary classification using the Breast Cancer Wisconsin dataset. The objective is to build models with both linear and RBF kernels, evaluate them using accuracy and confusion matrices, and tune hyperparameters to improve performance.

---

## Dataset

- **Source**: `sklearn.datasets.load_breast_cancer()`
- **Features**: 30 numerical measurements (e.g., radius, texture, concavity)
- **Target**:
  - `0`: Malignant
  - `1`: Benign
- No missing values and all features are continuous.

---

## Objectives

- Train an SVM classifier using both **linear** and **RBF kernels**
- Standardize features for optimal performance
- Evaluate accuracy and classification report
- Perform hyperparameter tuning with `GridSearchCV`
- Visualize decision boundaries using two features
- Understand the impact of `C` and `gamma` on the model

---

## Files Included

- `Day7_SVM.ipynb`: Jupyter notebook with all code, visualizations, and evaluation
- `README.md`: This documentation file

---

## Key Results

- **Linear SVM Accuracy**: High performance with simple decision boundaries
- **RBF SVM Accuracy**: Slightly better classification with flexible boundaries
- **Best Parameters (via Grid Search)**: Optimized model hyperparameters for accuracy
- **Visualization**: 2D plot showing SVM decision boundaries using key features

---

## Conclusion

SVM proved to be an effective and robust classifier for the breast cancer dataset. With proper preprocessing and hyperparameter tuning, it achieved high accuracy and reliability. This task highlighted the importance of choosing the right kernel and tuning key parameters like `C` and `gamma` for non-linear classification problems.
