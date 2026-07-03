# 🏏 IPL Score Prediction using Machine Learning & Deep Learning

## 📌 Project Overview

This project predicts the **final innings score of an IPL team** based on the current match situation using **Machine Learning** and **Deep Learning** techniques.

The model takes real-time match information such as the batting team, bowling team, venue, current score, wickets lost, overs completed, striker runs, batsman, and bowler to estimate the final score.

To identify the most accurate prediction model, three different models were developed and compared:

- Artificial Neural Network (TensorFlow/Keras)
- XGBoost Regressor
- Random Forest Regressor

The models were evaluated using multiple regression metrics, and the **Random Forest Regressor** achieved the highest prediction accuracy.

---

# 🎯 Objectives

- Predict the final IPL innings score.
- Perform data preprocessing and feature engineering.
- Compare Deep Learning and Machine Learning models.
- Select the best-performing model based on evaluation metrics.

---

# 📂 Dataset

The dataset contains historical IPL match information with features including:

- Batting Team
- Bowling Team
- Venue
- Current Runs
- Wickets Lost
- Overs Completed
- Striker Runs
- Batsman
- Bowler
- Final Score (Target Variable)

---

# ⚙️ Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Encoding
5. Feature Scaling using MinMaxScaler
6. Model Building
7. Model Evaluation
8. Performance Comparison
9. Final Score Prediction

---

# 🔍 Exploratory Data Analysis (EDA)

The dataset was analyzed using different visualization techniques to understand feature relationships.

Performed EDA using:

- Heatmap
- Correlation Analysis
- Distribution Plots
- Feature Relationship Analysis

---

# 🧠 Models Implemented

### 1. Artificial Neural Network (ANN)

- TensorFlow / Keras
- Dense Neural Network
- Regression Output Layer

---

### 2. XGBoost Regressor

A gradient boosting algorithm that provides high prediction accuracy by combining multiple decision trees.

---

### 3. Random Forest Regressor

An ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

---

# 📊 Model Performance

| Model | MAE | RMSE | R² Score |
|------|------:|------:|------:|
| Artificial Neural Network | 14.42 | 19.73 | 0.5383 |
| XGBoost Regressor | 8.60 | 11.97 | 0.8302 |
| ⭐ Random Forest Regressor | **4.99** | **8.19** | **0.9204** |

---

# 🏆 Best Model

After comparing all three models, the **Random Forest Regressor** achieved the best performance.

### Final Results

- **Model:** Random Forest Regressor
- **MAE:** 4.99
- **RMSE:** 8.19
- **R² Score:** 0.9204

The Random Forest model produced the lowest prediction error and the highest coefficient of determination (R²), making it the most accurate model for this dataset.

---

# 📈 Evaluation Metrics

The models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras
- XGBoost
- Random Forest

---

# 🚀 Key Features

- Data Cleaning and Preprocessing
- Feature Encoding
- Feature Scaling
- Exploratory Data Analysis
- Deep Learning Model
- Machine Learning Models
- Model Comparison
- Performance Evaluation
- IPL Score Prediction

---

# 📌 Results

The project demonstrates that traditional Machine Learning algorithms can outperform Deep Learning models on structured tabular datasets.

Among all implemented models, the **Random Forest Regressor** delivered the highest prediction accuracy and was selected as the final prediction model.

---

# 🔮 Future Improvements

- Deploy the project using Streamlit or Flask.
- Use real-time IPL match data.
- Perform Hyperparameter Tuning.
- Add player statistics and recent match performance.
- Improve prediction accuracy using advanced ensemble methods.

---

# 👨‍💻 Author

**Yudhvir Singh**

M.Tech AI|ML

Machine Learning | Deep Learning | Data Science Enthusiast

---

⭐ If you found this project useful, consider giving it a star!
