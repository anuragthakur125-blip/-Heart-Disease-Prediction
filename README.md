# Heart Disease Prediction

This project focuses on predicting the presence of heart disease using supervised machine learning classification techniques.

## Project Overview

The project uses patient data to build classification models that predict whether heart disease is present or not. The analysis includes data splitting, Decision Tree classification, tree pruning, and hyperparameter optimization using GridSearchCV.

## Machine Learning Techniques

- Decision Tree Classifier
- Decision Tree with Pruning
- Decision Tree with GridSearchCV

## Project Workflow

1. Split the dataset into training and testing sets
2. Build a Decision Tree using the Entropy criterion
3. Visualize the Decision Tree
4. Generate predictions on the test dataset
5. Evaluate model performance using:
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - Kappa Score
   - AUC
   - ROC Curve
   - Confusion Matrix
6. Apply Decision Tree pruning to reduce model complexity
7. Use GridSearchCV with 10-fold cross-validation to optimize hyperparameters
8. Compare the performance of the models

## Model Optimization

GridSearchCV was used to identify suitable hyperparameters for the Decision Tree, including:

- Criterion
- Maximum depth
- Maximum leaf nodes
- Minimum samples required for splitting
- Minimum samples required at a leaf

## Results

The Decision Tree with GridSearchCV achieved:

- **Accuracy:** 81%
- **Kappa Score:** 0.6218
- **AUC:** 0.7543

The notebook compares different Decision Tree approaches and evaluates their classification performance using multiple metrics.

## Conclusion

The project demonstrates how Decision Tree classification and hyperparameter tuning can be used to predict the presence of heart disease. GridSearchCV was used to optimize the Decision Tree model and improve its performance compared with the basic and pruned Decision Tree models.
