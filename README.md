# InsuranceClaimsSeverityPrediction

This project develops a machine learning model that predicts insurance claim severity. It uses data from Allstate Claims Severity data, which is available in Kaggle at https://www.kaggle.com/c/allstate-claims-severity/data. The project includes:
- exploring the data such as checking missing values, and outliers. The outliers were handled using interquartile range IQR) approach
- Numerical and catagorical feature selection
- base model development using Random Forest and Gradient Boosting regressors
- hyperparameters tunning using Random Search CV. The Grid Search CV was also tried, but as it took too long time to complete the parameter search, the optimization was aborted. Likewise, my computer's memory wasn't sufficient to model the problem using XGBoost Machine Learning algorithm.
- Of the modelled approaches, the Gradient Boosting regressor with Random Search CV provided better mean square error.
