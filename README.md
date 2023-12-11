# credit-risk-classification
# Overview:
 In this Challenge, we will use various techniques to train and evaluate a model based on loan risk. we will use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

 ## Flow Steps of the analysis
    1-Split the Data into Training and Testing Sets

    2-Create a Logistic Regression Model with the Original Data

    3-Write a Credit Risk Analysis Report

## ML Model 1:
### Summary Results

                      precision recall  f1-score   support

           0           1.00      0.99      1.00     18765
           1           0.85      0.91      0.88       619

    accuracy                               0.99     19384
    macro avg          0.92      0.95      0.94     19384
    weighted avg       0.99      0.99      0.99     19384


## ML Model 2:
### Summary Results

                     precision    recall  f1-score   support

              0       1.00      1.00      1.00     18759
              1       0.87      1.00      0.93       625

         accuracy                           1.00     19384
        macro avg       0.94      1.00      0.96     19384
     weighted avg       1.00      1.00      1.00     19384


### Data Analysis Report
#### Logistic Regression Model with the Original Data
the logistic regression model performs very well in predicting both healthy loans (label "0") and high-risk loans (label "1"). The model has high precision and recall for both classes, resulting in an overall accuracy of 99% and strong F1-scores
#### Predicted Logistic Regression Model with Resampled Training Data
the logistic regression model seems to be performing very well  particularly in correctly identifying healthy loans (label "0"). For high-risk loans (label "1"), while the precision is little bit  lower, the model compensates with a high recall, resulting in a good overall performance.
#### Summary
The logistic regression model trained on resampled data demonstrates enhanced efficacy in addressing imbalanced datasets, specifically in the accurate identification of instances belonging to the minority class, such as high-risk loans. This improvement is notably reflected in the elevated recall for high-risk loans, resulting in superior overall F1-scores and accuracy.



