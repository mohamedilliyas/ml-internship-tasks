# Task 3: Forest Cover Type Classification

## Objective
Multi-class classification: predict one of 7 forest cover types using cartographic variables only.

## Dataset
- **Forest Cover Type** (covtype.csv)
- 581,012 rows, 54 features, 7 classes
- Source: https://www.kaggle.com/datasets/uciml/forest-cover-type-dataset

## Approach
- EDA & class distribution analysis
- Train / val / test split (stratified)
- Compared: Decision Tree, Random Forest, XGBoost
- Evaluation: Accuracy, Classification Report, Confusion Matrix
- Visualized top feature importances

## Results
- Best model: **XGBoost** / **Random Forest** (~86–89% accuracy)
- Most important features: elevation, soil type indicators, hillshade

## Bonus (optional)
- Hyperparameter tuning with RandomizedSearchCV or Optuna
- Class weight handling for slight imbalance