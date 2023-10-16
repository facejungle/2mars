# 2mars
### The 2Mars strategy is a trading strategy that aims to enhance trading efficiency by incorporating several simple order opening tactics. These tactics include moving average crossovers, Bollinger Bands, and SuperTrend.

### When entering a position using the 2Mars strategy, there are three methods:
1. Crossing of moving averages: The strategy takes into account the crossing of moving averages as a signal to enter a position.
2. Price crossing Bollinger Bands: If the price crosses one of the Bollinger Bands, it is considered a signal to enter a position.
3. Price crossing the moving average: If the price crosses the moving average, it is also considered a signal to enter a position. The SuperTrend indicator is used for additional confirmation.

### To manage risk, the strategy suggests using stop loss options. There are two options:
1. ATR (Average True Range): The stop loss is updated with each entry order and take-profit. It allows for flexible adjustment of the stop loss when the trend changes. For long positions, the stop loss is set at (low price - ATR * Multiplier), and for short positions, it is set at (high price + ATR * Multiplier).
2. SuperTrend + ATR: The stop loss is updated with every change in the SuperTrend indicator that is not in our favor. For long positions, the stop loss is set at (SuperTrend - ATR * Multiplier), and for short positions, it is set at (SuperTrend + ATR * Multiplier). When using the SuperTrend Confirmation, the stop loss requires confirmation of a change in trend.

#### The strategy also includes three levels for taking profits, which are calculated using standard deviation:
1. 0.618 times the standard deviation
2. 1.618 times the standard deviation
3. 2.618 times the standard deviation

Additionally, the strategy allows for entering a position using a limit order. The calculation for the limit order incorporates the ATR (Average True Range) for a certain period.
