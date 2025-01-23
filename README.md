# Credit-Risk-Analysis-for-Extending-Bank-Loans

# Problem Statement

Credit scoring is a classification problem where the objective is to predict whether or not an individual will default on their credit.
Credit scoring is perhaps one of the most "classic" applications for predictive modeling, to predict whether or not credit extended to an applicant will likely result in profit or losses for the lending institution.
There are many variations and complexities regarding how exactly credit is extended to individuals, businesses, and other organizations for various purposes (purchasing equipment, real estate, consumer items, and so on), and using various methods of credit (credit card, loan, delayed payment plan). But in all cases, the lender provides money to an individual or institution and expects to be paid back in time with interest commensurate with the risk of default.

# About Dataset:

age: Age of the Customers

ed: Education Level

employ: Work Experience

address: Address of the Customer

income: Yearly Income of the customer

debtinc: Debt to Income Ratio

creddebt: Credit to Debt ratio

othdebt: Other debts

default: Customer defaulted in the past (1= defaulted, 0= Never defaulted)

# Overview 
Developed machine learning models to predict loan defaults using imbalanced banking data. Addressed class imbalance with the SMOTE technique to improve the model's ability to identify defaults. 

Implemented Logistic Regression, achieving 74% accuracy and an 83% F1-score as a baseline. Advanced to XGBoost for improved performance, achieving a 91% F1-score after fine-tuning with Grid Search CV. The model helps banks make data-driven decisions, reducing financial risk while maintaining profitability.

# Project Structure
Data Preprocessing:
Handled missing values, encoded categorical variables, and created features such as debt-to-income ratio and total debt.

Models: Implemented two machine learning models:
Logistic Regression for baseline classification. XgBoost Classifier for high-performance classification with hyperparameter tuning.

Regularization:
Applied GridSearchCV to further fine-tune the model with additional regularization parameters.

Evaluation:
The model's performance was evaluated using accuracy, confusion matrix, classification report, and F1-score.
