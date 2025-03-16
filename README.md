📈 Stock Price Prediction using KNN
This project predicts stock prices using the K-Nearest Neighbors (KNN) algorithm. The dataset is fetched using the yfinance library, and the model is built using scikit-learn.

🚀 Overview
This project uses historical stock data from yfinance to predict future stock prices.
The KNN algorithm predicts the stock price based on the similarity of data points (neighbors).
Performance is measured using Mean Squared Error (MSE) and R-squared (R²).

🛠️ Technologies Used
Python
yfinance
scikit-learn
NumPy
Pandas
Matplotlib
Seaborn

📂 Dataset
Data Source: Yahoo Finance
Stock Symbol: AAPL (Apple)
Features Used:
Open
High
Low
Volume
Target:
Close (Closing Price)

🧠 How It Works
Download stock data using yfinance
Preprocess data (handle missing values, feature scaling)
Split data into training and testing sets
Train the KNN model
Predict and evaluate using MSE and R²
