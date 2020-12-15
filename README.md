# Rain Prediction using Logistic Regression

## Problem Statement
This project is to answer the question that whether or not it will rain tomorrow in Australia using Logistic Regression with Python and Scikit-Learn.

To answer the question, I build a classifier to predict whether or not it will rain tomorrow in Australia by training a binary classification model using Logistic Regression. I have used the Rain in Australia dataset downloaded from the Kaggle website for this project.

The Python implementation is presented in the Jupyter notebook

## Dataset Description

I have used the Rain in Australia data set downloaded from the Kaggle website.

I have downloaded this data set from the Kaggle website. The data set can be found at the following url:-

https://www.kaggle.com/jsphyg/weather-dataset-rattle-package

This dataset contains daily weather observations from numerous Australian weather stations.

## Results and Conclusion

1. The logistic regression model accuracy score is 0.8506. So, the model does a very good job in predicting whether or not it will rain tomorrow in Australia.

2. Small number of observations predict that there will be rain tomorrow. Majority of observations predict that there will be no rain tomorrow.

3. The model shows no signs of overfitting.

4. Increasing the value of C results in increase in training set accuracy but test set accuracy decreases relative to the default parameters

5. ROC AUC of our model approaches towards 1. So, we can conclude that our classifier does a good job in predicting whether it will rain tomorrow or not.

6. Our original model accuracy score is 0.8506 whereas accuracy score after RFECV is 0.8501. So, we can obtain approximately similar accuracy but with reduced set of features.

7. We can see that in the original model, we have FP = 1462 whereas FP1 = 1476. So, we get approximately higher number of false positives. Also, FN = 3849 whereas FN1 = 3853. So, we get slightly higher false negatives.

8. Our, original model score is found to be 0.8474. The average cross-validation score is 0.8472. So, we can conclude that cross-validation does not result in performance improvement.

9. Our original model test accuracy is 0.8506 while GridSearch CV accuracy is 0.8506. We can see that GridSearch CV does not affect the performance for this particular model.
