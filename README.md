# LoanDefault-Prediction

Lending Club Data Default Prediction Peer-to-peer lending is a relatively new form of credit that focuses on financing borrowers from their peers (small lenders) and individuals who earn interest on the money they lend. Borrowers can apply through an online platform for personal loans, often unsecured, that are financed by one or more peer investors.

The P2P lender is not an actual lender, but rather an intermediary that facilitates the lending process and provides the platform. These platforms have developed in US, UK, Australia and other financial markets, but the US remains the leader in the peer-to-peer lending space. Peer-to-peer lending may not have begun in the US, but it has quickly spread to dominate the personal loan market and is slowly making its way into other markets. Lending Club, a San Francisco-based fintech company, works to facilitate peer-to-peer loans through their online lending platform. Started in 2007, their website allows individuals to publicly post loan applications, which other users can then browse and choose to fund. Their website makes its historical records publicly available, leading to the interesting question: can we determine an accurate way of using loan characteristics to predict which loans will be paid back in full and which will default?

####This project aims to develop a robust module for predicting your chances of loan approval. The features used for prediction are considered to be available at the time of loan origination and thus do not leak any information from the future. The prediction model has been built separately for Individual Applicants and Joint Applicants with a maximum accuracy. Few highly correlated features such as Grade, Sub Grade, Interest Rate are estimated using the provided FICO score by the applicant.

## Model Accuracies:


Model | Accuracy
--- | ---
Random Forest with Randomized search CV            | 82.09
Logistic Regression with Grid search CV            | 83.18
Support Vector Machine with Grid search CV         | 82.50
K Nearest Neighbors with Grid search CV            | 77.40
Bagging with Base estimator as Random Forest       | 84.10
Bagging with Base estimator as Logistic Regression | 83.10
AdaBoost Classifier                                | 83.60
MultilLayer Perceptron Classifier                  | 83.40


## Technologies:
* Programming Language: Python
* Libraries: Pandas, Scikit-learn, Matplotlib, Seaborn
* Visualization: plotly

## Data Source:
https://www.lendingclub.com/info/download-data.action


 
 

