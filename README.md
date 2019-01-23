# CRISP-DM assessment

## Description

The Cross Industry Standad Process for Data Mining (CRISP-DM) is a good practice in machine learning and is considered by many to be a wholistic and structured framework to solve machine learning problems. following such a process allows the data scientist to understand the problem, ask approriate questions, understand the data available for the analysis and trainig of an evantual model to describe the problem at hand.
Following CRISP-DM process is thus hilghly recommanded. It consist of the following stages:

1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Modeling
5. Evaluation
6. Deployment  

The objective of this assessment is to demonstrate the ability to solve machine learning problems following the CRISP-DM stages, and making informed decisions with regards to the approaches taken for feature engineering and modelling.

As a use case, we will use a churning problem, where, based on historical churning data, a classification model should be designed and trained to predit customers churn in a telecommunicaton company.

## Data 

The data used (found in the [data folder](./data)) is sampled from the [churning dataset](https://www.ibm.com/communities/analytics/watson-analytics-blog/guide-to-sample-datasets/).
Each row represents a customer, each column contains that customer’s attributes, and the target column "churn".

## Submission and evaluation

Submit the commented code (A python notebook would be ideal) including explanations on choices made.

There is no right or wrong, the submission will be evaluated more on the general understanding of machine learning along the CRISP-MD process, than on the prediction accuracy (though a good ML will result in a adequate prediction accuracy)
The main focus of the evaluation will be around the following points:

* Quality of the resulting algorithm (i.e. feature engineering and classification model): 

An algorithm that demonstrates clear understanding of the the approach taken and the tools used, and results in good prediction evaluation metrics

* Model deployment, accessibility and scalability:

Online accessibility and scalability of the model using a tool of your choice (e.g. flask, docker, cloud computing platforms, etc)

**Note:**

You can either focus on both, or on one of the above points depending on what you feel most confortable with.
In case you are more confortable with the deployment part, a very simple classification algorithm will suffice. 
