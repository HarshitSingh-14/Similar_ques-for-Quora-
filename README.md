# Sentiment/Question Comparer
> ------------
> ### I made this webapp using the dataset given by quora on Kaggle [Link](https://www.kaggle.com/competitions/quora-insincere-questions-classification). I have developed more scalable methods to find similarity between the two questions. Intially after performing EDA, I vectorized it to perform Algorithms. 
> Further to improve the accuracy, I applied various feature engineering methods.
------------

## Feature Engingeering Steps
 > * q1 length.  
 > * q2 length
 > * words in q1
 > * words in q2
 > * words common
 > * Word part in each
 > * Token Features -> found features like common words, stop words, first & last common words
 > * Length based features -> mean_length, absolute_diff_length, Longest substring ratio
 > * fuzzy features
 ------------
 After getting a descent results, I created a Web Application using Streamlit and hosted it on heroku https://question-similar.herokuapp.com/
