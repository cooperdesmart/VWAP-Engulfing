# VWAP-Engulfing
The purpose of these strategies was to learn the basics of backtesting and importing stock data, and get familar with the python libraries. My goal was to automate trading strategies based on technical analysis indicators and see if they were actually worth using in real-time trading.

The first algo is titled VWAP, and is extremely simple - as well as unsuccessful. For a buy condition to be satified, there must be a break out above (or below for a short entry) VWAP after previously trading below. This was intended to be a high-frequency trading strategy that quickly took profits by scalping quick market moves. In aprox. 18 months, I simulated 1650+ trades with a win rate of 35.9% and a Profit Factor of .84. Clearly, this is alone is not a profitable strategy. 

The second algo in this file is titled Engulfing, since the only criteria for a buy (or sell signal - for short positions) signal is if the current candle Opens below the previous candles Close, and Closes above the previous candles Open. This strategy is suppose to capture market reversals, such as sellers slowing down and letting buyers take control. While I do not think Engulfing is a good strategy on its own, I do believe engulfing candles can be significant in showing a tape reversal.  

Finally, I compiled these two losing strategies, to test if together, they may offer a better chance at identifying a trend. While the results still showed a losing strategy, the win rate % did increase slightly, giving me a little bit of hope for futher experimentation. 
