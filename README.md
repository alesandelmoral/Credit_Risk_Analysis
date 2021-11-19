# Credit_Risk_Analysis

## Overview of the analysis
The Purpose of this analysis is to evaluate some models with unbalanced classes with some machine learning models. After that, compare the models in order to know the bias reduction in order to predict credict risk. Once that is done, it is necessary to evaluate the performance of each models and whether or not they should be used to predict any kind of risk.

## Results:

- **Oversampling**
Using oversampling, it can be observed that the high risk precision is 1%, its recall is 69%, while the low risk has a 100% precision but the recall has 60% of accuracy.

![oversampling](https://github.com/alesandelmoral/Credit_Risk_Analysis/blob/main/Images/oversampling.PNG)

- With SMOTE oversampling, the high risk precision is 1% and the recall is 63%. The low risk has a precision of 100% while the recall is 69%.

![SMOTE_oversampling](https://github.com/alesandelmoral/Credit_Risk_Analysis/blob/main/Images/SMOTE_oversampling.PNG)

- Undersampling presents an accuracy in high risk precision of 1% and a recall of 69%. The low risk presents a precision of 100% and a recall of 39%.

![Undersampling](https://github.com/alesandelmoral/Credit_Risk_Analysis/blob/main/Images/Undersampling.PNG)

- In the case of combination sampling (under and oversampling), high risk precision has a percentage of 1% and the recall 72%. The low risk presents a precision of 100% but the recall is 57%.

![combination_sampling](https://github.com/alesandelmoral/Credit_Risk_Analysis/blob/main/Images/combination_sampling.PNG)

- Using balanced ramdom forest, presents a high risk precision of 3% and a recall of 70%. The low risk has a precision of 100% and a recall of 87%. In this case, the high risk precision improved a bit.

![balanced_random_forest](https://github.com/alesandelmoral/Credit_Risk_Analysis/blob/main/Images/balanced_random_forest.PNG)

- AdaBoost, has a high risk precision of 9% and a recall of 92%, it also has a low risk of 100% and a recall of 94%. This improved also a little.

![AdaBoost](https://github.com/alesandelmoral/Credit_Risk_Analysis/blob/main/Images/AdaBoost.PNG)

## Summary:
With this results, using the F1 as a metric, and considering the respective precision and recall, the models with most improvements were the Balanced Random Forests and the AdaBoost. Even if those models were the ones that presented a significant accuracy, none of the models should be used to predict the high risks due to the low precision in the respective risk percentage.