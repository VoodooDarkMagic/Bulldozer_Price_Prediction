# Bulldozer_Price_Prediction


This repo contains Notebook to predict the price bulldozers using past data. The data is can be found from this [Kaggle link](https://www.kaggle.com/c/bluebook-for-bulldozers/data)

There are 3 main datasets:

+```Train.csv``` is the training set, which contains data through the end of 2011.
+```Valid.csv``` is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.
+```Test.csv``` is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition.

## Evaluation metric 
The evaluation metric for this project is the RMSLE (Root Mean Squared Log Error) between the actual and predicted auction prices. Our goal for this project will be to build a machine learning model which minimises RMSLE.