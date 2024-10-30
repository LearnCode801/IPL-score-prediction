---

# IPL Innings Score Prediction

## Project Overview

This project aims to predict the score of an innings in an IPL (Indian Premier League) match using various machine learning techniques. By analyzing historical IPL data, the model forecasts the score based on parameters such as current score, overs, and other in-game features.

![Project Overview](https://github.com/LearnCode801/IPL-score-prediction/blob/main/Screenshot%202024-10-30%20132355.png)  
*Web App Image.*

## Objectives

- Conduct exploratory data analysis (EDA) on IPL match data.
- Train a machine learning model to predict the innings score based on the input features.
- Deploy the model using a web framework for real-time predictions.

## Project Workflow

### 1. Data Collection and Preprocessing
- Load and preprocess the IPL dataset to handle missing values, convert data types, and clean columns.
- Perform feature engineering to extract relevant inputs for the model.

### 2. Exploratory Data Analysis (EDA)
- Analyze distribution of features, identify correlations, and visualize data insights.
- Key features include total runs, number of overs, wickets taken, and match location.

### 3. Model Training
- Train machine learning models to predict scores using the cleaned dataset.
- Models explored include:
  - Linear Regression
  - Decision Trees
  - Random Forest

### 4. Model Evaluation
- Evaluate models based on metrics such as MAE, MSE, and R-squared scores.
- Compare models to select the best performing model for deployment.

### 5. Deployment
- Use Flask or a similar web framework to create an API for the model.
- Integrate the model into a web application for live predictions during matches.

## Files and Structure

- **data/**: Contains IPL match data used for model training.
- **notebooks/**: Jupyter notebooks with EDA, model training, and evaluation steps.
- **model/**: Saved model files using Pickle for deployment.
- **app.py**: Flask application to serve the model API.

## How to Run

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Run the Flask app:
   ```bash
   python app.py
   ```

3. Access the application locally at `http://127.0.0.1:5000`.

## Future Improvements

- Experiment with advanced models like XGBoost for improved accuracy.
- Integrate additional features such as player statistics and match conditions.

--- 
