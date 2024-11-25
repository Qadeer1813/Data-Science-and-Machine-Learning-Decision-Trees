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
After downloading this dataset, a test print was conducted using this code ```loan_training_dataset.head()```. Data displayed the information about missing values in some of the columns. The data missing in some columns is as follows ```Gender```, ```Married```, ```Dependents```, ```Self_Employed```, ```LoanAmount```, ```Loan_Amount_Term```, ```Credit_History```. To clean this data all rows that contain a NaN value were dropped. Columns such as ```Gender```, ```Married```, ```Education```, ```Self_Employed```, ```Loan_Status``` need to be encoded as they are categorical data. After this was done, One-hot encoding was conducted for categorical data with more than 2 categories: ```Dependents```, ```Property_Area```. The ```Loan_ID``` and ```Loan_Status``` columns are dropped as the ```Loan_ID``` is a unique ID and the ```Loan_Status``` is the target. The cleaned data was then split into training sets and testing sets.

# Data Understanding and Visualisation 
After processing the data we then proceed to start creating the confusion matrix and the other Decision Tree and Random Forest:

1. The model below is the full Decision Tree with no restrictions
   
   Confusion matrix and metrics  

   ![image](https://github.com/user-attachments/assets/4c5da6d9-377f-48f5-989c-fd033901cea5)

   ![image](https://github.com/user-attachments/assets/301520af-4772-46bd-8286-cbe6bdc09f99)

   ![image](https://github.com/user-attachments/assets/fae346fa-dd50-4400-a0b3-215997adb8c1)

   Decision Tree

   ![image](https://github.com/user-attachments/assets/c9f23f10-b41a-424e-b11a-cc8e12b88b61)

2. The model below is a Decision Tree with a max depth restriction of 3

   Confusion matrix and metrics

   ![image](https://github.com/user-attachments/assets/5c054cd6-8f4c-40ac-a3d6-3486cccbae39)

   ![image](https://github.com/user-attachments/assets/b792ea7b-bd94-4a33-8a33-33558070f12f)

   ![image](https://github.com/user-attachments/assets/9683b8ad-156a-4e61-ad86-52bf6aee358b)

   Decision Tree

   ![image](https://github.com/user-attachments/assets/466a93fe-4958-4918-87e6-2e719386d388)

3. The model below is a Random Forest Decision Tree with a max depth restriction of 3

   Confusion matrix and metrics

   ![image](https://github.com/user-attachments/assets/10416a0f-64b0-4cb0-aa95-cd36006a72ce)

   ![image](https://github.com/user-attachments/assets/44d64f2c-d153-4604-9f51-78945497524b)

   ![image](https://github.com/user-attachments/assets/c714cc5c-b133-4274-b487-f38a3b9ee98c)

# Algorithims:
Decision Tree: 

Random Forest:

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
