This model didn't do very Good even in training, Submission got a score of 0.6415 0.5000
Everything it predicted was positive.

## For the h1n1_vaccine prediction
Training Score:  0.7873190214677983
====================================================================================================
Mean ROC AUC: 0.51269
====================================================================================================
Confusion Matrix
 [[5263    0]
 [1414    0]]
====================================================================================================
Classification Report 
               precision    recall  f1-score   support

           0       0.79      1.00      0.88      5263
           1       0.00      0.00      0.00      1414

    accuracy                           0.79      6677
   macro avg       0.39      0.50      0.44      6677
weighted avg       0.62      0.79      0.69      6677


## For the seasonal_vaccine prediction

Training Score:  0.5308537194208687
====================================================================================================
Mean ROC AUC: 0.68920
====================================================================================================
Confusion Matrix
 [[3639    0]
 [3038    0]]
====================================================================================================
Classification Report 
               precision    recall  f1-score   support

           0       0.55      1.00      0.71      3639
           1       0.00      0.00      0.00      3038

    accuracy                           0.55      6677
   macro avg       0.27      0.50      0.35      6677
weighted avg       0.30      0.55      0.38      6677