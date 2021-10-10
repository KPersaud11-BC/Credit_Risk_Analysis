# Credit_Risk_Analysis by Kieran Persaud

## Overview of the Credit Risk Analysis Challenge
In this Challenge, I apply the concepts of Supervised machine learning to evaluate credit card risk. Using the credit card dataset provided, I;
- Oversample the data using the ```RandomOverSampler``` and ```SMOTE``` algorithms, and undersample the data using the ```ClusterCentroids``` algorithm.
- Use a combinatorial approach of over- and undersampling using the ```SMOTEENN``` algorithm. 
- Compare two new machine learning models that reduce bias, ```BalancedRandomForestClassifier``` and ```EasyEnsembleClassifier```, to predict credit risk.

## Resources
- Data Source: LoanStats_2019Q1.csv
- Software: Anaconda 4.10.1, kernels mlenv, ```imbalanced-learn``` and ```scikit-learn``` libraries; Jupyter Notebook

## Results
Below are the results of each of the machine learning models I created in this challenge.

### Naive Random Oversampling

![image](https://user-images.githubusercontent.com/84286467/136702258-82996e19-a07e-4c41-9c28-d1e41c672c04.png)

- Accuracy: 64.6%
- High Risk: Precision: 1% Recall: 63%
- Low Risk: Precision: 100% Recall: 66%

### SMOTE Oversampling

![image](https://user-images.githubusercontent.com/84286467/136702461-0e8a4684-2a5a-46d4-b37b-e02716cf1ee1.png)

- Accuracy: 62.9%
- High Risk: Precision: 1% Recall: 60%
- Low Risk: Precision: 100% Recall: 66%

### Undersampling

![image](https://user-images.githubusercontent.com/84286467/136702610-e65dfc60-0e79-4737-b315-b695f6f702c6.png)

- Accuracy: 52.9%
- High Risk: Precision: 1% Recall: 61%
- Low Risk: Precision: 100% Recall: 45%

### Combination Sampling

![image](https://user-images.githubusercontent.com/84286467/136702666-3a55fcfd-f1ca-45bd-8f41-916fd9a2411b.png)

- Accuracy: 63.6%
- High Risk: Precision: 1% Recall: 69%
- Low Risk: Precision: 100% Recall: 58%

### Balanced Random Forest Classifier

![image](https://user-images.githubusercontent.com/84286467/136702820-1ba5aa29-8600-48d5-8c97-07bfaac1fe19.png)

- Accuracy: 78.8%
- High Risk: Precision: 4% Recall: 67%
- Low Risk: Precision: 100% Recall: 91%

### Easy Ensemble Classifier

![image](https://user-images.githubusercontent.com/84286467/136702875-84570591-ec70-44a2-839b-0fd5d39a7868.png)

- Accuracy: 92.5%
- High Risk: Precision: 7% Recall: 91%
- Low Risk: Precision: 100% Recall: 94%

## Summary
