# Measuring Model Performance
Accuracy is often misleading, especially with imbalanced datasets (e.g., detecting a rare disease).
# The Confusion Matrix
| | Predicted Positive | Predicted Negative |
|---|---|---|
| **Actual Positive** | True Positive (TP) | False Negative (FN) |
| **Actual Negative** | False Positive (FP) | True Negative (TN) |

## Key FormulasPrecision: 
- $\frac{TP}{TP + FP}$ (Accuracy of positive predictions).
- Recall (Sensitivity): $\frac{TP}{TP + FN}$ (Ability to find all positive instances).
- F1-Score: $2 \times \frac{Precision \times Recall}{Precision + Recall}$ (Harmonic mean of both).
- Specificity: $\frac{TN}{TN + FP}$ (Ability to find all negative instances).