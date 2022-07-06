<h1 align="center">Credit Card FraudRisk Detection</h1>
<head>
 <h2>Tools :</h2>
</head>
<body>
  <ul>
   <li>Python3, NumPy, Pandas, Seaborn, Matplotlib, Tableau & Scikit-learn</li>
  </ul>
 <head>
   <h2>Context :</h2>
 </head>
 <body>
   Credit score cards are a common risk control method in the financial industry. It uses personal information and data submitted by credit card applicants to predict the probability of future defaults and credit card borrowings. The bank is able to decide whether to issue a credit card to the applicant. Credit scores can objectively quantify the magnitude of risk.

Generally speaking, credit score cards are based on historical data. Once encountering large economic fluctuations. Past models may lose their original predictive power. Logistic model is a common method for credit scoring. Because Logistic is suitable for binary classification tasks and can calculate the coefficients of each feature. In order to facilitate understanding and operation, the score card will multiply the logistic regression coefficient by a certain value (such as 100) and round it.

At present, with the development of machine learning algorithms. More predictive methods such as Boosting, Random Forest, and Support Vector Machines have been introduced into credit card scoring. However, these methods often do not have good transparency. It may be difficult to provide customers and regulators with a reason for rejection or acceptance.
 </body>
 <head>
   <h2>Problem Statement :</h2>
 </head>
 <body>
 Build a model to predict Whether the Credit Card Fraud Risk is there or not
 </body>
 <head>
   <h2>Description :</h2>
 </head>
 <body>
 There are 13 Variables that describes the features of the Dataset.
  
 <h3 align="lest">Dataset Details</h3>
     
|<h5 align="center">Field</h5> | <h5 align="center">Description</h5> |
|------|-------------|
|<h5 align="left">Gender :</h5>|<h5 align="left">Gender of the applicant (Female/Male)</h5>|
|<h5 align="left">Married :</h5>|<h5 align="left">Marital status of the applicant (Married/single)</h5>|
|<h5 align="left">Dependents :</h5>|<h5 align="left">The applicant is dependent on some one or not</h5>|
|<h5 align="left">Education :</h5>|<h5 align="left">whether the applicant is educated or not</h5>|
|<h5 align="left">Self Employed :</h5>|<h5 align="left">Applicant is Self Employed or not</h5>|
|<h5 align="left">Applicant Income :</h5>|<h5 align="left">Income status of the applicant</h5>|
|<h5 align="left">Coapplicant Income :</h5>|<h5 align="left">Income status of the coapplicant</h5>|
|<h5 align="left">Credit History :</h5>|<h5 align="left">Applicant Credit History Availablity</h5>|
|<h5 align="left">LoanAmount :</h5>|<h5 align="left">Applicant Loan amount status </h5>|
|<h5 align="left">Loan Term :</h5>|<h5 align="left">Applicant Loan term status</h5>|
|<h5 align="left">Housing :</h5>|<h5 align="left">The Applicant has house or not</h5>|
|<h5 align="left">Locality :</h5>|<h5 align="left">Applicant Locality status</h5>|
|<h5 align="left">Fraud Risk :</h5>|<h5 align="left">Whether the fraud risk is there or not</h5>|
 </body>
 <head>
   <h2>Exploratory Data Analysis :</h2>
 </head>
 <body>
  <h2>Table of Contents:</h2>
- Importing Libraries
- Reading and Preparing the dataset 
* Exploring the data
* Cleaning the data 
* Exracting the data
* Visualizing the data 
* Creating a model
* Conclusion 
 </body>
 
