## Stock-market-prediction
Stock market analysis and prediction of India and China using ML. 
Built this model as a part of my project work at College, with the hopes of publishing a research paper.😅

# Models
Long short-term memory(LSTM), testing using chow test, ADF test and structural break test.

# Libraries 
Tensorflow(Dense, LSTM, Sequential), scikit learn(MinMaxScaler), datetime, matplotlib, yfinance, pandas,  statmodels(OLS, Bartelett,ChowTest,adfuller,coint_johansen , VAR), ruptures, numpy, scatter_matrix.

# Abstract 
Stock markets of India and China have shown remarkable growth in recent years. But the stock market returns in these countries are affected by macroeconomic and political factors. Economic factors such as inflation and GDP growth play a significant role in shaping returns in both countries. This study examined the relationship between these factors and stock market Returns in India and China. We have taken past 20 years data for NIFTY 50 index and past 15 years data for HSI index. We study the stock market returns of these indexes over the past two decades and forecast it to predict the stock market returns over the next 365 days using the LSTM model.
However, the data collected and preprocessed can show some anomalies, dips and fluctuations so we perform the augmented decay fuller test for checking stationarity of our time series and structural break test for checking for breaks in the data. The study concludes with interpretations of various breaks and dips along the past 20 years for nifty 50 and HSI. 

# Detailed Submission
https://docs.google.com/document/d/1SGXxBg92LAY2dqyll_iNx32NtAcQ_4r3sy-Mqcw-M4I/edit?usp=sharing
