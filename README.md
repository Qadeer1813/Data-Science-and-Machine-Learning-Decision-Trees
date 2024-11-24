# Data-Science-and-Machine-Learning-Decision-Trees

**Student Name: Qadeer Hussain**

**Student ID: C00270632**

**Lecture: Greg Doyle**

**Decision Tree and Random Forest**

# Project Description
The purpose of this project is to predict whether a loan application should be approved or rejected based on the applicants details

# Data Source
The dataset that was used for this project can be downloaded from https://www.kaggle.com/datasets/granjithkumar/loan-approval-data-set

# Data

The data downloaded contains the following columns:

  * Loan_ID- Unique Loan ID
  * Gender- Male/ Female
  * Married- Applicant married (Y/N)
  * Dependents- Number of dependents
  * Education- Applicant Education (Graduate/ Under Graduate)
  * Self_Employed- Self employed (Y/N)
  * ApplicantIncome- Applicant income
  * CoapplicantIncome- Coapplicant income
  * LoanAmount- Loan amount in thousands
  * Loan_Amount_Term- Term of loan in months
  * Credit_History- credit history meets guidelines
  * Property_Area- Urban/ Semi Urban/ Rural
  * Loan_Status- (Target) Loan approved (Y/N)

# Processing
After downlading this dataset, the dataset was loaded. A test print was conducted using this code ```loan_training_dataset.head()```. Data displayed the information about missing values in some of the columns. The data missing in some columns were as follows ```Gender```, ```Married```, ```Dependents```, ```Self_Employed```, ```LoanAmount```, ```Loan_Amount_Term```, ```Credit_History```. To clean this data all rows that contain a NaN value were dropped. Columns such as ```Gender```, ```Married```, ```Education```, ```Self_Employed```, ```Loan_Status``` need to be encoded as they are categorical data. After this was done One-hot encoding was doe for categorical data with more than 2 categories ```Dependents```, ```Property_Area```. The ```Loan_ID``` and ```Loan_Status``` columns aare dropped as the ```Loan_ID``` is an unique ID and the ```Loan_Status``` is the target. The cleaned data was then split nto training sets and testing sets.

# Data Understanding and Visualisation 


# Algorithims:


# Online Sources:
1. User guide# (2024) User Guide - pandas 2.2.3 documentation. Available at: https://pandas.pydata.org/docs/user_guide/index.html (Accessed: November 2024).
2. Matplotlib 3.9.2 documentation# (2024) Matplotlib documentation - Matplotlib 3.9.2 documentation. Available at: https://matplotlib.org/stable/ (Accessed: November 2024).
3. User guide (2024) scikit. Available at: https://scikit-learn.org/stable/user_guide.html (Accessed: November 2024).
4. Jakevdp (2023) Pythondatasciencehandbook/notebooks/05.08-Random-Forests.ipynb at master · JAKEVDP/Pythondatasciencehandbook, GitHub. Available at: https://github.com/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/05.08-Random-Forests.ipynb (Accessed: November 2024).

# Tools and Tech Used: 
1. Jupter Notebook
2. Decision Tree
3. Random Forest
4. Pandas Library - Loading the data and analysing it
5. Matplotlib - Plotting and Visualising the graph 
6. Scikit Learn(Sklearn) - Implementing linear regression model.
