## End to End ML project

## Introduction

This is an End-to-End Machine Learning Project which predicts the math score of students based on  independent features like : 
 1. Race
 2. Ethnicity
 3. Gender
 4. Parental Level of Education
 5. Lunch Type
 6. test_preparation_course
 7. Reading Score
 8. Writing Score

The aim of this project was to build a Production Ready Model that can be deployed directly on platforms like AWS , MS Azure etc.

## Exploratory Data Analysis

  1. Checking for Missing Values
  2. Analyzing the Skewness in some features 
  3. Checking for Multicolliarity using VIF.
  4. Visualizing the Plots and understanding the trends

## Feature Engineering

 1. Missing Data Imputation
 2. Categorical Encoding
 3. Variable Transformation
 4. Outlier Engineering


## Feature Selection

Since the number of independent features were not huge, all of them were used in model creation.

## Model Creation
We built the prediction pipleine usinf Random Forest Regressor Model which was complied in the research phase and then stored as .pkl file which was eventually used in the Pipeline.


## Performance Metric

The performance of the model was analyzed using Adjusted R-Square and Mean Square Error. Adjusted R-Square came out to be 0.87 on the test data whereas MSE came out  to be 4.3
