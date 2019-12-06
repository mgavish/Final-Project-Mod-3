# Introduction

The goal of this classification project was to predict whether a person would submit a claim or not. 

Multiple permutations of several models, including Logistic Regression, Random Forest and XGBoost did not produce significant results and therefore we must conclude the data is not predictive.  The iterations were initially split between those using sklearn's SMOTE to upsample the minority target class and using python's `.resample()`, which are the titles of the respective notebooks.  A snapshot of each models score may be viewed in the 'Results_Snapshot.xlsx' file.  Grid Search on XGBoost produced the best results. 

However, we did gain insight on useful and superfluous features and can begin to focus energy on collecting more data for those.  We can also work on identifying new data points and feature engineering to produce a data set that will be predictive and answer our questions with confidence.  



