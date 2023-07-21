# CodeClause_Churn-Prediction-in-Telecom-Industry-using-Logistic-Regression_ManasviRally
This repository contains a Jupyter Notebook that demonstrates how to perform churn prediction in the telecom industry using logistic regression. 
The notebook includes the code and the corresponding outputs to guide you through the process.

**Introduction**
Customer churn is a significant concern for telecom companies as it impacts revenue and customer retention rates. 
By leveraging machine learning techniques like logistic regression, it is possible to build predictive models that identify customers who are likely to churn. 
Logistic regression is a commonly used method for binary classification problems, and it can be employed to predict whether a customer will churn or not based on 
various features such as call duration, data usage, customer demographics, and more.

This project demonstrates how to apply logistic regression to a telecom churn prediction problem. 
The code is implemented in Python, utilizing popular libraries such as scikit-learn, pandas, and numpy. 
The logistic regression model is trained on historical customer data with labeled churn outcomes, and it can subsequently be used to predict churn for new customers.

**Dataset**
The notebook uses a telecom churn dataset that contains customer information and whether they have churned or not. 
The dataset used here is not included in the repository, but you can find similar churn datasets on various platforms like Kaggle or UCI Machine Learning Repository.

Please ensure that you have the dataset in the same directory as the notebook, and modify the code accordingly to load the dataset correctly.

**Getting Started**
**_To run the notebook and reproduce the results, follow these steps:_**
Clone the repository to your local machine or download the notebook file.
Ensure you have Jupyter Notebook installed. If not, you can install it by following the instructions here.
Open a terminal or command prompt, navigate to the directory where you have saved the notebook, and run the command jupyter notebook.
The Jupyter Notebook interface should open in your browser. Click on the notebook file (Churn Prediction in Telecom Industry using Logistic Regression.ipynb) to open it.
Run each cell in the notebook sequentially to execute the code and see the outputs. Make sure to read the code comments and markdown cells for explanations.


_**In this code, you performed the following steps:**_

1. Imported the necessary libraries, including numpy, pandas, matplotlib, seaborn, and plotly.
2. Read the customer data, churn data, and internet data from CSV files into pandas dataframes.
3. Merged the dataframes based on the "customerID" column to create a consolidated dataframe called "telecom."
4. Cleaned the data by replacing empty values in the "TotalCharges" column and converting it to numeric format.
5. Converted the "Churn" column from binary values (Yes/No) to numerical values (1/0).
6. Created dummy variables for categorical variables using one-hot encoding.
7. Created additional dummy variables for categorical variables.
8. Removed redundant variables from the dataframe.
9. Checked for null values and dropped rows with missing values.
10. Split the dataset into features (X) and the target variable (y).
11. Split the data into training and testing sets using the train_test_split function.
12. Performed feature scaling on the training and testing sets using StandardScaler.
13. Created a logistic regression model using LogisticRegression from scikit-learn.
14. Fit the logistic regression model on the training data.
15. Predicted the churn values for the test set.
16. Evaluated the model's performance using accuracy, precision, weights and visualized the correlations.

**License**
The source code in this repository is provided under the MIT License. However, the dataset and any other proprietary information used in training the model might have different licensing terms. Make sure to comply with the relevant licenses when using the code and data.


