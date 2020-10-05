# Predict Sales for a Catalog Launch
### by Sooyeon Won 

## Introduction

> This project is a part of Predictive Analytics for Business Nanodegree in Udacity. In this project, I analyze a business problem in the mail-order catalog business. I am tasked with predicting how much money the company can expect to earn from sending out a catalog to new customers. This task involves building  a **linear regression model** and applying the results in order to provide a recommendation to management.

> The details of the business situation are as follows: 
- The costs of printing and distributing is USD 6.50 per catalog.
- The average gross margin (price - cost) on all products sold through the catalog is 50%
- Management will send out the catalogs to the new customers only if the expected profit contribution exceeds USD10,000. 

## Summary of Findings
- Analysis, Modeling, and Validation <br>
The dataset includes various customer information such as customer segment, post address, the store where each customer usually visit, average number of products purchased and so on. Among all the features, it turns out _Customer Segment_ and _the number of products purchased_ are significantly associated with the average sales amounts. Based on this data investigation, I built a linear regression model to predict sales for the new 250 customers. 

- Business Recommendation <br>
The company should send this year’s catalog to these new customers. According to the predictive analysis, the expected profit is  USD 21,634.39, assuming that the catalog is sent to the 250 new customers. The expected profit contribution is higher than USD 10,000 which is the cut-off suggested by the management. 

## Key Insights for Presentation
- Data visualizaitions for understanding customer characteristics
- Regression modeling to predict sales 
- Interpretation of the regression results and application to the business problem.

## References
[Udacity- Predictive Analytics for Business Nanodegree](https://www.udacity.com/course/predictive-analytics-for-business-nanodegree--nd008)
[Linear Regression - statsmodel](https://www.statsmodels.org/dev/regression.html)
