This is the baseline model No Hyperparameter tuning done on the model. Submission got a score of 0.6415.

The model isn's that bad actually, let's see how it'll perform when we tune it.

## For the h1n1_vaccine prediction
Training Score:  1.0
====================================================================================================
Mean ROC AUC: 0.85385
====================================================================================================
Confusion Matrix
 [[5055  208]
 [ 767  647]]
====================================================================================================
Classification Report 
               precision    recall  f1-score   support

           0       0.87      0.96      0.91      5263
           1       0.76      0.46      0.57      1414

    accuracy                           0.85      6677
   macro avg       0.81      0.71      0.74      6677
weighted avg       0.84      0.85      0.84      6677


## For the seasonal_vaccine prediction
Training Score:  1.0
====================================================================================================
Mean ROC AUC: 0.84828
====================================================================================================
Confusion Matrix
 [[2953  686]
 [ 742 2296]]
====================================================================================================
Classification Report 
               precision    recall  f1-score   support

           0       0.80      0.81      0.81      3639
           1       0.77      0.76      0.76      3038

    accuracy                           0.79      6677
   macro avg       0.78      0.78      0.78      6677
weighted avg       0.79      0.79      0.79      6677
