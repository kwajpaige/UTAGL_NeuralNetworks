# UTAGL_NeuralNetworks
Deep learning has gained a lot of attention in recent years with the increase in the amount of data being generated across businesses. Deep learning algorithms have proven to work better with large data as compared to traditional machine learning. The rise in data and computing power has driven tremendous developments in the machine learning space, and the need to access and process large data is turning out to be increasingly significant with regards to solving real-life/business problems. Currently, deep neural networks can learn the complex relations among the data and provide us with meaningful insights. The purpose of this project is to explore the exciting world of deep learning.

Link to Jupyter Notebook: https://github.com/kwajpaige/UTAGL_NeuralNetworks/blob/main/BankChurnPredictionProject/PaigeSingleton_NeuralNetworks_BankChurnPrediction.ipynb

## Background
Businesses like banks that provide service have to worry about the problem of 'Churn' i.e. customers leaving and joining another service provider. It is important to understand which aspects of the service influence a customer's decision in this regard. Management can concentrate efforts on the improvement of service, keeping in mind these priorities.

## Data Dictionary
- CustomerId: Unique ID which is assigned to each customer
- Surname: Last name of the customer
- CreditScore: It defines the credit history of the customer.
- Geography: A customer’s location
- Gender: It defines the Gender of the customer
- Age: Age of the customer
- Tenure: Number of years for which the customer has been with the bank
- NumOfProducts: It refers to the number of products that a customer has purchased through the bank.
- Balance: Account balance
- HasCrCard: It is a categorical variable that decides whether the customer has a credit card or not.
- EstimatedSalary: Estimated salary
- isActiveMember: It is a categorical variable that decides whether the customer is an active member of the bank or not ( Active member in the sense, using bank products regularly, making transactions, etc )
- Exited: It is a categorical variable that decides whether the customer left the bank within six months or not. It can take two values 
  - 0=No ( Customer did not leave the bank )
  - 1=Yes ( Customer left the bank )

## Objective
Given a Bank customer, build a neural network-based classifier that can determine whether they will leave or not in the next 6 months. 

## Insights and Recommendations
- Build a program for at-risk customers using data to identify which customers as most at-risk for churn
- Build a machine learning classification model, such as logistic regression or decision tree, and then use the model to generate a list of most informative features.
- Use the features identified in this report - Age, Number of Products, Geography, Gender, Is Active Member as a guide in identifying at-risk customers
- The models in this report are overfitting; build additional models using other techniques, in order to find the best model that does not overfit the data while improving the recall score
- Seek to simplify the model through more in-depth feature analysis and feature enginnering
