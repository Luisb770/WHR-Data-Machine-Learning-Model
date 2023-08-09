# WHR-Data-Machine-Learning-Model
Description:
This GitHub repository contains code for implementing a machine learning project plan focused on analyzing the World Happiness Report (WHR) dataset. The project involves various stages, including data loading, exploratory data analysis (EDA), data preprocessing, model training, evaluation, and improvement. The code is structured as follows:

Part 1: Load the Data Set:
The code loads the WHR dataset from a CSV file and saves it to a Pandas DataFrame. This step is crucial to prepare the dataset for analysis and modeling.

Part 2: Exploratory Data Analysis (EDA):
EDA is performed to analyze the dataset and determine suitable data preparation techniques. Missing values are filled with means, and features are prepared for various prediction tasks. Key tasks include preparing features and labels, splitting data consistently for training and testing, and scaling the data using StandardScaler.

Part 3: Implement Your Project Plan:
In this section, the project plan is executed. The code focuses on predicting different aspects of happiness and well-being using various models:

Linear Regression for Happiness Score Prediction:

A Linear Regression model is trained and evaluated using cross-validation. The root mean squared error (RMSE) is calculated to assess model performance.
Random Forest Regression for Happiness Score Prediction:

A Random Forest Regression model is trained and evaluated using cross-validation. RMSE is calculated as an evaluation metric.
Random Forest Regression for Happiness Rank Prediction:

A Random Forest Regression model is trained and evaluated to predict happiness ranks. RMSE is calculated.
Logistic Regression for Happiness Level Prediction (Classification):

A Logistic Regression model is trained and evaluated using cross-validation to predict happiness levels (categorized). Accuracy is used as an evaluation metric.
Random Forest Classifier for Happiness Level Prediction (Classification):

A Random Forest Classifier model is trained and evaluated using cross-validation to predict happiness levels. Accuracy is used as an evaluation metric.
Regression Models for Predicting Social Support, Healthy Life Expectancy, and Perceptions of Corruption:

Linear Regression models are trained and evaluated for predicting these attributes. RMSE is calculated for evaluation.
The evaluation results are printed, providing insights into the performance of the various models for different prediction tasks. RMSE values and accuracy scores are reported, indicating the quality of the predictions.

Conclusions:
The project demonstrates the practical implementation of a machine learning project plan using the WHR dataset. Through data preprocessing, model training, and evaluation, the code showcases the use of Linear Regression, Random Forest Regression, and Classification models for predicting happiness-related attributes. The code serves as a valuable resource for understanding and applying machine learning concepts to real-world datasets, particularly in the context of happiness prediction.




