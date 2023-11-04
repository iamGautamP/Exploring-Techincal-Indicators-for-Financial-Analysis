# "Exploring Technical Indicators for Financial Analytics"
Here we have tried to understand how we can take help of indicators to place our orders wisely.
- **Getting Data from Yahoo Finance**:
  - We started by collecting important financial data from Yahoo Finance, making sure we had a good base to work with.

- **Using VWAP**:
  - We looked at VWAP (Volume-Weighted Average Price) for 13 and 20 days. It helped us see market trends and good times to make a move.
  - We also made our own special indicator from VWAP data, giving us an extra edge in predicting.

- **Using RSI**
  - RSI (Relative Strength Index) came into play, letting us spot those moments of over-eagerness (above 70) and oversold opportunities (below 30) in the market.

- **Using 3EMA**:
  - We used something called Exponential Moving Averages (EMAs) for 12, 24, and 55 days. It helped us know when it's smart to jump in and when to step back.

- **Highs and Lows in Predictions**:
  - We tried something different by using daily high and low data to make a special prediction indicator.

- **MACD**:
  - We used the MACD (Moving Average Convergence Divergence) indicator to guide us. It worked with short, long, and signal lines over 12, 26, and 9 days. This gave us a new way to predict.

- **Getting Ready for the Model**:
  - We organized our data neatly, splitting it into groups for training and testing to see how well our model would do.
  - We also made sure our data was all on the same scale, so we used a tool to do that.

- **Using LSTM for prediction**:
  - Our special tool was an LSTM (Long Short-Term Memory) network. This network was four layers deep (1 input, 2 intermediate, 1 output), each packed with neurons set at 50-50-25-1.
  - With just a little bit of difference towards the end, our model had an overall error rate of only 4.56. It proved it could predict really well!
