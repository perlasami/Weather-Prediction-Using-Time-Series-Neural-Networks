# Weather-Prediction-Using-Time-Series-Neural-Networks
🌦️ Weather Prediction Using Time Series Neural Networks
📌 Overview
This project tackles the classic weather forecasting problem using time series neural networks. Specifically, it explores LSTM and GRU models to predict future weather conditions such as temperature and precipitation. The goal is to model sequential dependencies from historical weather data and implement multi-step forecasting.

🗓️ Timeline
Duration: March 5 – March 20
Focus: Time-Series Forecasting, Deep Learning, Real-World Data Handling

📊 Dataset
Source: Kaggle Weather Dataset

Description: A curated dataset with time-stamped historical weather variables such as:

Temperature

Humidity

Wind speed

Precipitation

Preprocessing:

Missing value handling

Time series alignment

Feature scaling (e.g., MinMaxScaler)

🧠 Models
Two deep learning architectures were designed and compared:

LSTM (Long Short-Term Memory)

GRU (Gated Recurrent Unit)

Model Highlights:
Sequence-to-one and sequence-to-sequence forecasting

Multi-step ahead prediction

Comparison of model performance using metrics like MAE, RMSE

🔬 Research Basis
Paper Reference:

"A Comparative Study of LSTM and GRU for Time Series Forecasting"
Chung-Cheng Chiu, Yi-Hsuan Yang, Yu-Chiang Frank Wang

Provides empirical comparison of LSTM vs. GRU on time-series data

Inspired model design and evaluation strategy

📈 Results
Both models successfully captured temporal patterns

GRU showed slightly faster training time with comparable accuracy to LSTM

Visualizations included:

True vs. predicted temperature plots

Loss curves across epochs

🛠️ Tools & Frameworks
Python (Pandas, NumPy, Matplotlib)

TensorFlow / Keras

Scikit-learn

Jupyter Notebooks


