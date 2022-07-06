<h1 align="center">Credit Card FraudRisk Detection</h1>
![12](https://user-images.githubusercontent.com/98824669/177502556-a6a3980a-ad22-4a1f-990d-92d47ff9980c.jpg)
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
  <h2>Table of Contents:</h2>
 </head>
 <body>
  <ol>
   <li>Importing Libraries</li>
   <li>Reading and Preparing the dataset</li> 
   <li>Exploring the data</li>
   <li>Cleaning the data</li> 
   <li>Exracting the data</li>
   <li>Visualizing the data</li> 
   <li>Creating a model</li>
   <li>Conclusion</li>
  </ol>
 </body>
 <head>
  <h2>ML approaches :</h2>
 </head>
 <body>
  The aim is to apply machine learning approach to predict the Fraud Risk.
  <ul>
   <li>Logistic Regression</li>
   <li>Random Forest Classifier</li>
   <li>Decision Tree Classifier</li>
   <li>Naive Bayes</li>
   <li>AdaBoost Classifier</li>
  </ul>
 </body>
 <head>
  <h2>ML approach Functions :</h2>
 </head>
 <body>
  <ul>
   <li>Model fitting</li>
   <li>Predicting using test</li>
   <li>Accuracy score</li>
   <li>Confusion matrix</li>
   <li>Classification Report</li>
   <li>time taken by each model</li>
  </ul>
 </body>
 <head>
  <h2>Conclusion :</h2>
 </head>
 <body>
  <ul>
   <li>Time taken is maximum for Random Forest Classifier and minimum for Naive Bayes For a best model prediction</li>
   <li>Accuracy is maximum for Random Forest and minimum for Naive Bayes
  </ul>
 </body>
 
 <table>
  <tr>
    <th>Model</th>
    <th>Accuracy Percentage</th>
    <th>Timetaken</th>
  </tr>
  <tr>
    <td><u>Logistic Regression<u></td>
    <td>90%</td>
    <td>0.03</td>
  </tr>
  <tr>
    <td><u>Decision Tree Classifier<u></td>
    <td>92%</td>
    <td>0.008</td>
  </tr>
  <tr>
    <td><u>Random Forest<u></td>
    <td>93%</td>
    <td>0.23</td>>
  </tr>
  <tr>
    <td><u>Naive Bayes<u></td>
    <td>90%</td>
    <td>0.009</td>
  </tr>
  <tr>
    <td><u>ADA Boost<u></td>
    <td>92%</td>
    <td>0.12</td>
  </tr>
</table>
     
  <ul>   
    <li>Random Forest is the best from among the models trained to predict the accurate result with an accuracy of 93% and time taken to execute is 23s.</li>
  </ul>
 

 







 
