This is the baseline model No Hyperparameter tuning done on the model. Submission got a score of 0.7022 Rank 642 out of 2649 Competitors (as at 23/09/2021)

This model didn't do very Good.
Everything it predicted was positive.

## For the h1n1_vaccine prediction
Training Score:  0.9431352970544183
====================================================================================================
Mean ROC AUC: 0.85050
====================================================================================================
Confusion Matrix
 [[4946  317]
 [ 698  716]]
====================================================================================================
Classification Report 
               precision    recall  f1-score   support

           0       0.88      0.94      0.91      5263
           1       0.69      0.51      0.59      1414

    accuracy                           0.85      6677
   macro avg       0.78      0.72      0.75      6677
weighted avg       0.84      0.85      0.84      6677


## For the seasonal_vaccine prediction

Training Score:  0.9002496255616576
====================================================================================================
Mean ROC AUC: 0.84515
====================================================================================================
Confusion Matrix
 [[2924  715]
 [ 744 2294]]
====================================================================================================
Classification Report 
               precision    recall  f1-score   support

           0       0.80      0.80      0.80      3639
           1       0.76      0.76      0.76      3038

    accuracy                           0.78      6677
   macro avg       0.78      0.78      0.78      6677
weighted avg       0.78      0.78      0.78      6677