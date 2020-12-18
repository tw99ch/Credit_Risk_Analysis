# Credit_Risk_Analysis

## Overview of the analysis:
The purpose of the analysis is to use different maching learning techniques, including random oversampling, undersampling, SMOTEENN algorithm, combination, and Ensemble Classifiers: random_forest and easy ensemble adaBoost classifier to train the machine and evaluate models with various lenders' criteria in order determine the best models to predict the credit risk. 

## Results:
- Credit Risk Resampling Techniques
1.  Naive Random Oversampling: accuracy score it 63%, high_risk has a very low precision for prediction at 1% recall(sensitivity) of 59%, and F1 of 2%; low_risk has a high precision for prediction at 100%, recall(sensitivity) is 69% and F1 of 81%.
    ![](/img/Naive_random_oversampling_score.PNG)

2. SMOTE Oversampling: accuracy score it 64%, high_risk has a very low precision for prediction at 1% recall(sensitivity) of 66%, and F1 of 2%; low_risk has a high precision for prediction at 100%, recall is 64% and F1 of 78%.
    ![](/img/SMOTE_oversampling_score.PNG)

3. Undersampling: accuracy score it 59%, high_risk has a very low precision for prediction at 1% recall of 63%, and F1 of 2%; low_risk has a high precision for prediction at 100%, recall(sensitivity) is 56% and F1 of 71%.
    ![](/img/Undersampling_score.PNG)

4. Combination (Over and Under) Sampling: accuracy score it 64%, high_risk has a very low precision for prediction at 1% recall(sensitivity) of 72%, and F1 of 2%; low_risk has a high precision for prediction at 100%, recall(sensitivity) is 57% and F1 of 73%.
    ![](/img/Combination_score.PNG)

- Credit Risk Ensemble Techniques
1. Balanced Random Forest Classifier: accuracy score it 99%, high_risk has higher precision for prediction at 54% recall(sensitivity) of 29%, and F1 of 38%; low_risk has a high precision for prediction at 100%, recall(sensitivity) is 100% and F1 of 100%.
    ![](/img/balance_random_forest_score.PNG)

2. Easy Ensemble AdaBoost Classifier: accuracy score it 91%, high_risk has low precision for prediction at 6% recall(sensitivity) of 91%, and F1 of 11%; low_risk has a high precision for prediction at 100%, recall(sensitivity) is 92% and F1 of 96%.
    ![](/img/Easy_ensemble_adaBoost_classifier_score.PNG)


## Summary:
Based on the above result, resampling techniques have lower accuracy score, lower recall and F1 scores than the Ensemble Techniques. Within Ensemble Techniques, Balanced Random Forest Classifier has better accuracy score than Easy Ensemble AdaBoost Classifier. Balanced Random Forest Classifier also has higher precision for prediction at 54% and recall(sensitivity) of 29% which is better than other models. To sum up, Ensemble Techniques of Balanced Random Forest Classifier has better predictibility over the other models.