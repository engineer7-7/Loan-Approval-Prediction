Project Overview
This project is a machine learning application designed to predict loan approval statuses based on various applicant details. It includes data preprocessing, exploratory data analysis (EDA), and the implementation of multiple machine learning models to classify loan status.

Dataset
Source: LoanApprovalPrediction.csv
Columns: Various features related to loan applications, such as Gender, Married, Dependents, Education, Self_Employed, ApplicantIncome, CoapplicantIncome, LoanAmount, Loan_Amount_Term, Credit_History, Property_Area, and Loan_Status.
Project Structure
Data Import and Exploration:

Load the dataset and examine its shape and structure.
Drop unnecessary columns, such as Loan_ID.
Check for missing values and replace them with mean values as needed.
Data Preprocessing:

Convert categorical features to numerical values using LabelEncoder.
Handle missing values by filling with column means where applicable.
Exploratory Data Analysis (EDA):

Visualizations:
Count plots for categorical features like Gender, Married, and Loan_Status.
Correlation heatmap to understand relationships between features.
Model Training:

Split the data into training and testing sets with an 80-20 ratio.
Implement the following machine learning models:
K-Nearest Neighbors (KNN)
Naive Bayes (GaussianNB)
Logistic Regression
Support Vector Machine (SVM)
Random Forest Classifier
Model Evaluation:

Use metrics like accuracy, confusion matrix, and classification report to evaluate each model.
Compare models based on performance.
Dependencies
Python 3
Libraries:
pandas - Data manipulation and analysis.
numpy - Numerical operations.
matplotlib, seaborn - Data visualization.
scikit-learn - Machine learning algorithms and evaluation metrics.
