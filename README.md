# Stock-Price-Prediction

Exploring the Yahoo Stock Price and investigating effectiveness of different ML models for predicting stock price into the future

Aim: Predict the closing price of the stock in 10 days time 

ML Models Investigated:
- Linear Regression
- Decision Tree
- Random Forest
- Gradient Boosting Regression
- Neural Networks


Data Available from: https://www.kaggle.com/datasets/arashnic/time-series-forecasting-with-yahoo-stock-price/data



Installing TA-Lib:
To install the ta-lib library, need to first install the .whl file with:
    pip install path\to\TA_Lib‑0.4.0‑cp311‑cp311‑win_amd64.whl

Then can use usual pip install ta-lib

There is a binary compatibility issue between ta-lib and numpy, so need to downgrade Numpy:
    pip install numpy==1.24.4 works