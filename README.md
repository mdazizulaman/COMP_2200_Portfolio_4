# portfolio-part-4-mdazizulaman
# Name: MD AZIZUL HOQUE ID: 46769579
# Heart Stroke Dataset
# Introduction
In this portfolio we were told to pick a dataset on our own to work on to resolve what we have learned till now. We are given instructions on how to choose a dataset and what to do to. We are also given a list of suggestion which outlines working areas.
# Purpose of choosing DATASET
More than half a billion people around the world continue to be affected by cardiovascular diseases, which accounted for 20.5 million deaths in 2021 according to World Heart Report 2023. Australian Bureau of Statistics 2018 demonstrated that Heart disease kills one Australian every 28 minutes.Stroke is one of Australia’s biggest killers says Australian Institute of Health and Welfare. It kills more women than breast cancer and more men than prostate cancer. More than 445,087 Australians are living with the effects of stroke. and were 27,428 Australians who experienced stroke for the first time in their lives in 2020, which equates to one stroke every 19 minutes according to Deloitte Access Economics heart stroke 2020. Researcher's say 80 percent of the strokes can be prevented if necessary actions are taken in time. Therefore, I choose to work on a dataset related to stroke. In this portfolio my prime agenda is to clean and preprocess data and implement classification, Regression and Clustering techniques and building models which can predict whether a patient is likely to get stroke or not based on the given parameters.
# Description of Dataset
This dataset is taken from kaggle. Source of the data :https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset/data1 . This dataset is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient.
## Attribute Information
1) id: unique identifier
2) gender: "Male", "Female" or "Other"
3) age: age of the patient
4) hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
5) heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
6) ever_married: "No" or "Yes"
7) work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
8) Residence_type: "Rural" or "Urban"
9) avg_glucose_level: average glucose level in blood
10) bmi: body mass index
11) smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
12) stroke: 1 if the patient had a stroke or 0 if not

*Note:'Unknown' in smoking_status means that the information is unavailable for this patient
# Exploring Dataset
# Data Processing
### Missing Value Treatment

### Outliers Detect and removal

### Coverting Categorical Value into Numerical Value

### Correaltion among features
**Highly Positive Correlations**

0.53 EverMarried vs age 

0.25 hypertension vs age

0.24 heart_disease vs age

**Highly Negative Correlations**

-0.13 Smoking_status vs age

-0.075 Job_type vs bmi

-0.069 Job_type vs EverMarried

**Least Positive Correlations**

0.00028 Job_type vs age

0.0024 residence_type vs EverMarried

0.0034 Job_type vs heart_disease

**Least Negative Correlations**

-0.00059 Smoking_status vs hypertension

-0.0008 residence_type vs stroke

-0.0014 residence_type vs heart_disease

**Correlation In terms of Stroke:**

**Highly Positive :** 0.22 stroke

**Highly Negative :** -0.025 Smoking_status

**Least Positive :** 0.015 avg_glucose_level

**Least Negative :** -0.0008 residence_type
# Regression Model
## Linear Regression
## Logistic Regression
## RFE model
we applied RFE where we found the same result as logistic regression model.
# Clustering
## KMeans clustering
## Hierarchical clusting
# Classification
## KNN
In KNN we choose 
## Gaussian Naive Bayes classifier model
# Overview
Overall, Among Linear Model and Classification model KNN works better than other models with maximum accuracy.

=======
