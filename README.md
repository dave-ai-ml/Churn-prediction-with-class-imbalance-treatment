# Churn-prediction-with-class-imbalance-treatment

Problem Statement
Telecommunications industry experiences an average of 15-25% annual churn rate.
It costs 5-10 times more to acquire a new customer than to retain an existing one.
Customer retention is therefore a major focus area.
Analyse customer data of a telecom firm. Build predictive models to identify customers at high risk of churn and identify the main indicators of churn.
In the Indian and the Southeast Asian market, 80-20 rule plays out in the telecom churn. For instance, approximately 80% of revenue comes from the top 20% customers. These top 20% are the so called high-value customers. Thus, if we can reduce churn of the high-value customers, we will be able to reduce significant revenue leakage.
After filtering the high-value customers, you should get about 29.9k rows.
Objective
To reduce customer churn, need to predict which customers are at high risk of churn.
Retaining high value customers is key requirement.
Churn prediction is usually more critical for prepaid customers. This must be taken care while defining churn.
Usage-based definition to define churn
Predict the churn in the last (i.e. the ninth) month using features from the first three months.
Goals
Predict whether a high-value customer will churn or not
Identify important variables that are strong predictors of churn
Table of Contents

1.Importing & Data Understanding
2. Data Cleaning
2.1 DatetimeIndex
2.2 Filter High Value Customers
2.3 Tag Churners
2.4 Handling of missing values
2.5 Churn imbalance
2.6 Outlier Analysis
3. EDA and Data Visualization
4. Goal-1: Churn Prediction
4.1 Derive New Features
4.2 Train Test Split
4.3 PCA for Dimensionality Reducion
4.4 Model-1 Churn Prediction: PCA, Logistic Regression, Class Weight Balanced
4.5 Model-2 Churn Prediction: PCA, Logistic Regression, Hyper Parameter Tuning
4.6 Model-3 Churn Prediction: Undersampling, PCA, Logistic Regression
4.7 Model-4 Churn Prediction: Oversampling, PCA, Logistic Regression
4.8 Model-5 Churn Prediction: SMOTE, PCA, Logistic Regression
4.9 Model-6 Churn Prediction: PCA, Random Forest, Class Weight Balanced, Hyper Parameter Tuning
4.10 Summary: Goal-1 Churn Prediction
5. Goal-2: Identify important predictor attributes
5.1 Logistic Regression without PCA
5.2 Decision Trees
5.3 Random Forest
5.4 Important Features
6. Conclusion & Recommendations
