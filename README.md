# Financial Distress Prediction

Check out the jupyter notebook here: https://jovian.ai/olivelikes2chat/financial-distress-prediction

## Introduction
Banks play a crucial role in market economies. They decide who can get finance and on what terms and what can make or break investment decisions. For markets and society to function, individuals and companies need access to credit.

Lenders approve loans based on several factors, including your credit score. Credit scoring algorithms, which make a guess at the probability of default, are the method banks use to determine whether or not a loan should be granted.

## Project Objective & Outline
The aim of this project is to improve on the state of the art in credit scoring, by predicting the probability that somebody will experience financial distress in the next two years. This model will help borrowers to make the best financial decisions. To accomplish this task, we will be using a dataset that contains about 150,000 rows with 12 columns. The target column of our dataset has two variables, 0 and 1;

* 0 represents - No, the borrower will not experience financial distress in the next two years, and
* 1 represents - Yes, the borrower will experience financial distress in the next two years

Source: The dataset used for this project was obtained from Kaggle: Link

Here's the outline we followed to complete this project

* Downloading the Data
* Perform exploratory analysis and visualization on the dataset
* Preprocess and clean the data using the pandas library
* Set up evaluation metrics
* Build models
* Tune hyperparameters of our best performing model
* Make predictions on new input data

## Variable Description
Here's a full description of the variables in the dataset.

* SeriousDlqin2yrs: Person experienced 90 days past due delinquency or worse Y/N
* RevolvingUtilizationOfUnsecuredLines: Total balance on credit cards and personal lines of credit except real estate and no installment debt like car loans divided by the sum of credit limits percentage
* age: Age of borrower in years integer
* NumberOfTime3059DaysPastDueNotWorse: Number of times borrower has been 30-59 days past due but no worse in the last 2 years. integer
* DebtRatio: Monthly debt payments, alimony,living costs divided by monthy gross income percentage
* MonthlyIncome: Monthly income real
* NumberOfOpenCreditLinesAndLoans: Number of Open loans (installment like car loan or mortgage) and Lines of credit (e.g. credit cards) integer
* NumberOfTimes90DaysLate: Number of times borrower has been 90 days or more past due. integer
* NumberRealEstateLoansOrLines: Number of mortgage and real estate loans including home equity lines of credit integer
* NumberOfTime60-89DaysPastDueNotWorse: Number of times borrower has been 60-89 days past due but no worse in the last 2 years. integer
* NumberOfDependents: Number of dependents in family excluding themselves (spouse, children etc.) integer
