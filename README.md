# Predicting Student Test Scores 
Regression modeling to predict test scores 

## Objective 
Analyze student data. Use demographic and school performance data to predict math test scores. 

## How to Run 
```
gh repo clone cbotts/test_scores-
jupyter notebook Botts_Project2.ipynb
```

## Data 
Each instance in the dataset represents an individual student. Student test scores in math, reading and writing are provided. Demographic information about each student is also provided. This is a clean dataset. Data is available from: https://www.kaggle.com/datasets/bhavikjikadara/student-study-performance

Data Dictionary

gender: binary values of male and female

race_ethnicity: contains 5 values of anonymized classifications

parental_level_of_education: contains 6 values: some high school, high school, some college,                                 associate degree, bachelor’s degree, master’s degree

lunch: binary values of standard or free/reduced

test_preparation_course: binary values of completed or none

math_score: math test scores ranging from 0-100

writing_score: writing test scores ranging from 0-100 

reading_score: reading test scores ranging from 0-100

## Method  
The target feature was math_score which was randomly selected as a measure of school performance. Three regression models were built: linear regression, nonlinear regression, and ridge regression. 

## Conclusion 
The relationship between features and target variable appears to be linear based on the high performance of the linear and ridge regression models compared to the nonlinear models. Test scores in other subjects were found to be the strongest predictors in math score, implying that math scores will improve with a focus on overall school investment. 
