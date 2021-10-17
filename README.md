# Credit_Risk_Analysis
## Overview
The purpose of this analysis is to create a supervised machine learning model that could accurately predict credit risk. Six different methods were utilized.

* 1. Naive Random Oversampling
* 2. SMOTE Oversampling
* 3. Cluster Centroid Undersampling
* 4. SMOTEENN Sampling
* 5. Balanced Random Forest Classifying
* 6. Easy Ensemble Classifying

Through each of these methods, the data was split into training and testing datasets. Accuracy scores, confusion matrices and classification reports were compiled in summary form. 

## Deliverable 1
## Use Resampling Models to Predict Credit Risk
![Resources/Naive_Random_Oversampling.jpg](Resources/Naive_Random_Oversampling.jpg)

### Random Oversampling
* Accuracy Score: 67.4%

![Resources/SMOTE_Oversampling.jpg](Resources/SMOTE_Oversampling.jpg)

### SMOTE Oversampling
* Accuracy Score: 68.2%

## Deliverable 2
## Use the SMOTEENN algorithm to Predict Credit Risk

![Resources/Undersampling_Analysis.jpg](Resources/Undersampling_Analysis.jpg)

### Undersampling Analysis
* Accuracy Score: 52.2%

![Resources/SMOTEENN_Analysis.jpg](Resources/SMOTEENN_Analysis.jpg)

### SMOTEENN Analysis
* Accuracy Score: 68.1%

## Deliverable 3
## Use Ensemble Classifiers to Predict Credit Risk

![Resources/Random_Forest_Analysis.jpg](Resources/Random_Forest_Analysis.jpg)

### Random Forest Analysis
* Accuracy Score: 64.8%

![Resources/Easy_Ensemble_Analysis.jpg](Resources/Easy_Ensemble_Analysis.jpg)

### Easy Ensemble Analysis
* Accuracy Score: 92.3%

## Summary

This analysis tries to find the best model that can detect if a loan is high-risk. Because of that, we need to find a model that lets the least amount of high-risk loans pass through undetected. That correlating statistic for this is the recall rate for high-risk. Looking through the different models, the ones that scored the highest were:

* Easy Ensemble Analysis (91%)
* SMOTEENN Analysis (76%)
* SMOTE Oversampling (70%)

While this is the most important statistic that is pulled from this analysis, another important statistic is recall rate for low-risk as it shows how many low-risk loans are flagged as high-risk. Looking through the different models, the ones that scored the highest were:

* Random Forest Analysis (100%)
* Easy Ensemble Analysis (94%)

However, one looks at the accuracy score to get a picture of how well the model performs in general. The models with the highest accuracy scores were:

* Easy Ensemble Analysis (92.3%)
* SMOTE Oversampling (68.2%)
* SMOTEENN Analysis (68.1%)

Therefore the model that is recommended by factoring multiple metrics is the Easy Ensemble Analysis.



