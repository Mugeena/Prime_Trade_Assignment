# Bitcoin Market Sentiment vs Trader Performance Analysis

## Objective

The objective of this analysis is to study the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance using Hyperliquid historical trading data.

## Data Sources

1. Bitcoin Fear & Greed Index Dataset
2. Hyperliquid Historical Trader Dataset

## Methodology

* Loaded both datasets using Python and Pandas.
* Checked for missing values and data quality issues.
* Converted date columns into a common format.
* Merged trader data with sentiment data using the trade date.
* Performed exploratory data analysis on profitability, win rate, and trading volume.

## Key Findings

### Profitability

* Extreme Greed produced the highest average profit per trade (67.89).
* Fear generated the highest cumulative profit (3.36 million).

### Win Rate

* Extreme Greed achieved the highest win rate (46.49%).
* Extreme Fear had the lowest win rate (37.06%).

### Trading Activity

* Fear periods recorded the highest number of trades (61,837).
* Fear periods generated the highest trading volume (483.3 million USD).

### Risk Analysis

* The largest single-trade loss (-117,990) occurred during Greed periods.
* Higher profitability during Greed was accompanied by increased downside risk.

## Conclusion

Market sentiment has a measurable impact on trader behavior and performance. Extreme Greed conditions resulted in higher average profitability and win rates, while Fear periods generated the highest trading activity and cumulative profits. These findings suggest that sentiment indicators can be valuable inputs for trading strategy design and risk management.
