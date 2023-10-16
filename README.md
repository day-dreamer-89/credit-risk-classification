# credit-risk-classification

##Overview of the Analysis
In this analysis,  conducted an evaluation of machine learning models to predict the credit risk associated with a set of loans. The primary purpose of this analysis was to provide a means for financial institutions to make informed lending decisions and manage credit risk more effectively.

##Financial Information and Data
The dataset used in this analysis contains essential financial information related to loans, including loan size, interest rate, borrower income, debt-to-income ratio, the number of accounts, derogatory marks, and total debt. The key target variable, "loan_status," indicates whether a loan is high-risk (1) or healthy (0).

##Variables Information
loan_size: The size of the loan.
interest_rate: The interest rate associated with the loan.
borrower_income: The income of the borrower.
debt_to_income: The borrower's debt-to-income ratio.
num_of_accounts: The number of accounts the borrower has.
derogatory_marks: The number of derogatory marks on the borrower's credit history.
total_debt: The total debt amount.
loan_status: The target variable, with 0 indicating a healthy loan and 1 indicating a high-risk loan.
Stages of the Machine Learning Process
The machine learning process involved the following stages:
1.Data Preprocessing: We prepared the data by separating features and labels and then split the data into training and testing sets.
2.Model Selection: We opted to use the Logistic Regression model, which is well-suited for binary classification tasks.
3.Model Training: The Logistic Regression model was trained using the training dataset.
4.Model Evaluation: We assessed the model's performance using a confusion matrix and a classification report.
5.Interpretation: We interpreted the results to make recommendations.

##Methods Used
Logistic Regression: We utilized a logistic regression model for binary classification, a fitting choice for predicting the likelihood of high-risk loans based on the provided features.
##Results

###Machine Learning Model 1
Accuracy: 0.99
Precision for Label 0 (healthy loans): 1.00
Precision for Label 1 (high-risk loans): 0.86
Recall for Label 0: 1.00
Recall for Label 1: 0.91
F1-score for Label 0: 1.00
F1-score for Label 1: 0.88
###Machine Learning Model 2
Accuracy: [Insert Model 2 Accuracy]
Precision for Label 0 (healthy loans): [Insert Model 2 Precision for Label 0]
Precision for Label 1 (high-risk loans): [Insert Model 2 Precision for Label 1]
Recall for Label 0: [Insert Model 2 Recall for Label 0]
Recall for Label 1: [Insert Model 2 Recall for Label 1]
F1-score for Label 0: [Insert Model 2 F1-score for Label 0]
F1-score for Label 1: [Insert Model 2 F1-score for Label 1]

##Summary
In summary, our analysis resulted in the evaluation of two machine learning models for predicting high-risk loans. Model 1 stands out with an impressive overall accuracy of 0.99. It exhibits strong precision and recall scores for both label 0 (healthy loans) and label 1 (high-risk loans), making it a suitable choice for various credit risk assessment needs.

The performance of the models depends on the specific objectives of the analysis. If the priority is to minimize the risk associated with high-risk loans, Model 1 is recommended. However, the choice of the model should align with the specific business goals and objectives of the financial institution.

In case none of the models meet the desired performance criteria, further feature engineering, hyperparameter tuning, or the exploration of alternative modeling techniques may be considered to enhance results.

This analysis provides valuable insights for credit risk assessment, enabling more informed lending decisions and better management of credit risk.
