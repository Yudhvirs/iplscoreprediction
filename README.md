🏏 IPL Score Prediction using Machine Learning & Deep Learning
📌 Project Overview

This project aims to predict the final innings score of an IPL team based on the current match situation using Machine Learning and Deep Learning techniques. The model takes live match information such as batting team, bowling team, venue, current score, wickets lost, overs completed, striker, batsman, and bowler to estimate the final total score.

To identify the most effective prediction model, multiple algorithms were implemented and compared. The project evaluates the performance of an Artificial Neural Network (ANN), XGBoost Regressor, and Random Forest Regressor using standard regression metrics.

🚀 Features
Data preprocessing and feature encoding
Exploratory Data Analysis (EDA) using Matplotlib and Seaborn
Feature scaling using MinMaxScaler
Deep Learning model using TensorFlow/Keras
Machine Learning models using XGBoost and Random Forest
Model comparison using MAE, MSE, RMSE, and R² Score
Visualization of Actual vs Predicted values and Residual plots
Final score prediction based on match inputs
📊 Models Implemented
Artificial Neural Network (TensorFlow/Keras)
XGBoost Regressor
Random Forest Regressor
📈 Model Performance
Model	MAE	RMSE	R² Score
Artificial Neural Network	14.42	19.73	0.5383
XGBoost Regressor	8.60	11.97	0.8302
Random Forest Regressor	4.99	8.19	0.9204

Random Forest Regressor achieved the best performance and was selected as the final prediction model.

🛠 Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
TensorFlow / Keras
XGBoost
📂 Project Workflow
Data Collection
Data Cleaning and Preprocessing
Exploratory Data Analysis (EDA)
Feature Encoding and Scaling
Model Development
Artificial Neural Network
XGBoost Regressor
Random Forest Regressor
Model Evaluation
Performance Comparison
Final Score Prediction
🎯 Conclusion

This project demonstrates the complete workflow of a machine learning problem, from data preprocessing and exploratory analysis to model development and evaluation. Multiple regression models were trained and compared to identify the most suitable approach for IPL score prediction. Among all the models, the Random Forest Regressor delivered the highest prediction accuracy with an R² Score of 0.9204 and the lowest prediction error, making it the most effective model for this dataset.

⭐ Future Improvements
Use ball-by-ball real-time data for more accurate predictions.
Deploy the model using Streamlit or Flask for an interactive web application.
Perform hyperparameter tuning using GridSearchCV or RandomizedSearchCV.
Incorporate additional match features such as current run rate, recent over performance, and player statistics.
