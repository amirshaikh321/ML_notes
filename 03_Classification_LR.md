# Classification Logic
Unlike Linear Regression, Classification predicts a category.
# Logistic Regression
Despite its name, it is a classification algorithm. It uses the Sigmoid Function to output a probability between 0 and 1.$$S(z) = \frac{1}{1 + e^{-z}}$$Getty Images
![alt text](image.png)
- If $P \ge 0.5$, Class = 1.
- If $P < 0.5$, Class = 0.

## Decision Trees
These split data based on feature values.Entropy: A measure of disorder/impurity.Information Gain: The reduction in entropy after a split. We want the split that maximizes Information Gain.