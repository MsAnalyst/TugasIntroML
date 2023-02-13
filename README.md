# Chronic Kidney Disease Classification using Supervised Machine Learning 

## Content
Problem Definition & Goals
Dataset
Methods & Modelling
Model Evaluation
Conclusion
References

## Problem Definition & Goals
Business Problems
Early and accurate detection of chronic kidney disease (CKD) is needed to minimize patient’s health complications. 
In many cases, CKD is only found when a routine blood or urine test is done where the result of the tests comes out as abnormal and shows that patient’s kidney may not be working normally. Routine tests are time consuming and costly.

Business Solution
Machine learning has revolutionized the way the patient history data is being processed. Previous studies in this field of research have generally followed the approach of applying a machine learning model to test the model’s efficacy in classifying the kidney health data into severity level and the existence of CKD. 
In this study, binary classification was performed using supervised machine learning model trained to classify the CKD and notCKD classes.  

Goal
The goal of this project is to find the best-supervised machine learning algorithm for CKD classification.

## Dataset
Description:
Dataset is from Apollo Hospitals, Managiri, India which was obtained from the machine learning data site Kaggle.com.  
Dataset comprises of 400 instances with 25 attributes (excluding the ‘id’ column).
There are 11  categorical data: rbc, pc, pcc, ba, htn, dm, cad, appet, pe, ane, classification.
There are  15  numerical data: age, bp, sg, al, su, bgr, bu, sc, sod, pot, hemo, pcv, wc, rc. 

![EDA   PP - CKD](https://user-images.githubusercontent.com/109356444/218491325-ff2f4230-b90d-475a-82f9-145f45483d5b.png)

Handling Missing Values: 
Data may not always be present (or missed) as a result of equipment failure, inconsistent with other recorded data and thus deleted, not entered into the database as a result of misunderstanding, or not thought important at the time of input for some data.

Sometimes zero can be used in place of the missing numbers, leaving the model unchanged. Since the missing features are numerical and mean imputation works better for numerical missing values, this study used the mean, an average of the observed characteristics, to handle the missing values.

Handling Categorical Data: 
In this step, data has been formatted in accordance with the specifications.

Feature Selection
Feature selection is the important preprocessing step to detail with the problem of high dimensionality. Hence, the main aim of feature selection is to select the subset of features that are relevant and independent [3]. We reduce the dimensionality and complexity of the data and make the model be faster, more effective and accurate. 

Next to better understand feature importance, a correlation matrix was assembled to observe correlation coefficients, to which the algorithm was applied to score the extracted features and eventually select the most important features to be used as the model inputs (Table 1). The feature matrix was then standardized by removing the mean and scaling to unit variance. 

![Correlation - CKD](https://user-images.githubusercontent.com/109356444/218491970-596bbc87-2d38-4ac8-ac62-7404a155f5d7.png)

# C. Methods
![Modeling CKD](https://user-images.githubusercontent.com/109356444/218492220-7b27ef26-99a3-4389-82c6-fd008b0772b1.png)



To understand the behavior of taxonomy, we use the following hypothesis: • True Positive (TP) is the number of positively estimated positive assumptions. • True Negative (TN) is an accurately estimated number of negative samples • False Negative (FN) means the number of positively estimated positive samples. • False Positive (FP) is the number of negative samples that are negatively estimated.

C.2. Machine learning models
The aim of the study was to predict chronic kidney disease using machine-learning techniques. 7 Machine learning algorithms (in alphabetical order): Decision Tree, XGB, and Random Forest, Support Vector Machine, Naive Bayes, Probabilistics Neural Networks, and K-Nearest Neighbors Algorithm (KNN) have been used in this study. The algorithms were selected based on their popularity in chronic kidney disease prediction and their performance of classification on previous research works.

# D. Conclusion
Evaluation by Accuracy
Accuracy implies the ability of the classification algorithm to predict the classes of the dataset correctly. It is the measure of how close or near the predicted value is to the actual or theoretical value. Generally, accuracy is the measure of the ratio of correct predictions 
over the total number of instances. 

# E.Conclusion
Chronic kidney disease is a global threat and many people die or suffer severely from the disease mainly due to lack of awareness about the disease and inability to detect it early. Thus, early prediction of chronic kidney disease is believed to be helpful to slow the progress of the disease. Machine learning plays a vital role in early disease identification and prediction. It supports the decision of medical experts by enabling them to diagnose the disease fast and accurately. 
