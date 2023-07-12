# Stock Market Prediction System Using Sentimental Analysis and Historical Real-State Stocks Data
Stock market price prediction has been a subject of significant interest and research due to the inherent challenges in accurately forecasting stock prices, primarily driven by the volatile nature of the data. Predicting stock market movements is complex, as it is influenced by various factors including personal fortunes, political events, individual preferences, and natural disasters. These sentiments and opinions expressed through social media platforms, financial news, and blogs play a crucial role in shaping stock market dynamics. It is important to note that stock prices are not solely governed by the law of demand and supply, but also heavily influenced by public sentiment and mood.
In recent years, there has been growing attention on incorporating data from social media platforms such as Facebook and Twitter to enhance the accuracy of stock market predictions. Social media serves as a valuable source of sentiment indicators, known to impact the stock market. This project proposes the utilization of AI algorithms, specifically in Natural Language Processing (NLP), to extract sentiments from social media conversations related to specific companies' stocks. By leveraging this sentiment analysis, it aims to predict stock market prices and train a deep learning model using historical datasets.

## Summary:
To initiate the project, a comprehensive collection of stock data was assembled for five prominent stock tickers: APPL, AMZN, GOOG, FB, and TSLA. The dataset included news article headlines related to these stocks, enabling sentiment analysis. Another dataset was created by aggregating historical stock data, allowing for the exploration of correlations between sentiment scores and the historical performance of stocks. Subsequently, deep learning algorithms were applied to the historical stock data to facilitate prediction. The accuracy and error of the models were carefully measured, and the results were effectively summarized through the utilization of interactive Plotly Dash. This encompassed evaluation scores, informative graphs, and concise tables, providing a comprehensive overview of the project outcomes.
* See flowchart below:


## Data
To obtain the article headlines for the specified stock tickers, the Python Beautifulsoup library was employed for web scraping from FinViz. FinViz is a renowned financial visualization website in the United States that offers a wide range of valuable information, including comprehensive trading data from major banks and regularly updated news headlines for various stocks. In order to gather historical stock data spanning five years, the Yahoo Finance website was scraped using the yfinance library, enabling access to a rich dataset for analysis and modeling purposes.

## Algorithm 
The algorithm here I have used for the stock price prediction is the LSTM, Long short Term Memory networks, that has been observed as the most effective solution in time series forcasting. Long short-term memory (LSTM) is a recurrent neural network (RNN) architecture used in the field of deep learning. Unlike standard feedforward neural networks, LSTM has feedback connections. It can not only process single data points, but also entire sequences of data. LSTM models are able to store information over a period of time. LSTMs have an edge over conventional feed-forward neural networks and RNN in many ways. This is because of their property of selectively remembering patterns for long durations of time.

## Dashboard:

## Access to Material:
The material provided in this repository is made available for reference and educational purposes. You are free to use and modify the material while adhering to the terms of the license mentioned in the repository. When utilizing or referencing this material, please give appropriate credit by mentioning the original creator and the research article:

[Sayed Shahid Hussain]

