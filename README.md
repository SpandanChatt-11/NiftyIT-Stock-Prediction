# Overview
When it comes to financial markets then stock market trading is an important activity. Even
with the uncertain and volatile nature in the prices of stocks, an investor tries to predict
the future prices of stocks in order to minimize the losses and gain the maximum possible
profit. In this paper we have used some machine learning techniques namely - Simple Linear
Regression, Polynomial Regression, Multiple Linear Regression, Ridge Regression and Lasso
Regression for predicting stock price of 10 Nifty IT companies of National Stock Exchange
of India using the daily data of stock prices of the listed companies. A comparative analysis
of the aforementioned algorithms are provided in a tabulated and graphical form for better
analysis. Through our proposed method stakeholder can invest confidently with a minimal
Mean Absolute Error of Rs.15.92, Root Mean Squared Error of Rs.27.35 and maximum R2
value of 0.999.

# About
Due to the volatility and uncertainty of stock market, predicting the behavior of stock prices
is a growing topic to research. The negative correlation between stock returns and volatility is
a well established fact in many research articles. Stock market indicates
the financial power of a country, it is also a good indicator of the economy. A decline in
stock market results is recession and a strong stock market indicates the booming in economy.
Further stock market can be good source of income. Even though the unpredictable nature
of stock market, stake holders want to get their hands on something that would provide
them higher profit by trying to predict the behavior of stock market.

There are several factors that influence the stock market, namely economic indicators, mar-
ket sentiment, and external events. Market trends are shaped by economic indicators like
inflation, interest rates and unemployment rates which provide an overview of how well the
economy is doing. Additionally, stock prices depend on corporate earnings and financial
performance as shown by their annual reports. The fluctuations in the market depend on in-
vestor perceptions and emotions through which news rumors, market trends lead to changes
in the capital markets. Furthermore, there are also geopolitical events that will move a
government policy or any global economic conditions resulting in volatile times as investors
worry about any uncertainty that could affect their investments Understanding these fac-
tors is important for those wishing to effectively navigate through the complexity of this
environment.

Almost every country has one or more stock exchanges, where the shares of listed companies
can be sold or bought. In India the BSE(Bombay Stock Exchange) and the NSE(National
Stock Exchange) are the two most active stock exchange. The BSE has around 5000 listed
companies where as NSE had around 1600. Both the exchange has similar trading mechanism
and market open time, closing time and settlement process.

The process of determining the future stock price of a company is called stock market
forecasting. Predicting stock market prices involves analyzing historical data, market trends,
and economic indicators using statistical methods and machine learning algorithms[9]. Thus
in this paper we have used machine learning techniques, namely - Simple Linear Regression,
Polynomial Regression, Multiple Linear Regression, Ridge Regression, Lasso Regression an
Elastic Net to predict the behavior of stock prices of Nifty IT companies. Lastly we did a
comparative analysis of the aforementioned methods.

# About the data
In this paper we have worked on the Nifty IT companies of National Stock Exchange of
India, which are Wipro, Infosys, TCS, HCL Technologies, Tech Mahindra, Coforge, Mphasis,
Persistent, L&T Technologies Services (LTTS), Ltimindtree (LTIM). We have collected the
daily data of stock prices of each of the company from Jan-2008 to June-2024 (Except LTTS
and LTIM as the data of these two companies were available from Oct-2016 and The data of
Persistent is from May-2010 ) from ’finance.yahoo.com’. The data consists of Six variables,
those are Date, Open, High, Low, Close and Volume.

The first variable in our data is date which is recorded in the form Day-Month-Year. It tells
us the date for which the opening price, closing price, highest price, lowest price and volume
are recorded.

The second variable is Open, which indicated the opening price of a share of stock when
the stock market exchange opens for trade. it is measured in INR. Opening price is a good
predictor to forecast the behavior of stock market. It is one of the independent variables
that we have used to predict the closing price.

The third variable that we have is High, which indicates the highest price of a share of stock
on a particular day. It is measured in INR. The highest price is the maximum price for which
a share of stock is traded on that day.

The fourth variable is Low, that tells us the lowest price of a share of stock on a particular
day. It is measured in INR. The lowest price is the minimum price of a share of stock for
which it was traded on that day.

The fifth variable in our data is Close, which tells us the closing price of a share of stock
at the end of the day when the stock exchange closes. It is measured in INR. The closing
price is our dependent variable that means we will predict the value of closing price by the
available data of high, low, open and volume.

The sixth variable that we have is volume, that indicates the number of shares traded on a
particular day.

# Results
In this paper our target was to develop machine learning models that would be capable of
predicting stock price with an high accuracy. Through the help of these models the stake-
holders would be able to experience increased profit by investing on right time. The machine
learning techniques namely, Simple Linear Regression, Polynomial Regression, Multiple Lin-
ear Regression, Ridge Regression and Lasso Regression are used to predict the stock price
of Nifty IT companies, which are - Wipro, HCL tech, Infosys, Tech Mahindra, Coforge,
LTTS, LTIM, TCS, Mphasis, Persistent. We have used the daily data of stock prices of
each of the company from Jan-2008 to June-2024 (Except LTTS and LTIM as the data of
these two companies were available from Oct-2016 and The data of Persistent is from May-
2010 ). After successful implementation of the aforementioned Machine Learning techniques
we observed that Multiple Linear Regression has the minimum MAE (15.923981), minimum
RMSE (27.353042) and R-squared value (0.999222) very close to 1, followed by the Ridge
regression that provides MAE=15.923681 RMSE=27.353043 with an R-squared value same
as Multiple Linear Regression.
So, by using Multiple Linear Regression almost 100% variation in Close can be explained by
Open and Volume as the R-squared value is very close to 1, with an MAE of 15.923981 and
RMSE of 27.353043.
