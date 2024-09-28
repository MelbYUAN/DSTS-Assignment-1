# Sydney Restaurant Rating Prediction

## Overview
This project focuses on predicting restaurant ratings in Sydney based on spatial and categorical data from various eateries. Using machine learning models, the project aims to correlate features like location, cuisine type, and user votes with the restaurant's rating.

## Features
- **Location Data**: Longitude (`lng`) and latitude (`lat`) used to understand spatial influences on ratings.
- **Cuisine Details**: Types of cuisine which may affect consumer preferences and ratings.
- **Aesthetic Attributes**: `cuisine_color` and `restaurant_color` that might impact customer perception.
- **User Interaction**: Number of votes reflecting popularity and customer engagement.

## Dependencies
Ensure you have Python installed along with the following packages:
- pandas
- numpy
- scikit-learn
- matplotlib
- ast
- seaborn
  
## Running the Project
Navigate to the project directory and run the main script:
Assignment.ipynb

## Expected Outcomes
Upon running the script, expect the following:

A set of visualizations showing the distribution of ratings across different cuisines and locations.
Predictive accuracy metrics for each machine learning model used:
Linear Regression
KNN (K-Nearest Neighbors)
SVM (Support Vector Machine)
Random Forest
Logistic Regression
