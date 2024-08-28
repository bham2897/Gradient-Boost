Gradient Boosting Regressor for Predicting Gym, Pool, and Other Fitness Activities

This project demonstrates how to use the Gradient Boosting Regressor algorithm to predict the likelihood of gym, pool, and other fitness center activities based on user data. The analysis includes feature importance visualization and performance evaluation metrics such as R², MSE, and RMSE.

This repository contains Python code that applies the Gradient Boosting Regressor from the sklearn library to predict various fitness-related activities such as gym access, pool access, classes, squash, and more. The project focuses on understanding which features (e.g., age, gender, membership level) most influence these predictions and how accurate the model is in making these predictions.
Data Processing

The script processes the data by converting date columns into numerical formats, encoding categorical variables, and calculating additional features like the frequency of entry.

Model Training

The Gradient Boosting Regressor is used to train a model for each activity. The script splits the data into training and testing sets, fits the model, and evaluates its performance.

Feature Importance Visualization

The script generates bar plots showing the importance of each feature (e.g., age, gender, membership level) in predicting each activity. These plots help identify which factors are most influential in determining gym or pool access, participation in classes, etc.

Evaluation Metrics

The script calculates and prints several evaluation metrics:

R² (R-squared): Indicates how well the model explains the variance in the data.
MSE (Mean Squared Error): Measures the average squared difference between predicted and actual values.
RMSE (Root Mean Squared Error): The square root of the MSE, providing error measurement in the same units as the target variable.
Prediction for Individual Members

The script includes a function to predict the likelihood of different activities for a specific gym member based on their unique key. It also provides a detailed breakdown of their predicted activities.
