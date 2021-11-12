# Credit_Risk_Analysis

## Overview
In this analysis Jill wants to understand how all the factors in loan applications database helps predict whether the applicant is highly likely to fail in loan payment. The method that was used was imbalanced-learning and scikit-learn libraries to build models and evalute them using a resampling method. 

## Results
- **Naive Random Oversampling results:** 
  - Balanced accuracy test it 66.6%
  - Precision for the high_risk has a very low positivity at 1% and the recall is 70%

![image](https://user-images.githubusercontent.com/84694664/141409679-4af336ab-b53b-4774-9fe2-dae7e9138caf.png)

- **SMOTE oversampling results: **
  - Accuracy score is 66.2%
  - Precision for the high_risk loans has a low positvity again at 1% and recall is 63% overall
  
![image](https://user-images.githubusercontent.com/84694664/141409819-5398111c-eb5b-4f62-ab15-e6b88eb331c0.png)

- **Undersampling results: **
  - Balanced accuracy score is 66.2% overall 
  - Precision is at 99% and the recall is 40%

![image](https://user-images.githubusercontent.com/84694664/141410386-b697c7c5-58ea-46b6-b6ca-2dfb55f4eddf.png)

- **Combination(over and undersampling) results: **
  - Balanced accuracy score is 54.7% 
  - Precision is 99% and the recall is 57% overall

![image](https://user-images.githubusercontent.com/84694664/141410493-9980f1b0-f058-4074-8079-a3b1242b61ff.png)

- **Balanced Random Forest Classifier results: **
  - Accuracy score is 77.46% 
  - Precision is 99% and the recall is 88%
  
![image](https://user-images.githubusercontent.com/84694664/141410577-6461ac81-b523-4f74-a109-dbf84bc67383.png)

- **Easy Ensemble AdaBoost Classifier results: **
  - Accuracy score is 91.7% 
  - Precision is 99% and the recall is 94%
 
![image](https://user-images.githubusercontent.com/84694664/141410904-5cd2c0be-32ac-4370-a5d9-9a2b6492fc69.png)

## Summary
- The first four models does not have a high accuracy score as the ensemble classifiers and the recall in the oversampling/undersampling/mixed models is low as well. 
- The recommendation would be to use Easy Ensemble since it had the best balance of all the models because of it's high accuracy score and good balance of precision and recall scores.


