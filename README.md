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
