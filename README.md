# Commute Time Regression Analysis: Feature Importance and Predictive Modeling with Census Data

##### by Francesco Giuseppe Gillio
###### Department of Control and Computer Engineering (DAUIN)
###### Politecnico di Torino

## Reference Paper
- [Commute Time Regression Analysis: Feature Importance and Predictive Modeling with Census Data](https://github.com/305909/commute-time-regressor/blob/main/docs/commute-time-regressor-ACM.pdf)

## Abstract

This research presents a comprehensive regression analysis to predict commute times via census data. The analysis investigates the main socio-economic variables that influence commuting patterns to develop and refine a predictive model for practical applications. The study evaluates a dataset with over 130,000 observations, enforcing rigorous preprocessing techniques to drop irrelevant or redundant entries and normalize feature vectors to match the requirements of some regression models. Several regression models, including Random Forest, Decision Tree, and Support Vector Regression (SVR), undergo evaluation to extract the most relevant features and assess the dataset’s predictive power. Among these models, Random Forest shows superior performance, achieving the highest coefficient of determination (R2). Core predictors, such as departure and arrival times, emerge as critical determinants of commute time. Furthermore, the introduction of the Commute Time to Work (CTTW) feature, i.e. the time difference between departure and arrival, enhances the performance of the models, with emphasis on the Random Forest model, which attains an R2 value approaching 0.997 post-processing. Broader socio-economic variables, such as income and education, show minimal influence on commute times, reflecting their statistical independence from commuting patterns. By refining the dataset to prioritize temporal variables, the analysis improves model accuracy, offering a more efficient and reliable tool for predicting commute times.

## Setup for Google Colab

Clone the repository by running the following command:

```python
!git clone https://github.com/305909/commute-time-regressor.git
```

#### How to run the code on Google Colab

Evaluate feature importance and predictive modeling with census data by running the following command:

```python
# run regression analysis
!python /content/commute-time-regressor/regression-model.py
```
