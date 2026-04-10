# Time_series_Analysys_with_cryptocurrency

"Time Series Analysis with cryptocurrency" predicts Bitcoin prices using ARIMA, LSTM, and Prophet models and analyzes market sentiment from tweets. It helps traders understand price trends and emotions in the crypto market.

📌 Features
✅ Live Bitcoin Price (Real-time data)
✅ Future Price Predictions (ARIMA, LSTM, Prophet)
✅ Sentiment Analysis of Tweets
✅ Interactive Streamlit Dashboard

📁 Data Used
Bitcoin Price History (bitcoin_prices.csv)
Forecasts (ARIMA, LSTM, Prophet models csv files)
Sentiment Analysis (crypto_sentiment.csv)

🚀 How to Run the Project
1️⃣ Install Dependencies
pip install -r requirements.txt

2️⃣ Run the Streamlit App
streamlit run streamlit_app.py

📊 How It Works
1️⃣ Live Price Fetching: Uses CoinGecko API to get real-time Bitcoin price.
2️⃣ Time Series Forecasting:

ARIMA: Uses past trends for statistical forecasting.
LSTM: Deep learning-based future price prediction.
Prophet: Facebook’s model for time series forecasting.
3️⃣ Sentiment Analysis: Extracts public sentiment from tweets using NLP techniques.
4️⃣ Visualization: Graphs showing price trends, forecasts, and sentiment correlation.