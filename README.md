# Trader Behavior Under Market Sentiment Regimes

This project analyzes how Bitcoin market sentiment (Fear vs Greed) influences trader behavior and performance on Hyperliquid.

## Approach
- Merged Fear/Greed index with trader execution data (daily level)
- Engineered daily metrics: PnL, win rate, leverage, trade frequency, position size
- Compared Fear vs Greed regimes
- Segmented traders by behavior
- Built a Random Forest model for feature importance

## Key Insights
- Sentiment does not directly predict profitability.
- Greed increases leverage and PnL volatility.
- Behavioral features (especially leverage) matter more than sentiment.

**Conclusion:** Sentiment amplifies risk — trader behavior drives outcomes.

## Tech Stack
Python · Pandas · NumPy · Scikit-learn · Matplotlib
