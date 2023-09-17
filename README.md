# Quantiative Momentum Investing Strategy

This project is a quantitative momentum investment strategy created using Python and various libraries, such as NumPy, Pandas, Requests, and Scipy. Its primary objective is to identify the top 50 stocks exhibiting the highest price momentum within the S&P 500 index and subsequently calculate the optimal number of shares for an equal-weight portfolio. To achieve this, I leveraged the IEX Cloud API to retrieve stock data and financial information for the S&P 500 stocks.

To identify high-quality momentum stocks (those that consistently outperform over long periods of time), I considered not only the one-year price return but also the six-month, three-month, and one-month price returns. To implement this HQM (High-Quality Momentum) investing strategy, I first imported the latest S&P 500 stock data and retrieved the required price return metrics. Subsequently, I calculated the stocks based on their HQM Score. This score enabled me to identify and rank the top 50 high-quality momentum stocks from the S&P 500. 

To cater to various portfolio sizes, I integrated a user input system, allowing users to input their desired portfolio funds and calculate the precise number of shares required for an equal-weighted portfolio of these high-quality momentum stocks, which can be downloaded as an excel file.
