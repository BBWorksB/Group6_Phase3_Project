# Customer Churn Prediction for GNB Bank

## Table of content
<!-- TOC -->

- [Customer Churn Prediction for GNB Bank](#customer-churn-prediction-for-gnb-bank)
    - [Introduction](#introduction)
    - [Business Understanding](#Business-Understanding)
    - [Data Understanding](#Data-Understanding)
    - [Modelling](#Modelling)
    - [Data Evaluation](#Data-Evaluation)
    - [Conclusion](#conclusion)
    - [Non Technical Presentation](#non-technical-presentation)

<!-- /TOC -->

## Introduction
GNB Bank is a leading financial institution, providing various banking and financial services to its customers. As with any bank, customer retention is crucial for maintaining a strong market presence and sustaining profitability. Identifying customers who are likely to churn is of paramount importance for GNB Bank to implement targeted strategies and retain valuable customers. In this bprojec, we will explore a dataset containing customer information, including demographics, banking behavior, and historical churn data. Our objective is to build a predictive model that can accurately predict customer churn and provide valuable insights to help GNB Bank enhance its customer retention efforts.

## Business Understanding
For GNB Bank, understanding and predicting customer churn is critical for several reasons. First and foremost, customer churn impacts the bank's revenue and profitability. Acquiring new customers is more expensive than retaining existing ones, so preventing churn can lead to significant cost savings. Moreover, customer retention contributes to a positive reputation and strengthens the bank's position in the highly competitive financial industry. By leveraging machine learning techniques to predict customer churn, GNB Bank can proactively address the needs of at-risk customers, personalize their banking experience, and develop targeted marketing campaigns to foster long-term customer loyalty.

## Data Understanding
This project will use the churn modelling dataset. The dataset has 9970 rows, and 11 columns. The dataset has the following information which will give a better and insight of customer churning.

**1.RowNumber:** A sequential number assigned to each row in the dataset.
**2.CustomerId:** A unique identifier for each customer in the bank.
**3.Surname:** The last name of the customer.
**4.CreditScore:** The credit score of the customer, representing their creditworthiness.
**5.Geography:** The geographical location of the customer (e.g., France, Spain, Germany).
**6.Gender:** The gender of the customer (Male or Female).
**7.Age:** The age of the customer.
**8.Tenure:** The number of years the customer has been with the bank.
**9.Balance:** The account balance of the customer.
**10.NumOfProducts:** The number of bank products the customer has purchased.
**11.HasCrCard:** Whether the customer has a credit card (1 if yes, 0 if no).
**12.IsActiveMember:** Whether the customer is an active member (1 if yes, 0 if no).
**13.EstimatedSalary:** The estimated salary of the customer.
**14.Exited:** The target variable indicating whether the customer churned (1 if yes, 0 if no).


## Modeling
In the GBN bank customer churn prediction project, various machine learning models were employed to predict customer churn. Here are the results:

* Logistic Regression: Achieved an accuracy of 81.45%.
* XGBoost Model: Initially achieved an accuracy of 86% after performing SMOTE (Synthetic Minority Over-sampling Technique) to balance the dataset.
* GradientBoosting Model: Achieved an 86% accuracy after hyperparameter tuning.
* RandomForest: Also reached an accuracy of 86% after hyperparameter tuning.
* Decision Tree: Attained an accuracy of 78%.
* K-Nearest Neighbors (KNN): Achieved an accuracy of 82%.

## Conclusion
In this project, we tackled the problem of customer churn prediction for GNB Bank, a leading financial institution. Customer churn can have significant implications for a bank's revenue, profitability, and reputation. Our goal was to develop a predictive model that could accurately identify customers who are likely to churn, enabling the bank to take proactive measures to retain them.

We began by exploring a dataset containing customer information, including demographics, banking behavior, and historical churn data. After preprocessing the data, we built an XGBoost model to predict customer churn. The initial model achieved an accuracy of around 85.6%. However, due to the class imbalance present in the dataset, the model's performance was suboptimal in terms of precision, recall, and F1-score for the minority class (churned customers).

To address this class imbalance issue, we applied the Synthetic Minority Over-sampling Technique (SMOTE) to balance the dataset. The balanced XGBoost model demonstrated improved performance, achieving an accuracy of approximately 90.7%. The precision, recall, and F1-score for the churned customers also showed significant improvement, indicating that the model can better identify customers at risk of churn.

## Recommendations
Based on the results of our churn prediction model, here are some recommendations for GNB Bank:

1.Targeted Retention Strategies: Utilize the predictions from the model to implement targeted retention strategies for customers identified as at-risk of churning. By understanding the key factors contributing to churn, the bank can tailor its offerings and incentives to address customer concerns and increase loyalty.

2.Personalized Customer Experience: Leverage the insights gained from the model to provide personalized experiences for customers. By understanding customer preferences and needs, the bank can offer relevant products and services that meet individual requirements, increasing customer satisfaction and reducing churn.

3.Timely Engagement: Implement proactive engagement strategies for customers with a high churn likelihood. Reach out to these customers with timely offers, incentives, or support to address their concerns and enhance their overall experience with the bank.

4.Feedback Loop: Continuously collect feedback from customers, especially those who have churned, to understand their reasons for leaving. This feedback can provide valuable insights into areas of improvement, enabling the bank to make informed decisions for enhancing its services.

## Non Technical Presentation
To access the canvas slides click on the link [Presentation](https://docs.google.com/presentation/d/1ajg6cfOwB2MdpV1gWgzEFag6ig4nQKKjjr72dEZCPPk/edit?usp=sharing)
