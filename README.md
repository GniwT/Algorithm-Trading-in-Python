# **Algorithm Trading**

This project is to demonstrate a trading strategy based on the algorithm combining the market capitalization, quantitative momentum, and P/E ratio. The index presented in this project is S&P 500 Index Fund.

The S&P 500 is the world's most popular stock market index. The largest fund that is benchmarked to this index is the SPDR® S&P 500® ETF Trust. It has more than US$250 billion of assets under management.

The goal of this project is to create a portfolio model based on how much the investment funds from the client. The model will make a suggestion on how many shares of each S&P 500 constituent the client should purchase to get an equal-weight version of the index fund. I will divide the whole models in three sections: the market capitalization, return-of-period, and P/E ratio. Then I will select the optimal 50 stocks in each section

For simplicity, I built this model based on equal-weight strategy. The equal-weight strategy means the investment funds will be allocated equally on the selected stocks. Also, the data is based on free service from Wikipedia and IEX Cloud API. IEX Cloud is a platform that makes financial data and services accessible to everyone. The data is not real-time and may not be accurate.
