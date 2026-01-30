# Topic: The fundamental theory of model error.

The Bias-Variance Tradeoff
Every ML model has two types of error that we try to balance:

1. Bias (Error due to Underfitting)
- Occurs when a model is too simple (e.g., using a linear line for curved data).
- High Bias means the model pays very little attention to the training data.

2. Variance (Error due to Overfitting)
- Occurs when a model is too complex (e.g., a high-degree polynomial).
- High Variance means the model is too sensitive to small fluctuations in the training data.

## The Goal
We want the Sweet Spot where both Bias and Variance are low, resulting in the lowest possible Total Error.