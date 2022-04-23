# Credit_Risk_Analysis
## Overview of the Analysis:
Apply machine learning to solve a real-world challenge: Credit card risk.
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. 
Therefore, I need to employ different techniques to train and evaluate models with unbalanced classes.
Jill asked us to use imbalanced-earn and scikit-learn libraries to build and evaluate models using resampling

## Results:
### Random Naive Sampling
- Accuracy Score: 0.65
- Precision Score - High risk: 0.01, Low risk: 1.00
- Recall Score - High risk: 0.71, Low risk: 0.59
- F1 score: 0.74

![randomoversampling](Resources/randomoversampling.png)

### SMOTE Oversampling
- Accuracy Score: 0.62
- Precision Score - High risk: 0.01, Low risk: 1.00
- Recall Score - High risk: 0.59, Low risk: 0.66
- F1 score: 0.79

![smotoversampling](Resources/smotoversampling.png)

### Undersampling
- Accuracy Score: 0.52
- Precision Score - High risk: 0.01, Low risk: 1.00
- Recall Score - High risk: 0.60, Low risk: 0.43
- F1 score: 0.60

![undersampling](Resources/undersampling.png)

### Combination Sampling
- Accuracy Score: 0.64
- Precision Score - High risk: 0.01, Low risk: 1.00
- Recall Score - High risk: 0.70, Low risk: 0.58
- F1 score: 0.73

![combinationsampling](Resources/combinationsampling.png)

## Summary: 
