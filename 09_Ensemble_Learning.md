# Ensemble Learning Techniques
Ensemble methods combine multiple machine learning models to create a single, more powerful model.

1. Bagging (Bootstrap Aggregating)
Concept: Train multiple versions of the same model on different subsets of the data (with replacement) and average their results.

Key Algorithm: Random Forest. It builds many Decision Trees and lets them "vote" on the final classification. It is excellent for reducing Variance (overfitting).

2. Boosting
Concept: Train models sequentially. Each new model attempts to correct the errors made by the previous model.

Key Algorithms: * AdaBoost: Increases the weight of misclassified points.

XGBoost / Gradient Boosting: Uses Gradient Descent to minimize loss when adding new models. Excellent for winning Kaggle competitions.