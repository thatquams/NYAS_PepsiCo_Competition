PROJECT OVERVIEW

This project is a competition hosted by PEPSI, The Aim Of This Project is for each participant to predict the added sugars of their product with over 19,000 rows and 200 columns as features with any algorithm of their choice.
The dataset contains of training and testing data which is to bfed to the model.        The steps taken to achieve the aim of this project are as follow:

1. UNDERSTANDING THE DATA
    a. Read Both training and testing data, and the concatenate them to perform analysis
    b. Performed statistical techniques on the data to better understand the data given
    c. Represented the data in form of graphs and plots to visually understand the data
    d. Visually represent the data to check the correlation between The Features

2. DATA WRANGLING AND PREPROCESSING
    a. Dropping Unnecessary columns
    b. Filling The null Values of each columns
    c. One Hot Encoding columns with categorical features And many more preprocessing steps
    d. Data Segmentation

3. MODEL BUILDING AND EVALUATION
    a. Utilizing The KFold cross validation technique to split the data into folds
    b. Features Normalization
    c. Fit and Predict on the training data
    d. Calculating the metrics using RMSE
    e. Saved The Model with the highest performance

After Performing the cross validation on the data, we instantiated and train The data utilizing the XGBoost And Random Forest regression model, The Xgboost seems to have have higher performance than the Random Forest, so we dumped it into a pickle file using Joblib.
