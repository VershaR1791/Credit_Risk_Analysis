# Credit_Risk_Analysis

## Overview
In this analysis Jill wants to understand how all the factors in loan applications database helps predict whether the applicant is highly likely to fail in loan payment. The method that was used was imbalanced-learning and scikit-learn libraries to build models and evalute them using a resampling method. 

## Results
- Naive Random Oversampling results: 
  - Balanced accuracy test it 66.6%
  - Precision for the high_risk has a very low positivity at 1% and the recall is 70%

![image](https://user-images.githubusercontent.com/84694664/141409679-4af336ab-b53b-4774-9fe2-dae7e9138caf.png)

- SMOTE oversampling results: 
  - Accuracy score is 66.2%
  - Precision for the high_risk loans has a low positvity again at 1% and recall is 63% overall
  
![image](https://user-images.githubusercontent.com/84694664/141409819-5398111c-eb5b-4f62-ab15-e6b88eb331c0.png)
