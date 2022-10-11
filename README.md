# Fraudulent-Transaction-Prediction
# Problem Statement: 
This case requires to develop a model for predicting fraudulent transactions for a financial company. 

**Dataset**: Data for the case is available in CSV format having 63,62,620 rows and 10 columns.

# Data Dictionary:

**step** - maps a unit of time in the real world. In this case 1 step is 1 hour of time. Total steps 744 (30 days simulation).

**type** - CASH-IN, CASH-OUT, DEBIT, PAYMENT and TRANSFER.

**amount** - amount of the transaction in local currency.

**nameOrig** - customer who started the transaction

**oldbalanceOrg** - initial balance before the transaction

**newbalanceOrig** - new balance after the transaction

**nameDest** - customer who is the recipient of the transaction

**oldbalanceDest** - initial balance recipient before the transaction. Note that there is not information for customers that start with M (Merchants).

**newbalanceDest** - new balance recipient after the transaction. Note that there is not information for customers that start with M (Merchants).

**isFraud** - This is the transactions made by the fraudulent agents inside the simulation. In this specific dataset the fraudulent behavior of the agents aims to profit by taking control or customers accounts and try to empty the funds by transferring to another account and then cashing out of the system.

**isFlaggedFraud** - The business model aims to control massive transfers from one account to another and flags illegal attempts.

# Approach:
Steps to approach the problem:

1. **Libraries**: Imported required libraries such as Pandas, NumPy, Matplotlib, Seaborne, and Sklearn.
2. **Data Exploration**: Explored data using above mentioned libraries.
3. **Data Visualization**: Visualized data using matplotlib and seaborne.
4. **Model Traing**: Applied Logistic Regression to train the model.
5. **Evaluation of the model**: Evaluation is done by using metrics such as accuracy score, precision score and recall score.

# Conclusion:
Developed a machine learning model using logistic regression. Evaluated the performance of the model using an accuracy score which is 91.9%, a precision score which is 88.5%, and a recall score which is 96.4%.

