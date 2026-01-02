📈 Stock Price Prediction Using Hybrid Model (VADER Sentiment + LSTM)

🔍 Project Overview
This project focuses on predicting Amazon (AMZN) stock prices using a hybrid approach that combines:

📊 Historical stock market data

📰 News sentiment analysis using VADER

🤖 Deep Learning (LSTM model)

By integrating technical price data with market sentiment, the model aims to improve prediction accuracy compared to traditional stock-only models.

🚀 Key Features

Uses VADER (Valence Aware Dictionary and
 Sentiment Reasoner) for news sentiment analysis

Combines sentiment score + historical stock features

Implements LSTM (Long Short-Term Memory) for time-series forecasting

Predicts future closing prices of Amazon stock
Evaluates performance using RMSE
Amazon (AMZN)

🧠 Model Architecture

Data Collection

Historical stock data (Open, High, Low, Close, Volume)

Financial news headlines related to Amazon
Sentiment Analysis

News headlines processed using VADER
Sentiment scores: positive, negative, neutral, compound

Data Preprocessing

Missing value handling


Hybrid Feature Creation
Stock price features + sentiment scores merged
Prediction Model

LSTM Neural Network

Optimized for time-series forecasting
Evaluation

Root Mean Squared Error (RMSE)


🛠️ Technologies & Libraries Used

Python

Pandas, NumPy

Matplotlib, Seaborn

deep learning 

Scikit-learn

TensorFlow / Keras

NLTK (VADER Sentiment Analyzer)