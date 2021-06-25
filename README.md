# Stock-Price-Prediction
## PROBLEM STATEMENT
One of the most important things to do is to predict how the stock market will do. Physical vs. psychological factors, rational vs. irrational behaviour, and so on are all factors in the prediction. Almost all of these factors combine to make stock prices extremely volatile and difficult to forecast accurately.
In this project, we will be predicting future stock prices through a Long Short Term Memory (LSTM) method. The stock prices for this new duration will be predicted by the already trained LSTM model, and the predicted prices will be plotted against the original prices to visualise the model’s accuracy.

## INTRODUCTION
In the current world, all of us want our money to grow, so we can lead a comfortable life. This is only possible when we invest in stocks. But this does have a downside as we could lose money if we don't invest correctly. So, to reduce risks and increase profits, we have made a model that can predict the future values of the stock market and can also give insights into how the stock has been giving returns over the past 10 years. Our model can be used by investors and traders both, to gain some insight into the stock and thus use it to correctly put their money. It would also help them know when is the best time to enter the market, to leave the shares, or to buy more shares. Along with this, the plots of the Moving Average would help the traders to trade between various stocks and earn profits.

## TERMINOLOGY
1.	Date: Trading date of the stock.
2.	Open: This price of stock’s opening price which means the very beginning price of a particular trading day, but which is not the same price of the previous day's ending price.
3.	High: This is the highest price of the stock on a particular trading day.
4.	Low: This is the lowest stock price during trade day.
5.	Close: This is the closing price of the stock during trade-in particular day.
6.	Adj Close: This is the ending or closing price of the stock which was changed to contain any corporations’ actions and distribution that occurred during trade time of the day.
7.	Sales Volume: This is the number of stocks traded on a particular day.
8.	Daily Return: The daily return measures the dollar change in a stock's price as a percentage of the previous day's closing price. A positive return means the stock has grown in value, while a negative return means it has lost value.
9.	Moving Average:  It is an indicator that shows the average value of a stock's price over a period (i.e. 10 days, 50 days, 200 days, etc) and is usually plotted along with the closing price.
10.	 Expected Return vs Risk: Greater the risk, the larger the expected return and the larger the chances of substantial loss. Investments which carry low risks such as high grade bonds will offer a lower expected rate of return than those which carry high risk such as equity stock of a new company.

## METHODOLOGY

LSTMs are widely used for sequence prediction problems and have proven to be extremely effective. The reason they work so well is because LSTM is able to store past information that is important, and forget the information that is not. LSTM has three gates:
1.	The input gate: The input gate adds information to the cell state
2.	The forget gate: It removes the information that is no longer required by the model
3.	The output gate: Output Gate at LSTM selects the information to be shown as output

It can not only process single data points (such as images), but also entire sequences of data (such as speech or video). LSTM networks are well-suited to classifying, processing and making predictions based on time series data, since there can be lags of unknown duration between important events in a time series. LSTMs were developed to deal with the vanishing gradient problem that can be encountered when training traditional RNNs. Relative insensitivity to gap length is an advantage of LSTM over RNNs, hidden Markov models and other sequence learning methods in numerous applications.
