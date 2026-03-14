Vajra is a Pine Script v5 trading strategy for TradingView built around high-quality EMA pullback entries. It combines multiple confluence filters to avoid low-quality signals and only enters when the market structure is clearly in your favor.
How it works:

Detects an uptrend using a Fast EMA (9) / Slow EMA (15) crossover
Confirms trend strength with ADX (minimum 25 by default)
Validates EMA slope angle to ensure momentum isn't flat
Requires a volume spike above the 20-bar average
Waits for price to pull back near the EMAs within a controlled range
Automatically calculates stop loss (candle low) and take profit based on a configurable Risk:Reward ratio
Risk per trade is fixed in dollar terms for consistent position sizing

Inputs are fully configurable — EMA lengths, ADX threshold, pullback depth, volume multiplier, risk amount, and R:R ratio can all be tuned to your instrument and timeframe.
Built for: BTC 1H TF ONLY! 

RECOMMENDED SETTINGS :
EMA - 9,15
ADX LENGTH - 16
MINIMUM ADX - 35 
MAX PULLBACK % - 1.5 
RR - 1:1

⚠️ DISCLAIMER & RISK WARNING
This strategy is provided strictly for educational and research purposes only. It is not financial advice and should not be used as the sole basis for any real-money trading decisions.

Past performance is not indicative of future results. Backtested results on TradingView may not reflect real-world trading conditions due to slippage, latency, broker fees, and look-ahead bias.
Trading involves significant risk of loss. You can lose some or all of your capital. Never trade with money you cannot afford to lose.
No guarantee of profit. This strategy does not guarantee any specific outcome or return.
Always do your own research (DYOR). Backtest thoroughly on your specific instrument and timeframe before considering live use.
The author is not responsible for any financial losses incurred from using this code.

Use at your own risk.
