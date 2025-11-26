📊 Predictive Sales Model (Machine Learning Project)

This project builds a predictive sales model for a retail company using machine learning techniques.
It follows a full end-to-end pipeline:

🚀 Project Overview

The goal of this project is to:

Prepare and clean sales data

Analyze trends and insights

Create predictive features

Train a machine learning model

Predict future sales amounts

Evaluate performance with metrics and visuals

We used a realistic sales dataset downloaded from Google (CSV format) to simulate a real retail environment.

📂 Project Structure
predictive-sales-model/
│
├── Data/
│   └── synthetic_sales_dataset.csv
│
├── notebook/
│   └── 01_data_analysis.ipynb
│
└── README.md

🧠 Technologies Used

Python

Pandas

NumPy

Scikit-Learn

Matplotlib

Seaborn

Jupyter Notebook

🛠️ Machine Learning Model Used

We trained a Linear Regression model to predict total sales based on:

Date

Product category

Price

Quantity sold

📈 Model Performance
Metric	Score
MAE	46.79
RMSE	70.52
R² Score	0.85

The model explains 85% of the variance in sales, which is strong for a baseline model.

📊 Visuals Included

Sales trends over time

Total sales by category

Correlation heatmap

Actual vs predicted scatter plot

🔮 Future Improvements

Add seasonal features (holidays, weekends)

Train more advanced models (Random Forest, XGBoost)

Deploy model as an API

Integrate into a dashboard
