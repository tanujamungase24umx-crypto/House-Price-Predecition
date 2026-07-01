# 🏡 House Price Prediction using Machine Learning

## 📌 Project Overview

This project predicts house prices using a **Random Forest Regression** model. It demonstrates a complete end-to-end machine learning workflow, including data preprocessing, feature engineering, model training, evaluation, and prediction.

The goal is to build an accurate and reliable model that estimates house prices based on property characteristics.



## 🚀 Features

* 📊 Data Exploration and Analysis
* 🧹 Data Cleaning and Preprocessing
* 🔄 Handling Missing Values
* 🏷️ Encoding Categorical Features
* ✂️ Train-Test Data Splitting
* 🤖 Random Forest Regression Model
* 📈 Model Evaluation (MAE, MSE, RMSE, R² Score)
* 💾 Save and Load Trained Model using Joblib
* 🏠 Predict House Prices for New Data



## 📂 Project Structure


House-Price-Prediction/
│── dataset_2.csv
│── House_Price_Prediction.ipynb
│── house_price_model.pkl
│── requirements.txt
└── README.md


## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Joblib


## ⚙️ Machine Learning Workflow

1. Load Dataset
2. Explore Data
3. Handle Missing Values
4. Feature Selection
5. Data Preprocessing
6. Train-Test Split
7. Train Random Forest Regressor
8. Evaluate Performance
9. Save Trained Model
10. Predict House Prices


## 📈 Model Performance

| Metric   | Score            |
| -------- | ---------------- |
| MAE      | 34,280.64        |
| MSE      | 1,921,948,518.44 |
| RMSE     | 43,840.03        |
| R² Score | **0.9091** ✅     |

### ⭐ Model Accuracy

The Random Forest Regression model achieved an **R² Score of 0.9091**, indicating that it explains approximately **90.9%** of the variation in house prices, making it a strong and reliable predictive model.


## ▶️ Installation

git clone https://github.com/your-username/House-Price-Prediction.git

cd House-Price-Prediction

pip install -r requirements.txt


## ▶️ Run the Project

jupyter notebook House_Price_Prediction.ipynb


## 📊 Example Prediction

Input Features:

* Area: 2200 SqFt
* Rooms: 4
* Build Year: 2015
* Location: Urban
* Street Type: Paved
* Furnishing: Furnished
* Property Type: Villa
* Pool: Yes

Output:

Predicted House Price: <Predicted Value

## 📌 Future Improvements

* Hyperparameter Tuning
* Cross Validation
* XGBoost and LightGBM Comparison
* Feature Importance Visualization
* Deploy with Flask or Streamlit
* Interactive Web Application

