# Project-4
Members: Jamal Safadi, Jaheim Webster
Dataset: https://www.kaggle.com/datasets/gauravduttakiit/loan-default-prediction?select=train_LZV4RXX.csv


Technologies used: Python Pandas, Python Matplotlib, Machine Learning (CatBoost and Scikit-Learn)
Loan Default Prediction
Since it started to incur heavy losses due to defaults lately, a finance company decided to build a system for identifying potential defaulters automatically based on the given data. This system will help the company to keep lending housing loans at the most affordable interest rate to its customers. So in this project, we will use machine learning libraries and data analytics techniques to generate different accuracy scores, and see how accurate the system will be. We are going to use a dataset that contains information like age, education, loan amount, how much assets a customer has, and customer’s loans history via machine learning. The dataset is created from actual data. We will also use Pandas and Matplotlib to manipulate and visualize the data.


Questions to Answer:
1- Generate the value of R-Squared
2- Using Scikit-learn library, generate different machine learning classifiers to calculate the accuracy score
3- Perform hyperparameter tuning on every classifier to check if the accuracy improved
4- Using CatBoost library, generate different accuracy scores

Findings:


The value of R-Squared predictive power is 0.94
Scikit-learn library findings
Before hyperparameter tuning, the accuracy values are: 0.59 for Logistic Regression model, 0.59 for Support Vector model, and 0.57 for Random Forest model.
After hyperparameter tuning, the accuracy values are: 0.60 for Logistic Regression model, 0.59 for Support Vector model, and 0.59 for Random Forest model.


CatBoost Library Findings
Using CatBoost library, we calculated the following scores: 0.57 for the accuracy score, 0.46 for the precision score, 0.33 for the recall score, 0.38 for the F-score, and 0.56 for the AUC score
For the accuracy scores in the Scikit-learn library, we can notice that there was a small improvement for Logistic Regression and Random Forest, and no improvement for the Support Vectors.
Reasons for that might be data quality or the size of the data.