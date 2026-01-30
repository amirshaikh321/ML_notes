# Topic: Probability-based classification.

# Naïve Bayes Classifier
Naïve Bayes is a probabilistic classifier based on Bayes' Theorem. It is called "Naïve" because it assumes that all features are independent of each other, which is rarely true but works surprisingly well in practice.

## 1. Bayes' Theorem Formula
$$P(A|B) = \frac{P(B|A)P(A)}{P(B)}$$P(A|B): Posterior probability (Probability of hypothesis A given evidence B).P(B|A): Likelihood.P(A): Prior probability.

## 2. Use Cases
- Spam Filtering: Predicting if an email is spam based on word frequencies.
- Sentiment Analysis: Categorizing text as Positive, Negative, or Neutral.
- Real-time Prediction: Because it is very fast and requires low computational power.