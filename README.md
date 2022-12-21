# Standard-Bank-loan-worthiness
- Standard Bank Data Science Virtual Experience Programme 
- The data provided can be found in the Resources folder as well as (https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset).
# Project Overview
The bank aims to improve the current process in which potential borrowers apply for a home loan. The current process involves loan officers having to manually process home loan applications. This process takes 2 to 3 days to process upon which the applicant will receive communication on whether or not they have been granted the loan for the requested amount. To improve the process Standard Bank wants to make use of machine learning to assess the credit worthiness of an applicant by implementing a model that will predict if the potential borrower will default on his/her loan or not, and do this such that the applicant receives a response immediately after completing application.
# Project Life Cycle
- Business Understanding
- Data Understanding
- Data Preparation
- Modelling
- Evaluation
- Deployment
- The data science lifecycle (https://www.datascience-pm.com/crisp-dm-2/).

# Part One
Analytical View on the data set using AutoEDA 
There are many AutoEDA Python libraries out there which include:

- dtale (https://dtale.readthedocs.io/en/latest/)
- pandas profiling (https://pandas-profiling.ydata.ai/docs/master/index.html)
- autoviz (https://readthedocs.org/projects/autoviz/)
- sweetviz (https://pypi.org/project/sweetviz/) and many more. In this task i will use Sweetviz
# The Home Loans Department manager wants to know the following:
- An overview of the data. (HINT: Provide the number of records, fields and their data types. Do for both).
- What data quality issues exist in both train and test? (HINT: Comment any missing values and duplicates)
- How do the the loan statuses compare? i.e. what is the distrubition of each?
- How do women and men compare when it comes to defaulting on loans in the historical dataset?
- How many of the loan applicants have dependents based on the historical dataset?
- How do the incomes of those who are employed compare to those who are self employed based on the historical dataset?
- Are applicants with a credit history more likely to default than those who do not have one?
- Is there a correlation between the applicant's income and the loan amount they applied for?
# Part Two
The model we will train will be a Logistic Regression predict if the potential borrower will default on his/her loan or not, and do this such that the applicant receives a response immediately after completing their application.
