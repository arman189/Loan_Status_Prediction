# Loan_Status_Prediction
Loan Status Prediction is a predictive model to predict if an applicant is eligible to take loan from bank or not. As we know, loans are the core business of banks. The main profit comes directly from the loan’s interest. The loan companies grant a loan after an intensive process of verification and validation.  I prepared the data using Jupyter Notebook and use various models to predict the loan status. 

<br/>**Objectives:-**  To predict the loan status.
<br/>**Software Used:-** Anaconda, Jupyter Notebook, pyqt5
<br/>**Algorithm Used:-** Support Vector Machine Algorithm (SVM)
<br/>**Definition:-** Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.
<br/>**Data Processing Techniques:-**
<br/>1. Handling nan values using fillna() function.
<br/>2. Labelling string values using LabelEncoder().
<br/>**How to:-**
<br/>1. Read the csv file using pandas opencv() function.
<br/>2. Apply Data Processing technique to clean the data.
<br/>3. Divide data set into x and y; x having independents values and y having dependents variables.
<br/>4. Further dividing x and y into x_test, x_train, and y_test, y_train respectively using train_test_split().
<br/>5. Initialize the model by importing  SVC from sklearn.svm.
           <br/>-> from sklearn.svm import SVC
           <br/>-> model=SVC()
<br/>6. Train the model.
           <br/>-> model.fit(x_train,y_train)
<br/>7. Predict the loan status .



**OUTPUT**

![output](https://user-images.githubusercontent.com/70680425/135625934-86290851-38c5-447e-b80e-c1c1b9ae70e5.png)
