🚀 Project Overview
This project presents an end-to-end deep learning framework for stock price prediction using time-series analysis. 
The primary goal is to forecast stock closing prices by leveraging advanced neural network architectures capable of modeling sequential financial data.

The study compares three models:
LSTM
CNN-LSTM
Hybrid CNN + Bidirectional LSTM (Proposed Model)
The proposed hybrid model significantly reduces prediction errors compared to baseline architectures.

📊 Dataset Information
Historical Stock Market Data
Date Range: 2015-01-01 to Latest
Total Records: 2348
Features:
Open
High
Low
Close
Volume
Target Variable: Close Price
Sequence Length: 100 time-steps

Data Preprocessing
Chronological sorting
Missing value handling
Min-Max Scaling (0–1 normalization)
Time-series sequence generation
Train-Test Split

Model Architectures
1️⃣ LSTM Model
Captures long-term dependencies in stock price data.
2️⃣ CNN-LSTM Model
Uses Conv1D for feature extraction + LSTM for sequence modeling.
3️⃣ Proposed Hybrid CNN-BiLSTM Model

Architecture:
Input → Conv1D → MaxPooling → Bidirectional LSTM → Dropout → Dense

Conclusion
The Hybrid CNN-BiLSTM model effectively captures both short-term fluctuations and long-term dependencies in stock market data, 
resulting in improved predictive performance.
This architecture demonstrates strong potential for real-world financial forecasting applications.
