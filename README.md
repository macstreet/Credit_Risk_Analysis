# Credit Risk Analysis

## Overview of the Analysis

This analysis utilizes six different machine learning models to predict credit risk. Each model will be have its balance accuracy, precision, and sensitivity calclulated in order to determine its successfulness. 

## Results

Below is a review of balanced accuracy, the precision, and recall scores of all six machine learning models used in this analysis. Screenshots of the classification reports are also attached to their respective machine learning model. 

### Oversampling: RandomOversampler
- Balanced Accuracy Score: 0.65
- Precision Score: 0.99
- Recall Score: 0.68

**Classification Report:**
![ROS CR](/Images/1_ROS.png)



### Oversampling: SMOTE
- Balanced Accuracy Score: 0.64
- Precision Score: 0.99
- Recall Score: 0.66

**Classification Report:**
![SMOTE CR](/Images/2_SMOTE.png)


### Undersampling: ClusterCentroids
- Balanced Accuracy Score: 0.53
- Precision Score: 0.99
- Recall Score: 0.45

**Classification Report:**
![Undersample CR](/Images/3_Undersampling.png)


### Combination (Over/Under) Sampling: SMOTEENN
- Balanced Accuracy Score: 0.64
- Precision Score: 0.99
- Recall Score: 0.57

**Classification Report:**
![SMOTEENN CR](/Images/4_SMOTEENN.png)


### Ensemble Learners: Balanced Random Forest Classifier
- Balanced Accuracy Score: 0.79
- Precision Score: 0.99
- Recall Score: 0.91

**Classification Report:**
![BRFC CR](/Images/5_BRFC.png)


### Ensemble Learners: Easy Ensemble AdaBoost Classifier
- Balanced Accuracy Score: 0.93
- Precision Score: 0.99
- Recall Score: 0.94

**Classification Report:**
![EE CR](/Images/6_EasyEnsemble.png)


# Summary

All of the resampling models (Oversampling, )