# Advanced Machine Learning

This directory is dedicated to the implementation and evaluation of advanced machine learning models, focusing on ensemble learning techniques and hyperparameter optimization.

## Contents

*   **[`train.ipynb`](file:///d:/python/advance_ml/train.ipynb)**: A Jupyter notebook implementing ensemble methods and model training pipelines.
*   **[`Iris.csv`](file:///d:/python/advance_ml/Iris.csv)**: The classic Iris flower dataset used for testing and validating classification models.

## Key Concepts Covered

### 1. Ensemble Learning
Ensemble methods combine multiple base models to produce a single optimal predictive model. This notebook implements:
*   **Stacking (Stacked Generalization)**: Combines multiple classification models (e.g., `KNeighborsClassifier`, Support Vector Machine `SVC`) using a meta-learner (`LogisticRegression`) to aggregate predictions and improve overall accuracy.
*   **Bagging (Bootstrap Aggregating)**: Reduces variance using algorithms like `RandomForestClassifier` which trains multiple decision trees on random subsets of the data.
*   **Boosting**: Focuses on sequentially training models, where each subsequent model corrects the errors of its predecessor.

### 2. Hyperparameter Tuning
Optimizing machine learning estimators using Scikit-Learn:
*   **Grid Search (`GridSearchCV`)**: Exhaustive search over specified parameter values for an estimator.
*   **Randomized Search (`RandomizedSearchCV`)**: Randomized search on hyper parameters for faster training and optimization.

## Setup and Requirements

Ensure you have the required Python libraries installed:
```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```
