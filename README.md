# task--4
# Logistic Regression - Binary Classification Task

## Objective:
Build a binary classifier using logistic regression on the Breast Cancer dataset.

## Dataset:
Used the built-in Breast Cancer Wisconsin Dataset from `sklearn.datasets`.

## Steps Followed:
1. Loaded dataset and split into train and test sets.
2. Standardized the features.
3. Trained a Logistic Regression model.
4. Evaluated using:
   - Confusion Matrix
   - Precision
   - Recall
   - ROC-AUC
5. Tuned decision threshold.
6. Plotted ROC curve.

## Libraries Used:
- pandas
- numpy
- matplotlib
- sklearn

## Sigmoid Function:
The sigmoid function is used in logistic regression to map the linear combination of features to a probability between 0 and 1.

\[
\sigma(z) = \frac{1}{1 + e^{-z}}
\]

## Evaluation:
- Confusion Matrix shows TP, TN, FP, FN.
- Precision: TP / (TP + FP)
- Recall: TP / (TP + FN)
- ROC Curve helps visualize model performance at different thresholds.
