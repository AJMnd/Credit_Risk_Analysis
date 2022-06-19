# Credit_Risk_Analysis 🚩 💳   🚩

## Overview of the analysis:
Using machine learning, this analyzes credit card risk using six machine learning models.
We have employed different techniques to train and evaluate models with unbalanced classes. 
We are using imbalance-learn and scikit-learn libraries to build and evaluate models using resampling. 

## Results:

A low precision is indicative of a large number of false positives.

A low recall is indicative of a large number of false negatives. 


| Model      | Balanced Accuracy Score | Precision   |  Recall  | F1 |
| :---       |     ----:               |         ---:|     ---: |   ---: |
| Oversampling     | 64%      | 0.99   | 0.60 | 0.74
| SMOTE | 66% | 0.99 | 0.69 | 0.81 |
|ClusterCentroid | 66% | 0.99 | 0.40 | 0.56 |
|SMOTEENN | 54% | 0.99 | 0.57 | 0.72 |
|Balanced Random Forest | 68% | 1.00 | 1.00 | 1.00
| AdaBoost | 69%   | 1.00  | 1.00 | 1.00 |

## Summary: 
The models with the highest F1 score were Balanced Random Classifier and AdaBoost both with an F1 score of 1.00. However, SMOTE had an F1 score of 0.81 and a low recall of 0.69. Indicating that SMOTE is a more accurate model. 
![](/https://github.com/AJMnd/Credit_Risk_Analysis/blob/main/Resources/Rfc.png)

![](/https://github.com/AJMnd/Credit_Risk_Analysis/blob/main/Resources/Rfc.png)

![](/https://github.com/AJMnd/Credit_Risk_Analysis/blob/main/Resources/SMOTE.png)
