# Trader Behavior Insights – Market Sentiment Analysis

## Overview
This project explores the relationship between Bitcoin market sentiment
(Fear & Greed Index) and trader performance using historical trading data
from the Hyperliquid platform.

The objective is to understand how trader profitability varies across
different market sentiment regimes and to uncover behavioral patterns
that can inform smarter trading strategies.



## Datasets Used
- **Bitcoin Fear & Greed Index**
  - Provides daily market sentiment classifications such as Fear, Greed, and Neutral.
- **Hyperliquid Historical Trader Data**
  - Includes trade-level information such as execution price, size, timestamps, and Closed PnL.

## Methodology
- Loaded and cleaned both datasets using Python and Pandas.
- Converted millisecond-based timestamps into readable datetime format.
- Aggregated trader Closed PnL on a daily basis.
- Merged daily trader performance with corresponding market sentiment.
- Analyzed average profitability across sentiment categories.
- Visualized results using bar charts.

## Key Insights
- Trader performance varies significantly across market sentiment regimes.
- The highest average profitability is observed during **Fear** periods, suggesting that experienced traders capitalize on market panic and price inefficiencies.
- **Greed** phases show lower or negative average PnL, indicating overconfidence, excessive leverage, or overcrowded trades.
- **Neutral** market conditions exhibit stable but moderate profitability.
## Conclusion
Market sentiment plays a critical role in influencing trader behavior and performance.
The analysis suggests that contrarian strategies during Fear-driven markets can be more profitable,
while disciplined risk management is essential during Greed phases.

## Tools & Technologies
- Python
- Pandas
- Matplotlib
- Google Colab

## Author
Kiran Balbhim Jadhav
