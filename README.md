# CodSoft_Task_02
# Task 2 :MOVIE RATING PREDICTION WITH PYTHON:

# Introduction:
Movies are a cornerstone of entertainment, and their success often depends on how well they resonate with audiences. Predicting movie ratings can provide valuable insights for filmmakers, distributors, and streaming platforms. This project utilizes machine learning to forecast ratings based on historical data and key factors, enabling stakeholders to optimize decisions in the competitive film industry.

# Task Description:
Build a model that predicts the rating of a movie based on features like genre, director, and actors. You can use regression techniques to tackle this problem.
The goal is to analyze historical movie data and develop a model that accurately estimates the rating given to a movie by users or critics.
Movie Rating Prediction project enables you to explore data analysis, preprocessing, feature engineering, and machine learning modeling techniques. It provides insights into the factors that influence movie ratings and allows you to build a model that can estimate the ratings of movies accurately.

# Problem Statement:
Develop a predictive model: In this project, we are going to use machine learning models to predict IMDB ratings of any particular movie based on the provided dataset.
This is essentially a regression problem, where we aim to estimate the numerical movie ratings based on various features.
Identify influential factors: Analyze the dataset to determine which factors (e.g., genre, director, actors) have the most significant impact on movie ratings.
Provide actionable insights: Offer insights to the film industry stakeholders to make informed decisions about movie production, casting, and marketing.

# About the Dataset:
IMDb Movies India dataset is pulled from IMDb.com of all the Indian movies on the platform.

This dataset contains the following columns:
Name: Name of Movie
Year: Year Movie was released
Duration: Time duration of Movie in minutes
Genre: Different Genre of Movies
Rating: Rating given to Movie
Votes: Votes given to Movie
Director: Director of the Movie
Actor 1: Main Actor of Movie
Actor 2: Second Main Actor of Movie
Actor 3: Third Main Actor of Movie

# Overview:
Develop a predictive model: In this project, we are going to use machine learning models to predict IMDB ratings of any particular movie based on the provided dataset.
This is essentially a regression problem, where we aim to estimate the numerical movie ratings based on various features.
Identify influential factors: Analyze the dataset to determine which factors (e.g., genre, director, actors) have the most significant impact on movie ratings.
Provide actionable insights: Offer insights to the film industry stakeholders to make informed decisions about movie production, casting, and marketing.
# Project Details:
Objective: Movie Rating Prediction with Python
Model Used: Linear Regression, Random Forest, Decision Tree Regression, Extended Gradient Boosting, Gradient Boosting, Support Vector Regression, K Nearest Neighbors from Scikit-learn.
Best Model: Random Forest
R-squared score achieved: 93.5%
Mean Squared Error (MSE): 0.12

# Key Insights:
Data cleaning was essential, involving the correction of typos and handling missing/duplicated values.
Explored the temporal dimension of the data, noting the first entry in 1931 and a movie with just 45 minutes of duration.
Amitabh Bachchan is the most frequently appearing lead actor
Identified both the best and worst-performing movies in terms of votes and ratings.
Insights on directors with the most and least movies were gained.
The distribution of movies over the years is skewed, with a concentration in the 2015-2019 period.
In 2010, some movies had the highest average votes.

Short-duration movies tend to receive higher ratings and votes, indicating a potential preference for shorter films.

Drama is a consistently popular genre, while Comedy and Action genres had their origins in 1953 and 1964, respectively.

The distribution of ratings and votes follows Gaussian-like patterns, with specific peaks and trends over time.

Furthermore, the evaluation of machine learning models revealed that Random Forest outperformed other Regression models, with an impressive R-squared score of 93.5% and lowest Mean Squared Error (MSE) of 0.12 on unseen data, highlighting the model's robustness. 

Followed by XGBoost model with R-squared score of 91.4% and Mean Squared Error (MSE) of 0.16, and then Decision Tree Regression model with R-squared score of 90.7% and Mean Squared Error (MSE) of 0.17.

Throughout the analysis, I gained a deep understanding of the dataset and its trends. This knowledge can be leveraged to make informed decisions regarding movie production, genres, and more. Future work could involve building more advanced machine learning models or diving deeper into specific genres or time periods to uncover additional insights.

# Conclusion:
In analyzing the IMDb Movies India Dataset, I navigated through data visualization, data preprocessing, and machine learning model selection. And then we embarked on a journey to analyze and predict movie ratings.

We encountered a variety of data challenges, such as handling missing values, handling duplicated records, cleaning typos or unnecessary special characters in various columns, detecting outliers and removing the outliers by IQR Method.

Through a series of Data preprocessing steps, we were able to prepare the dataset for Exploratory data analysis(EDA).

The analysis uncovered several interesting insights about the movie dataset. We observed trends in movie durations, genre popularity, the most prolific actors and directors, and the distribution of movie ratings and votes over the years. Notably, we found that short-duration movies tend to receive higher ratings and votes, and the Drama genre has consistently performed well in terms of ratings.

Furthermore, the evaluation of machine learning models revealed that Random Forest outperformed other Regression models, with an impressive R-squared score of 93.5% and lowest Mean Squared Error (MSE) of 0.12 on unseen data, highlighting the model's robustness. Followed by XGBoost model with R-squared score of 91.4% and Mean Squared Error (MSE) of 0.16, and then Decision Tree Regression model with R-squared score of 90.7% and Mean Squared Error (MSE) of 0.17.
