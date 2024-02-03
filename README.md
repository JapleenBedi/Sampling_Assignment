# Sampling_Assignment
# Project Results

## Dataset Information

The dataset contains 772 entries with two classes: class 0 and class 1. The dataset is imbalanced, with 763 entries for class 0 and only 9 for class 1. SMOTE (Synthetic Minority Oversampling Technique) is used to balance the dataset.

## Sample Size Calculation

The sample size is calculated using the formula: \( n = \frac{Z^2 \cdot p \cdot (1-p)}{E^2} \), where \( n \) is the sample size, \( p \) is the standard deviation, \( Z \) is the z-score, and \( E \) is the margin of error.

## Sampling Techniques

- Simple Random Sampling
- Systematic Random Sampling
- Cluster Sampling
- Bootstrap Sampling

## Models Used for Evaluation

- Logistic Regression
- Support Vector Classifier (SVC)
- XGBoost Classifier
- Random Forest
- Gaussian Naive Bayes

## Accuracy Scores

| \ | Model 1 (LR) | Model 2 (SVC) | Model 3 (XGB) | Model 4 (RF) | Model 5 (GB) |
| --- | --- | --- | --- | --- | --- |
| **Sample 1 (Simple Random)** | 0.87 | 0.93 | 0.94 | 0.99 | 0.78 |
| **Sample 2 (Systematic Random)** | 0.89 | 0.94 | 0.97 | 0.97 | 0.81 |
| **Sample 3 (Cluster Sampling)** | 0.93 | 0.97 | 0.99 | 1 (overfit) | 0.83 |
| **Sample 4 (Bootstrap Sampling)** | 0.95 | 0.95 | 0.96 | 1 (overfit) | 0.87 |

## Conclusion

Based on the evaluation metrics, Bootstrap Sampling is identified as the most effective sampling technique.

Submitted by Japleen Kaur (ID: 102103204).
