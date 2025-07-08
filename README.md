# Flight Fare Prediction 

## Overview
Flight fares are highly dynamic and depend on various factors such as airline, source, destination, departure time, and duration. This project aims to build a machine learning model that can accurately predict flight ticket prices using historical data.

## Problem Statement
Airline ticket prices fluctuate based on numerous variables like travel time, duration, airline brand, and holidays. Predicting fares in advance can help travelers save both money and time. The goal is to use machine learning to forecast flight ticket prices using structured historical data.

## Dataset
The dataset used in this project is publicly available on Kaggle:  
🔗 [Flight Fare Prediction - Kaggle Dataset](https://www.kaggle.com/datasets/nikhilmittal/flight-fare-prediction-mh)

## Tech Stack and Tools
- **Python**
- **Pandas, NumPy** – Data manipulation and analysis
- **Matplotlib, Seaborn** – Data visualization
- **Scikit-learn** – Machine learning models
- **Jupyter Notebook**

## Machine Learning Models Used
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

## Key Steps in the Project
1. **Data Preprocessing**  
   - Handling missing values  
   - Encoding categorical variables  
   - Feature extraction and selection

2. **Exploratory Data Analysis (EDA)**  
   - Visualizing patterns in fare prices  
   - Understanding distributions and correlations

3. **Model Building & Evaluation**  
   - Training multiple regression models  
   - Comparing model performance using metrics like R² Score and MAE  
   - Achieved up to **96% accuracy**

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/flight-fare-prediction.git
   cd flight-fare-prediction
   
2. Install dependencies:
   ```bash
   pip install -r requirements.txt

3. Run the notebook:
   ```bash
   jupyter notebook flight_fare_prediction.ipynb

