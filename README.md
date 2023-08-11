# Customer Churn Prediction for GNB Bank

![Churn Prediction](image1.png)

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Methodology](#methodology)
- [Observations](#observations)
- [Models](#models)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview

Welcome to the "Customer Churn Prediction for GNB Bank" project. In this endeavor, we delve into the crucial task of predicting customer churn for GNB Bank, a leading financial institution. Customer churn, the phenomenon of customers discontinuing their engagement with a service, has far-reaching implications for a bank's revenue, reputation, and market position. Our primary goal is to develop a robust predictive model that identifies customers at risk of churning, enabling GNB Bank to take proactive measures to retain these valuable customers.

## Business Understanding

Understanding customer churn's impact on GNB Bank's financial health is essential. By predicting churn, the bank can optimize resource allocation, enhance customer satisfaction, and foster long-term profitability.

<<<<<<< HEAD
* 1.RowNumber: A sequential number assigned to each row in the dataset.
* 2.CustomerId: A unique identifier for each customer in the bank.
* 3.Surname: The last name of the customer.
* 4.CreditScore: The credit score of the customer, representing their creditworthiness.
* 5.Geography: The geographical location of the customer (e.g., France, Spain, Germany).
* 6.Gender: The gender of the customer (Male or Female).
* 7.Age: The age of the customer.
* 8.Tenure: The number of years the customer has been with the bank.
* 9.Balance: The account balance of the customer.
* 10.NumOfProducts: The number of bank products the customer has purchased.
* 11.HasCrCard: Whether the customer has a credit card (1 if yes, 0 if no).
* 12.IsActiveMember: Whether the customer is an active member (1 if yes, 0 if no).
* 13.EstimatedSalary: The estimated salary of the customer.
* 14.Exited: The target variable indicating whether the customer churned (1 if yes, 0 if no).
=======
## Usage
>>>>>>> fb87c3212e1e99702f4dba733bffd45aa6dd726d

To use the trained churn prediction model, follow these steps:

Ensure you have the required dependencies installed (see Installation section).
Open a Jupyter Notebook or Python environment.
Load the trained model using the provided code snippet.
Provide input data in the required format and use the model to make predictions.
Refer to the Jupyter Notebook provided in this repository for detailed usage examples.

## Data Exploration and Preprocessing

The initial step involves preparing the data for analysis. This includes data cleaning, handling missing values, and encoding categorical variables. The dataset is carefully processed to ensure its quality and reliability.

## Methodology

The project follows these key steps:

**Data Preprocessing:** Cleaning the dataset, handling missing values, and encoding categorical variables.

**Exploratory Data Analysis (EDA):** Analyzing the dataset's characteristics, distributions, and relationships to gain insights into customer behavior.

**Feature Engineering:** Creating new features and selecting relevant ones to improve model performance.

**Model Building:** Implementing machine learning models, including Logistic Regression, Random Forest, Gradient Boosting, K Nearest Neighbors, XGBoost, and Decision Tree.

**Model Evaluation:** Assessing model performance using accuracy, precision, recall, F1-score, and other relevant metrics. Handling class imbalance through techniques like SMOTE.

**Hyperparameter Tuning:** Optimizing model parameters using techniques like GridSearchCV.

## Exploratory Data Analysis (EDA)

EDA provides insights into the dataset's characteristics. The distribution of churn is visualized, uncovering patterns and trends. Correlations between features are examined, guiding modeling strategies.

## Modeling Strategies

Multiple machine learning algorithms are employed, justified by their relevance. Hyperparameters are fine-tuned for optimal performance. Imbalanced classes are tackled using the Synthetic Minority Over-sampling Technique (SMOTE).

## Model Evaluation and Interpretation

The models' effectiveness is assessed using an array of evaluation metrics. SHAP values facilitate understanding feature importance, enhancing model interpretability. Interpretations inform strategic decisions.

## Recommendations for GNB Bank

The model's insights serve as a foundation for retention strategies. Personalized experiences, timely engagement, and targeted initiatives are recommended to enhance customer loyalty and mitigate churn.

## Observations

Some key observations from the exploratory data analysis include:

Female customers tend to churn more than male customers.
Germany has a higher exit rate compared to France and Spain.
Customers without credit cards have a higher churn rate.
Inactive members have a higher churn rate.

## Models

The project evaluates various machine learning models, including Logistic Regression, Random Forest, Gradient Boosting, K Nearest Neighbors, XGBoost, and Decision Tree. The models are trained, tuned, and evaluated to select the best-performing one.

## Results
The best-performing model, based on accuracy and other metrics, is the Gradient Boosting classifier after hyperparameter tuning. This model provides valuable insights into predicting customer churn and can be deployed for real-world use.

## Contributing