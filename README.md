# Premier League Winner Prediction
This project was built using a Random Forest Classifier Machine learning Model to predict the premier league matches using team information, historical matches reults data and etc..
The goal of the project is to enhance prediction accuracy and offer insights into the factors that impact match results.
## Dataset
-matches.csv
## Content
1- Data Acquisition & Exploration:

Load and analyze the dataset. Address any missing values and discrepancies.  

2-Feature Engineering:

Establish the target variable (Win vs Not Win).  

Create training and testing datasets.  

Investigate statistics and patterns based on team performance.  

3-Building The Model:

Fit a Random Forest Classifier with tuned parameters.Assess accuracy on both training and test datasets.  

4- Model Evaluation:

Evaluate accuracy metrics for train/test divisions.  

Determine feature importance to identify the most influential factors in predictions. 

5-Results & Insights:

The Random Forest model demonstrates improved accuracy in comparison to baseline models.  

Factors such as recent performance, team capability, and opponent traits significantly impact match results.

## Problem Statement
Forecasting the results of football games is difficult because of the game's complexity and various influencing factors. The aim of this project is to:  
Develop a classification model that determines whether a team will win a match or not.  
Recognize the features (team statistics, opponents, historical performance) that have the greatest impact on prediction accuracy.
## Results
After the training and evaluation process:  
The Random Forest Classifier attained an accuracy of % on the test set.  
The model effectively pinpointed significant features that impact match outcomes.  
Enhancing the number of trees (n_estimators) and fine-tuning parameters such as max_depth enhanced predictive performance relative to the baseline model.
