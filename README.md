# Project Title: Using Linear Regression to Predict Sentiment Score of Amazon Review Text

## Fall 2023

## By Lizzie Gilson, Giovanni Battista Alteri and Qi Tifany Chu 

This Repository Contains all the files related to our Project.

## Research Questions 

- How has the sentiment of Amazon review text changed over time?
- Which model will best predict the sentiment score of review based on select features?

## Project Abstract

  This study analyzes evolving sentiment trends in Amazon reviews using the Amazon
Review Dataset, aiming to understand changes in user sentiments over time and build predictive
models for sentiment scores.

  The investigation reveals insights into sentiment analysis development and identifies
influential features impacting sentiment prediction. Utilizing a 5-core subset of 142.8 million
reviews from May 1996 to July 2014, the study spans diverse product categories and employs
VADER sentiment analysis.

  This research employs multiple models: a linear regression model predicting overly polar
reviews over time, and two linear models predicting polarity scores, the second using Lasso
regression with regularization. Model 1 displays remarkable accuracy, significantly reducing
standard deviations for overly positive and negative reviews, while Models 2 and 3 also
demonstrate acceptable accuracy, enhanced by incorporating one-hot encoded categories and
regularization.

  This research emphasizes the dynamic nature of sentiment trends in Amazon reviews and
underscores the importance of sentiment analysis in understanding consumer feedback nuances.
Future studies may explore alternative sentiment analysis methods and advanced modeling
techniques for enhanced predictive accuracy in comprehending online consumer sentiments


## Contents

The contents of this repository are as follows: 

1) /Analysis: Contains Python Notebooks where we applied the 3 models. 
    - Eda.ipynb : Exploratory Data Analysis of the Amazon Review Data Set
    - Preprocessing and Model1.ipynb : Preprocessing of data to find proportions and implementation of the Simple Linear Regression Model. 
    - Model 2.ipynb : Implementation of the Multiple Linear Model.
    - Model 3.ipynb : Implementation of the Lasso Regression Model.
      
2) /data : contains the subsets of the 5-core Amazon Review Dataset that we obtained.
   - /Original : the 7 specific subsets of we used
       - Kindle, MoviesandTv, Patio, Sports, Tools, Toys, Video Games.
3) /figures : contains the png of graphs and tables used in the report.
4) /narrative : contains one PDF with the Final Project Report.
     - Read here for a more indepth explanation of our project. 
