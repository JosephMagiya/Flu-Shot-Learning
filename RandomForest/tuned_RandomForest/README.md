# Intro
This is the tuned Random Forest Model.
There's some lift in the Mean ROC AUC for both the h1n1 & seasonal_vaccine predictions
### Submission got a score of 0.7337.

The model isn's that bad actually, let's see how it'll perform when we tune it.

## For the h1n1_vaccine prediction
Training Score: 0.89
====================================================================================================
Mean ROC AUC: 0.86259
====================================================================================================
Confusion Matrix
 [[3058  113]
 [ 442  394]]
====================================================================================================
Classification Report 
               precision    recall  f1-score   support

           0       0.87      0.96      0.92      3171
           1       0.78      0.47      0.59       836

    accuracy                           0.86      4007
   macro avg       0.83      0.72      0.75      4007
weighted avg       0.85      0.86      0.85      4007

## For the seasonal_vaccine prediction
Training Score: 0.86
====================================================================================================
Mean ROC AUC: 0.85663
====================================================================================================
Confusion Matrix
 [[1757  402]
 [ 461 1387]]
====================================================================================================
Classification Report 
               precision    recall  f1-score   support

           0       0.79      0.81      0.80      2159
           1       0.78      0.75      0.76      1848

    accuracy                           0.78      4007
   macro avg       0.78      0.78      0.78      4007
weighted avg       0.78      0.78      0.78      4007
