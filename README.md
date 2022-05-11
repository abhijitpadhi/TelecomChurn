# Telecom Churn
> In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- It will be used to predict whether a high-value customer will churn or not, in near future (i.e.,
churn phase). By knowing this, the company can take action steps such as providing special
plans, discounts on recharge etc.

It will be used to identify important variables that are strong predictors of churn. These variables
may also indicate why customers choose to switch to other networks.

Even though overall accuracy will be your primary evaluation metric, you should also mention
other metrics like precision, recall, etc. for the different models that can be used for evaluation
purposes based on different business objectives.
- Analysis of data set using Logistic Regression, Advanced Regression like Random Forest & XGBoost.
- Business probem: Risks are associated with the Telecom Churn:
    1) To predict whether a high-value customer will churn or not, in near future (i.e. churn phase). By knowing this, the company can take action steps such as providing special plans, discounts on recharge etc.
    2) It will be used to identify important variables that are strong predictors of churn. These variables may also indicate why customers choose to switch to other networks.
- The data set with name "train (1).csv" is used.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- In Random Forest model the accuracy is 89% where as the recall is 93% without hyperparameter tuning.
- In Random Forest the accuracy is 86% and the recall is 88% with hyperparameter tuning.
- In XGBoost the accuracy is 85% and the recall is 88%. 
- In Logistic Regression the recall is 86%.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy version	    : 1.20.3
- pandas version	: 1.3.4
- seaborn version	: 0.11.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by concepts of Logistic Regression, Advanced Regression like Random Forest & XGBoost.
- This project was based on [Telecom Churn]().


## Contact
Created by [@abhijitpadhi] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->