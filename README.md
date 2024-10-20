# **Loan Approval Prediction**
This repository contains a machine learning project aimed at predicting loan approvals. The dataset was obtained from Kaggle, and the project was completed as part of a Kaggle competition challenge.

# **Project Overview**
The goal of this project is to predict whether a loan will be approved based on various features like applicant information, loan amount, and credit history. The following key steps were performed:

* Data preprocessing: Handling missing values, encoding categorical features, and feature scaling.
* Model training: Using CatBoost, a powerful gradient boosting algorithm.
* Model evaluation: Evaluating model performance with metrics such as accuracy, confusion matrix, and classification report.

# **Features**
The dataset contains the following features:

* Gender: Male/Female
* Married: Marital status of the applicant
* Dependents: Number of dependents
* Education: Graduate/Not Graduate
* Self_Employed: Whether the applicant is self-employed
* ApplicantIncome: Income of the applicant
* CoapplicantIncome: Income of the coapplicant (if any)
* LoanAmount: Loan amount applied for
* Loan_Amount_Term: Term of the loan
* Credit_History: History of previous loan repayment
* Property_Area: Urban, Semiurban, or Rural area
* Loan_Status: Target variable (1: Approved, 0: Not Approved)

# **Libraries Used**
* pandas
* numpy
* scikit-learn
* CatBoost
* matplotlib
* seaborn
  
# **Project Structure**
Loan_Approval_Predictions_GoogleColab.ipynb: Jupyter notebook containing the code for data preprocessing, model training, and evaluation.

# **Model Performance**
The model was trained using CatBoost, and the accuracy on the validation set was evaluated using various metrics. The final predictions were made on the test dataset provided by Kaggle.

# **Reference**
This project was completed as part of a Kaggle competition. The dataset was collected from [Kaggle](https://www.kaggle.com/competitions/playground-series-s4e10), and the model was developed as an independent challenge submission.
