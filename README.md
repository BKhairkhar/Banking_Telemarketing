# Banking_Telemarketing
Predicting Success of Bank Telemarketing using Machine Learning Techniques

Problem Statement
The Portuguese Bank had run a telemarketing campaign in the past, making sales calls for a term-deposit product.The marketing team wants to launch another campaign, and they want to learn from the past one.
The aim of the project is to make use of machine learning techniques to build an effective predictive-analytical model which can forecast, whether a client is likely to subscribe to a long term (fixed) deposit account with the bank or not.i.e Whether a prospect had bought the product or not is mentioned in the column named 'response'

Data Exploration
In this project,The dataset comes from the UCI Machine Learning repository, The data is related with direct marketing campaigns (phone calls) of a Portuguese banking institution. The dataset can be downloaded from here 
https://archive.ics.uci.edu/ml/datasets/Bank+Marketing 
It provides assessment (data) of a bank’s marketing division, to sell long-term (fixed) deposits to clients based on their socio-economic indicators, like their marital status, type of job, age,.... etc. as given below.

Attributes Description: 
Input variables: 

i. Bank client data:
1 - age: (numeric)
2 - job: type of job (categorical: 'admin.','blue-collar','entrepreneur','housemaid','management','retired','self-employed','services','student','technician','unemployed','unknown')
3 - marital: marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means divorced or widowed)
4 - education: (categorical: primary, secondary, tertiary and unknown)
5 - default: has credit in default? (categorical: 'no','yes','unknown')
6 - housing: has housing loan? (categorical: 'no','yes','unknown')
7 - loan: has personal loan? (categorical: 'no','yes','unknown')
8 - balance: Balance of the individual.

ii. Related with the last contact of the current campaign:
8 - contact: contact communication type (categorical: 'cellular','telephone') 
9 - month: last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')
10 - day: last contact day of the week (categorical: 'mon','tue','wed','thu','fri')
11 - duration: last contact duration, in seconds (numeric). Important note: this attribute highly affects the output target (e.g., if duration=0 then y='no'). Yet, the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model.

iii. other attributes:
12 - campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
13 - pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)
14 - previous: number of contacts performed before this campaign and for this client (numeric)
15 - poutcome: outcome of the previous marketing campaign (categorical: 'failure','nonexistent','success')

Output variable (desired target):
21 - y - has the client subscribed a term deposit? (binary: 'yes','no')
