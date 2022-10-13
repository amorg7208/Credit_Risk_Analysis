# Credit_Risk_Analysis

## Overview of the Loan Prediction Risk Analysis:
Utilize Python to evaluate machine learning models to analyze credit risk via oversampling, undersampling, the SMOTEENN algorithm, and compare two machine learning models BalancedRandomForestClassifier and EasyEnsembleClassifier. 

## Results:

### Naive Random Oversampling
1. Balance Accuracy Score:
  * 0.6428089407802233
3. Precision Score: 
  * Low Risk: High (1.00)
  * High Risk: Low (0.01)
5. Recall Score:
  * Low Risk: 0.61
  * High Risk: 0.68
<img width="667" alt="Screen Shot 2022-10-12 at 2 19 26 PM" src="https://user-images.githubusercontent.com/106630710/195450079-f4ac7ace-4b6e-42e6-a599-92b3823eab48.png">

### SMOTE Oversampling model
1. Balance Accuracy Score:
  * 0.6201205828911692
3. Precision Score: 
  * Low Risk: High (1.00)
  * High Risk: Low (0.01)
5. Recall Score:
  * Low Risk: 0.60
  * High Risk: 0.64
<img width="663" alt="Screen Shot 2022-10-12 at 2 20 19 PM" src="https://user-images.githubusercontent.com/106630710/195450224-9ccbf1c8-0b56-449a-9498-603bcf3baa85.png">

### Cluster Centroids model
1. Balance Accuracy Score:
  * 0.6201205828911692
3. Precision Score: 
  * Low Risk: High (1.00)
  * High Risk: Low (0.01)
5. Recall Score:
  * Low Risk: 0.43
  * High Risk: 0.59
<img width="659" alt="Screen Shot 2022-10-12 at 2 21 24 PM" src="https://user-images.githubusercontent.com/106630710/195450381-487c9fcd-bb73-4730-aa89-daeadcce1b2f.png">

### SMOTEENN model
1. Balance Accuracy Score:
  * 0.5103309281216384
3. Precision Score: 
  * Low Risk: High (1.00)
  * High Risk: Low (0.01)
5. Recall Score:
  * Low Risk: 0.59
  * High Risk: 0.71
<img width="661" alt="Screen Shot 2022-10-12 at 2 22 08 PM" src="https://user-images.githubusercontent.com/106630710/195450480-f7fcf6e6-0a81-43ca-b04f-750128f5eee7.png">

### BalancedRandomForestClassifier model
1. Balance Accuracy Score:
  * 0.7877672625306695
3. Precision Score: 
  * Low Risk: High (1.00)
  * High Risk: Low (0.04)
5. Recall Score:
  * Low Risk: 0.91
  * High Risk: 0.67
<img width="660" alt="Screen Shot 2022-10-12 at 2 22 47 PM" src="https://user-images.githubusercontent.com/106630710/195450589-078f69a7-dcc9-45de-97ec-f12284149368.png">

### EasyEnsembleClassifier model
1. Balance Accuracy Score:
  * 0.925427358175101
3. Precision Score: 
  * Low Risk: High (1.00)
  * High Risk: Low (0.07)
5. Recall Score:
  * Low Risk: 0.94
  * High Risk: 0.91
<img width="666" alt="Screen Shot 2022-10-12 at 2 23 24 PM" src="https://user-images.githubusercontent.com/106630710/195450680-13c217a6-450f-401a-9098-c98b07d8c7cc.png">

## Summary:
Since the EasyEnsembleClassifier model has a Balance Accuracy Score closest to 1 (0.93), this is the best model to choose. Comparatively, the other models all have Balance Accuracy Scores less than 0.79. Looking at the Precision Scores doesn't tell us much since they are all similar. However, the Recall Score for the EasyEnsembleClassifier model stands out as it is the closest to 1. This analysis showcases the EasyEnsembleClassifier model is the best option.
