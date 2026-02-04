Weather Temperature Forecasting using Time Series Machine Learning
📌 Project Overview

This project focuses on forecasting daily temperature using historical weather data through time-series analysis and machine learning techniques.
The system predicts future temperature values by capturing trends, seasonality, and temporal dependencies in the data.

Both statistical (ARIMA) and deep learning (LSTM) models are implemented and compared to identify the most accurate forecasting approach.

🎯 Objectives

Analyze historical temperature data

Perform preprocessing and time-series exploration

Build forecasting models

Compare ARIMA and LSTM performance

Predict future temperature (next 7 days)

📊 Dataset

Daily temperature records for 3 years

Columns:

date → Date of observation

temp → Daily temperature (°C)

Dataset includes:

Seasonal patterns

Trend variations

Random noise (real-world behavior simulation)

⚙️ Project Workflow
1️⃣ Data Preprocessing

Missing value handling

Date-time indexing

Normalization using MinMaxScaler

Train-test split (80:20)

2️⃣ Exploratory Analysis

Trend visualization

Seasonality identification

Time-series plotting

3️⃣ Models Implemented
🔹 ARIMA (Statistical Model)

Captures linear dependencies

Suitable for stationary time-series

Parameters: (p, d, q)

🔹 LSTM (Deep Learning Model)

Recurrent Neural Network

Captures long-term dependencies

Handles non-linear patterns effectively

Provides better forecasting accuracy

📈 Evaluation Metrics

Models are evaluated using:

MAE (Mean Absolute Error) → average prediction error

RMSE (Root Mean Squared Error) → penalizes large errors

Lower values indicate better performance.

🚀 Results

Both ARIMA and LSTM successfully forecast temperature

LSTM performed better in capturing complex seasonal patterns

Reliable short-term predictions achieved

Future 7-day temperature forecasting implemented

🛠 Tech Stack

Python

Pandas

NumPy

Matplotlib

Scikit-learn

Statsmodels (ARIMA)

TensorFlow / Keras (LSTM)

Google Colab

📂 Project Structure
Weather-Temperature-Forecasting/
│
├── weather_temperature.csv
├── temperature_forecasting.ipynb
├── README.md

▶️ How to Run (Google Colab)

Open Google Colab

Upload dataset (weather_temperature.csv)

Copy the notebook/code

Run all cells

Install dependencies:

pip install pandas numpy matplotlib scikit-learn statsmodels tensorflow

💡 Applications

Weather planning

Agriculture support

Energy demand forecasting

Climate analysis

Environmental monitoring

📌 Key Learning Outcomes

Time-series preprocessing

Feature engineering for sequential data

ARIMA modeling

LSTM neural networks

Model evaluation & comparison

Real-world forecasting pipeline

👨‍💻 Author

Sanjai B
B.Tech – Artificial Intelligence & Data Science
