# Week17-CreditRisk

## Background
Credit risk is an inherently unbalanced classification problem, as the number of good loans easily outnumber the number of risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. Your final task is to evaluate the performance of these models and make a recommendation on whether they should be used to predict credit risk.

## Objectives
The goals of this challenge are for you to:

-Implement machine learning models.

-Use resampling to attempt to address class imbalance.

-Evaluate the performance of machine learning models.

## Analysis

### Describe the precision and recall scores

- Random Oversampling:  99% precision, 61% recall, 75% F1. 
- SMOTE Oversampling:  99% precision, 69% recall, 81% F1.
- Undersampling:  99% precision, 41% recall, 58% F1
- Combination:  99% precision, 58% recall, 73% F1

### Final Recommendation and justification

SMOTE oversampling would be the most ideal as it has the highest balanced accuracy score for the overall model.



