This is the tuned xgboost model. Submission got a score of 0.6928 

This model didn't do very Good.
Everything it predicted was positive.

## For the h1n1_vaccine prediction
Training Score: 0.94
====================================================================================================
Mean ROC AUC: 0.85121
====================================================================================================
Confusion Matrix
 [[2981  190]
 [ 385  451]]
====================================================================================================
Classification Report 
               precision    recall  f1-score   support

           0       0.89      0.94      0.91      3171
           1       0.70      0.54      0.61       836

    accuracy                           0.86      4007
   macro avg       0.79      0.74      0.76      4007
weighted avg       0.85      0.86      0.85      4007


## For the seasonal_vaccine prediction

Training Score: 0.89
====================================================================================================
Mean ROC AUC: 0.84921
====================================================================================================
Confusion Matrix
 [[1710  449]
 [ 463 1385]]
====================================================================================================
Classification Report 
               precision    recall  f1-score   support

           0       0.79      0.79      0.79      2159
           1       0.76      0.75      0.75      1848

    accuracy                           0.77      4007
   macro avg       0.77      0.77      0.77      4007
weighted avg       0.77      0.77      0.77      4007