# Bank-Loan-Project
Using the KDD process on the Lending Club Loans dataset.

To complete this coursework, you will be using the Lending Club Loan Dataset 
(https://www.kaggle.com/ethon0426/lending-club-20072020q1). A curated version of 
the dataset is uploaded on Blackboard as ‘LendingClubLoans2018-2020.xlsx’, which 
contains the loan applications related data the company received in years 2018 to 
2020.

The file has 77160 observations and 108 variables (memory usage: 50+ MB). If your 
computer has memory restrictions feel free to complete the experiment with a 
smaller portion of the provided data.

In the given data file, there are various information related to loan applicants status 
(homeownership status, annual income, purpose of taking the loan, debt-to-income 
ratio) and related information on loan amount, loan grade, various dates among 
others. A further description of the fields can be found in the Data Dictionary tab in 
the excel file for the dataset. Your task is to accurately classify the loan status 
(Current, Fully Paid, charged off, late etc.) from the given fields and then hep the 
lending club predict applications that may default/be late in paying or can be 
identified as potential bad loans.

To accomplish your task, you need to perform the following operations:
1. Download the dataset and prepare a summary of the features available on 
the dataset including data type (numerical/ categorical), amount of missing data
and outliers in individual fields.

2. Undertake any cleansing or pre-processing you think is necessary on the 
dataset. In your report, explain clearly what you have done and why you have done 
it. Some cleaning could be to remove any feature/column if 60% missing values or 
holds a NULL, constant, NaN values, or to remove duplicate and highly correlated 
information.

3. Split the data into a training set and a test set once cleansing is done. Use 
suitable toolkit and libraries (Python, Orange, Weka, or R whichever platform you are 
comfortable with) to train models (e.g. Decision Tree, Random Forest or SVM) from 
the training set to build the Loan Status Classifier. Note that you should deal with 
any class imbalance, do feature selection and other adjustments/tuning to improve 
the quality of the models obtained. You will need to test the performance of your 
model on your test set. As part of your final report, please describe and justify the 
decisions you have made, the results, how it models has been validated/evaluated
and discuss the model’s effectiveness in terms of precision and recall performances.

4. In the next stage, use an unsupervised clustering algorithm (K-means, or 
hierarchical) on the data. Use Scatter plots or t-SNE plots on the clusters to see if 
there are clusters formed for the various types of loan status (Current, Fully Paid, 
charged off, Late etc.). The Loan Status field should be omitted during clustering. 
Discuss your observations on the clusters in your report. Is there any suitable 
clustering for good loans that are paid regularly and bad loans that late/defaulted 
based on Loan Status Types?
