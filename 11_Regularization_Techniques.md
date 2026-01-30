# Topic: Preventing Overfitting.
## Regularization: Ridge and Lasso
Regularization adds a penalty to the Loss Function to discourage models from becoming too complex.

1. Ridge Regression (L2 Regularization)
- Adds a penalty equal to the square of the magnitude of coefficients.
- Keeps all features but minimizes their impact.
- Formula: $Loss + \lambda \sum (\text{weight})^2$

2. Lasso Regression (L1 Regularization)
- Adds a penalty equal to the absolute value of the magnitude of coefficients.
- Can force some coefficients to zero, effectively performing Feature Selection.
- Formula: $Loss + \lambda \sum |\text{weight}|$