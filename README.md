# Predicting Stock Prices using LSTM and News Sentiment Analysis


![image](https://user-images.githubusercontent.com/96855684/236266774-0770bbf3-53d6-4d56-a928-f30bbc9c19ba.png)



**Description:**

This project aims to predict the stock prices of a particular company using historical stock data and news sentiment analysis. The idea is to combine both technical and fundamental analysis in predicting the stock prices, since stock prices can be influenced by both factors.

**Situation:**

Stock price prediction is a challenging problem in the finance industry, as it is influenced by a wide range of factors. Technical analysis, which uses past stock prices and trading volume to predict future prices, is one approach that has been traditionally used. However, there is increasing interest in combining this with fundamental analysis, which takes into account other factors such as company financials, industry trends, and news sentiment analysis.

**Task:**

The task of this project is to predict the stock prices of a particular company using both technical and fundamental analysis. Specifically, we use an LSTM neural network to model the time-series behavior of the stock prices, and incorporate news sentiment analysis to capture the impact of news on the stock prices.

**Action:**

The project follows the following steps:

Load and preprocess the historical stock data and news data.
Merge the two datasets based on their dates.
Scale the data using MinMaxScaler to ensure all data is within a specified range.
Create input/output sequences for the LSTM model.
Train the LSTM model on the input/output sequences.
Test the LSTM model on new data and evaluate its performance using root mean squared error (RMSE).

**Result:**

The project was able to successfully predict the stock prices of a particular company using both technical and fundamental analysis. By incorporating news sentiment analysis, the model was able to capture the impact of news on the stock prices and improve its accuracy. The model achieved a test score of 2.87 RMSE, which is a significant improvement over the baseline score of 21.53 RMSE.

In conclusion, this project demonstrates the potential of combining technical and fundamental analysis in predicting stock prices, and highlights the importance of news sentiment analysis as an additional factor in stock price prediction.
