# Predicting San Francisco's Employee Salaries 
---
## Introduction

Our goal is to look at the different city job titles that are within the city government and prediciting their salary values. With using Kaggle's San Francisco's Salary Dataset - we narrowed down the job titles to the top 50 populated/common job titles and the created categories that best fit. This project would give those who are interested in working for the city of San Francisco and potential salary values for those intrigued in certain job titles and their job categories. The dataset entails job titles, departments, base pay, overtime pay and total compensation. This would also help create decisions around advancement in careers, hiring and keeping employees.
---
## In this project: 
- Data file which inlcudes CSVs and photos 
- Prediction SF Salaries updated.IPYNB
    - Clean, filter and narrow the dataset loaded from SF Salaries CSV : https://www.kaggle.com/datasets/kaggle/sf-salaries
    - Created multiple dataframes including cleaned version of the SF Salaries, dataframes that range to 2011-2014, and more.
    - EDA Visuals of : 2011 Top 5 Job Titles, 2014 Top Job Titles and Job Title Counts of the Overall Top 50
    - Creating the Top 50 Job Titles and separation into best fit categories and label encoded for machine learning preparation :
        - 0.Emergency Safety
        - 1 .Engineering	
        - 2.Food Service
        - 3.Healthcare	
        - 4.Maintenance and Operations	
        - 5.Professional_Administrative_Support Services
        - 6.Public Safety	
        - 7.Social and Public Services
        - 8.Transportation
    - Created the final dataframe and CSV that includes:
         - JobTitle
         - JobCategoryEncoded
         - TotalBasePay
         - AvgBasePay
         - MinBasePay
         - MaxBasePay
         - MedianBasePay
         - StdDevBasePay
    - Preparation of Data to fit the Linear Regression and Random Forest Model
          - Visuals of : Regression Line Plot and Box Plot- Actual Vs Predicted SF Salary Analysis a bar graph of Predicted Salaries by Job Categories

## Group 3 
- Jennifer G.
- David H.
- Alexa D.
