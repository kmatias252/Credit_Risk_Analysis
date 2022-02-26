# Credit_Risk_Analysis

## Overview of Credit Risk Analysis: 

The overall objective was to apply our machine learning skills to predict credit risk. Using the credit card dataset from LendingClub, a peer-to-peer lending services company, I had to oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, I used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Lastly, I compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier to predict credit risk. 

## Results: 

### Naive Random Oversampling 

•	Balanced Accuracy Score: 64.2%

•	Precision for High Risk: 1%

•	Precision for Low Risk: 100%

•	Recall Score for High Risk: 60%

•	Recall Score for Low Risk: 69%  

<img width="715" alt="Screen Shot 2022-02-20 at 11 49 41 AM" src="https://user-images.githubusercontent.com/91925639/154854467-aa03f926-fcad-4e41-85ec-410d8aef306a.png">

### SMOTE Oversampling

•	Balanced Accuracy Score: 62.7%

•	Precision for High Risk: 1%

•	Precision for Low Risk: 100%

•	Recall Score for High Risk: 62%

•	Recall Score for Low Risk: 63%  

<img width="711" alt="Screen Shot 2022-02-20 at 12 13 11 PM" src="https://user-images.githubusercontent.com/91925639/154878776-fb0d5a18-3e49-468c-8dc5-f7b4d0fa652c.png">

### Undersampling

•	Balanced Accuracy Score: 51.0%

•	Precision for High Risk: 1%

•	Precision for Low Risk: 100%

•	Recall Score for High Risk: 59%

•	Recall Score for Low Risk: 43% 

<img width="719" alt="Screen Shot 2022-02-20 at 12 16 24 PM" src="https://user-images.githubusercontent.com/91925639/154878862-f960d607-a4e2-42a5-918d-76c177fbd4cd.png">

### Combination (Over and Under) Sampling

•	Balanced Accuracy Score: 62.4% 

•	Precision for High Risk: 1%

•	Precision for Low Risk: 100% 

•	Recall Score for High Risk: 70%

•	Recall Score for Low Risk: 55%

<img width="708" alt="Screen Shot 2022-02-20 at 12 17 46 PM" src="https://user-images.githubusercontent.com/91925639/154878904-230e6603-c08c-4ed7-98ae-bf4df776ff80.png">

## Ensemble Learners:

### Balanced Random Forest Classifier

•	Balanced Accuracy Score: 78.8% 

•	Precision for High Risk: 4%

•	Precision for Low Risk: 100%

•	Recall Score for High Risk: 67%

•	Recall Score for Low Risk: 91%

<img width="714" alt="Screen Shot 2022-02-20 at 12 19 13 PM" src="https://user-images.githubusercontent.com/91925639/154878934-5bba9f36-c034-437d-b583-21eda2ed5562.png">

### Easy Ensemble AdaBoost Classifier

•	Balanced Accuracy Score: 92.0% 

•	Precision for High Risk: 7% 

•	Precision for Low Risk: 100% 

•	Recall Score for High Risk: 90% 

•	Recall Score for Low Risk: 94%  

<img width="713" alt="Screen Shot 2022-02-20 at 12 19 47 PM" src="https://user-images.githubusercontent.com/91925639/154878954-23264f52-a864-4fed-a939-f4033595b7cd.png">

## Summary: 

Based on our analysis, the machine learning model with the overall highest accuracy, precision and recall for both high risk and low risk credit was the Easy Ensemble AdaBoost Classifier. Although the precision for high risk credit is not very high for the Ensemble AdaBoost Classifier model (0.07), it is still the highest amongst the models we analyzed. Overall, I would recommend the Easy Ensemble AdaBoost Classifier model as a good method for assessing high and low risk credit. The model I would least recommend would be the Undersampling model which yielded the lowest balanced accuracy score and lowest recall out of all the models.
