# Lead-Scoring-Case-Study
### Problem Statement

An X Education needs help to select the most promising leads, 
i.e. the leads that are most likely to convert into paying customers. 

The company requires us to build a model wherein you need to 
assign a lead score to each of the leads such that the customers 
with higher lead scores have a higher conversion chance and 
the customers with lower lead scores have a lower conversion chance. 

The CEO, in particular, has given a ballpark of 
the target lead conversion rate to be around 80%.

# Goals and Objectives
Build a logistic regression model to assign a lead score between 0 and 100 to each of the leads which can be used by the company to target potential leads.

A higher score would mean that the lead is hot, i.e. is most likely to convert whereas a lower score would mean that the lead is cold and will mostly not get converted.

There are some more problems presented by the company which your model should be able to adjust to if the company's requirement changes in the future so you will need to handle these as well.

These problems are provided in a separate doc file. Please fill it based on the logistic regression model you got in the first step. Also, make sure you include this in your final PPT where you'll make recommendations.

# Solution
I have made this Lead Score Prediction Model using Logistic Regression which is a supervised 
learning algorithm.

📌Introduction:
Logistic regression, in contrast to linear regression, is utilized when the objective is to predict 
categorical outcomes, typically binary classification problems. Instead of predicting continuous 
values, logistic regression models the probability that an instance belongs to a particular class based 
on the relationship between the independent variables and the binary outcome.

📌Objective:
A machine learning model is to be proposed to predict a Lead Score based on data related to this.

📌Data:
The dataset consists of 9240 entries across 37 attributes, with the target column labeled as 
'Converted'.

📌Steps followed are:

📍 Applied data preprocessing and preparation techniques in order to obtain clean data which 
includes following steps:

1. Importing and understanding of data
2. Missing value check
3. Correlation Check
4. Data Reduction
5. Data Cleaning/Wrangling
6. Feature Engineering
7. Univariate Analysis
8. Bivariate Analysis
9. 
📍 Built machine learning model to be able to predict Lead Score based on the features using Logistic 
regression includes following steps:

1. Splitting data into training and testing data
2. Feature Scaling
3. Feature Selection
4. Building and training the model
5. Variance Inflation Factor
6. Making predictions from the model
7. Testing the performance of the model
a. ROC curve
b. Accuracy Score
c. Confusion Metrics
d. Precision and Recall

📌Model Evaluation:
Logistic regression performed well giving a testing accuracy of almost 85.44 % and Precision of 86.93 
% and Recall of 76.88 
