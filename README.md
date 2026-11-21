Sharing the Loan Prediction project, my data analytics portfolio piece from Business Informatics studies at Yoobee.

The project combines Python machine learning and Power BI to explore a raw dataset of 255,347 loan records and 18 columns. Preprocessing involved dropping the unique LoanID, encoding categorical variables (like Education and Employment Type) into 33 features, and using stratified sampling to handle the highly imbalanced default rate of 11.6%.

One useful finding: the XGBoost model achieved a test ROC-AUC of 0.755, which was only marginally better than the Random Forest (0.754) and Logistic Regression (0.753). The more complex models did not significantly improve predictive performance over the baseline on the holdout evaluation set.

An explainable risk policy produced Low, Medium, High, and Very High risk bands using the predicted probabilities. SHAP analysis identified Age, Interest Rate, and Months Employed as the top drivers of default risk. These are illustrative risk categories requiring human judgement, not automated lending decisions.

For public sharing, I created an aggregate-only edition: summary CSVs of the model comparison, reproducible Python code, feature importance data, Power BI dashboard and a short presentation. I included the original Loan_default raw data CSV File.

GitHub: https://github.com/jeyasriperumalsamynz/MBI806B_Loan-Prediction-with-Power-BI-Dashboard

#DataAnalytics #MachineLearning #PowerBI #Python #DataScience #XGBoost #SHAP #RiskAnalytics #CreditRisk #Portfolio #YoobeeCollege

