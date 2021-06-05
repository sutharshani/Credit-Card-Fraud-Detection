# Credit-Card-Fraud-Detection
Credit Card Fraud Detection using Machine Learning

# Table of Contents
1. [Introduction](#introduction)
2. [Data Background](#data-background)
3. [Prerequisite](#prerequisite)
4. [Project Status](#project-status)
5. [Versioning](#versioning)
6. [Authors](#authors)
7. [Acknowledgement](#acknowledgement)
8. [Reference](#reference)

## Introduction
We have witnessed enormous evolution in credit card processing over the last few years, issuing chip-based credit cards, starting mobile device based wallets like Apple Pay are some of the significant changes done to secure credit card transactions.

Despite financial institutions (banks) working hard to eliminate fraud in credit card transactions, credit card fraud has been continuously rising over the last few years. Fraudsters are getting smarter and using latest technologies to steal cardholder’s information, either through hacking or through social engineering.

Increasing fraud in the industry makes fraud prediction very critical to be able to identify and stop fraud in real-time, and data science plays a significant role in analyzing and being able to predict fraud based on transactional and cardholder information. The scope of this project is to research and identify different types of predictive analysis algorithms available that can be applied to determine and stop fraudulent transactions.


[back to top](#table-of-contents)
## Data Background
Credit card processing is one of the fast-growing industries due to rapid advances in technology and with more and more customers switching to use credit cards instead of cash for purchases. Innovations like mobile wallets provided by Apple, Google, and other major technology firms have played an enormous role in the increased usage of credit cards in recent years.

On a very high level, credit card transactions can be of two types, card present, and card not present transactions. Card present transactions are the transactions from retail stores or gas stations where the cardholder is present during the transaction, and that makes fraud a little bit difficult as the fraudster has to either steal the physical card or copy the card details, to create a duplicate card. Fraud in card-present transactions has reduced in recent years due to the introduction of chip cards (challenging to copy and reproduce) and increased usage of mobile wallets which have the same security as chip cards. That leaves us with the card, not present transactions, where we are seeing an increased number of fraudulent transactions in recent years. These are usually e-commerce or online portal based transactions. In this case, fraudsters needed very less information about the physical card and cardholder to perform the transactions.

We are planning to use the dataset we found at https://www.kaggle.com/mlg-ulb/creditcardfraud. The datasets contain transactions made using credit cards in September 2013 by European cardholders.

This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, the owner of the dataset did not provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. 


[back to top](#table-of-contents)
## Prerequisite
You will need the following applications to execute this project-

* Python 3 (or Anaconda distribution with Python 3)
* Jupyter or any other notebook

[back to top](#table-of-contents)

## Project Status
I was able to build a model which predicts fraud transaction with good accuracy. \
[back to top](#table-of-contents)

## Versioning
Git is used for project versioning. \
[back to top](#table-of-contents)

## Authors
Shani Kumar \
[back to top](#table-of-contents)

## Acknowledgement
We were able to create multiple prediction models using different techniques and all of them seem to be performing good in predicting fraudulent transactions.
Extra Trees Classifier technique seem to have given us best performance of all the models.

Based on our project work, if we deploy our model into a credit card transaction processing application, we could predict and stop fraudulent transactions in real time.

One thing we still have to figure out is how to make our models production ready where the training and model upgrades happen automatically whenever there is new set of data to review.


[back to top](#table-of-contents)

## Reference
1. https://www.kaggle.com/mlg-ulb/creditcardfraud
2. https://www.washingtonpost.com/news/the-switch/wp/2018/03/01/equifax-keeps-finding-millions-more-people-who-were-affected-by-its-massive-data-breach/?noredirect=on&utm_term=.0b854d8c3526

[back to top](#table-of-contents)
