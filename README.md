# Credit_Risk_Analysis

## Overview
Apply machine learning to predict someone's credit risk (either High-Risk or Low-Risk). Use imbalanced-learn and scikit-learn libraries to build and evaulate models using resampling. 

Resampling algorithms: 
- Oversample: RandomOverSampler, SMOTE
- Undersample: ClusterCentroids 
- Combo: SMOTEENN 

Esemble algorithms:
- BalancedRandomForestClassifier
- EasyEnsembleClassifier 

## Results

### Naive Random Oversampling
- Balanced Accuracy Score = 63%

- High-Risk
  - Precision = 1% 
  - Recall = 66% 
 
- Low-Risk
  - Precision = 100%
  - Recall = 59% 
  
![](/images/random_over.png)


### SMOTE Oversampling
- Balanced Accuracy Score = 66%

- High-Risk
  - Precision = 1% 
  - Recall = 63% 
 
- Low-Risk
  - Precision = 100%
  - Recall = 69% 
![](/images/smote.png)


### Cluster Centroids Undersampling
- Balanced Accuracy Score = 55%

- High-Risk
  - Precision = 1% 
  - Recall = 68% 
 
- Low-Risk
  - Precision = 100%
  - Recall = 41% 
![](/images/cluster_centroid.png)


### SMOTEENN Combination (Over and Under)
- Balanced Accuracy Score = 66%

- High-Risk
  - Precision = 1% 
  - Recall = 66% 
 
- Low-Risk
  - Precision = 78%
  - Recall = 54% 
![](/images/combo.png)


### Balanced Random Forest Classifier
- Balanced Accuracy Score = 79%

- High-Risk
  - Precision = 3% 
  - Recall = 70% 
 
- Low-Risk
  - Precision = 100%
  - Recall = 87% 
![](/images/rf.png)


### Easy Ensemble AdaBoost Classifier 
- Balanced Accuracy Score = 93%

- High-Risk
  - Precision = 9% 
  - Recall = 92% 
 
- Low-Risk
  - Precision = 100%
  - Recall = 94% 
![](/images/easy.png)


## Summary 
