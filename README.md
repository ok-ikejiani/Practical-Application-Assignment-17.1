# Final Report: Bank Client Subscription Prediction

## Introduction

The objective of this project is to predict whether a client will subscribe to a term deposit based on various features provided by the bank. The dataset contains information about the clients, including their age, job type, marital status, education level, default on credit card, housing loan, personal loan, contact type, month of contact, day of week, duration of contact, campaign, pdays, previous contacts, and outcome of the previous marketing campaign.

## Business Understanding

The primary objective of this task is to **predict whether a bank client will subscribe to a term deposit** based on various client attributes, previous campaign interactions, and external economic indicators. By developing an accurate predictive model, the bank aims to:

1. **Increase campaign efficiency**: Reduce the number of unnecessary contacts while maintaining or increasing the subscription rate.
2. **Optimize resource allocation**: Efficiently manage the time and efforts of call agents by focusing on high-potential clients.
3. **Improve marketing effectiveness**: Identify key factors influencing client behavior to refine future campaigns and enhance targeting strategies.
4. **Minimize costs**: Avoid wasting resources on low-probability leads while maximizing returns from successful subscriptions.

The task involves **data preprocessing, feature selection, and predictive modeling** to build a classification model that can accurately predict the likelihood of a subscription (target variable: **`y`**). Insights from the model will help the bank in **decision-making** and **resource planning** for future marketing efforts.

## Research Question

How can we predict whether a client will subscribe to a term deposit based on various client attributes, previous campaign interactions, and external economic indicators?

## Insights into Data

The dataset contains 41188 rows and 17 columns. The target variable is **`y`**, which indicates whether a client subscribed to a term deposit. The dataset is imbalanced, with only 11% of the clients subscribing to the term deposit.

## Performance of the Chosen Model

The chosen model is the **Decision Tree** model, which achieved an **F1-score of 0.8789**. This indicates that the model has a good balance between precision and recall, and is able to accurately predict the likelihood of a subscription.

The **F1-score** helps the bank make informed decisions about which model to deploy by **balancing the trade-offs between precision and recall**. A **high F1-score ensures** that the marketing team can **efficiently allocate resources** by focusing on the right clients, leading to **better conversion rates** and **reduced costs**. Therefore, the F1-score is a **critical metric** that aligns with the **business goal of optimizing the marketing campaign** to increase the number of term deposit subscriptions while minimizing wasted efforts.


## Recommendations

- Deploy the model to use in the next marketing campaign. Pass the list of potienal clients through the model to select the most likely to subscribe. Focus first on those clients that are most likely to subscribe.

## Outline of project

*Root Folder:*
- [Jupyter Notebook](prompt_III.ipynb)
- [CRISP-DM-BANK.pdf](CRISP-DM-BANK.pdf)

*Data:*
- [Bank Marketing Dataset](data/bank-additional-full.csv)

*Utils:*
- Helper functions for the project that handle data cleaning, modeling, and evaluation.


## Installed Dependencies

### tabulate
Tabulate is used to display tables in the terminal. To install it, run the following command:
```
pip install tabulate
```
