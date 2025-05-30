# Quantitative Trading Strategies

This project showcases a series of quantitative trading strategies, built in stages, to identify high-probability trading opportunities based on technical indicators and market dynamics. Additionally, I have implemented trading strategies that focus more on commodities rather than stocks, targeting areas such as credit risk and energy markets.

**Note:** The strategies in **Level 3** and **Level 4** represent the most advanced techniques in this project. While they contain more sophisticated methods, they build upon the foundations established in **Level 1** and **Level 2**. Please note that **Level 4** is actively used for real-time trading and is not publicly available. However, Levels 1–3 provide a comprehensive view of the system's capabilities.

## Project Structure:

**[Quantitative Analysis: Credit and Commodities](notebooks/credit_risk_and_gas_forecasting/README.md)** 

This project (from JPM) includes two practical quantitative analyses: one models the likelihood of credit defaults using borrower FICO scores, and the other evaluates gas storage contracts by forecasting future prices to estimate their financial value. Both use real data and focus on applying data-driven methods to real-world financial and energy markets.

**[Level 1 – Momentum Riding and Dip Buying](notebooks/Level_1_Momentum_Dip_Buying.ipynb)** 

The first level focuses on riding momentum in established trends, with entries triggered by short-term pullbacks ("dips"). The goal is to buy these dips and profit from the continuation of the trend.

**[Level 2 – Moving Average Crossover with RSI Confirmation](notebooks/Level_2_MA_Crossover_RSI.ipynb)** 

The second level introduces simple moving average (SMA) crossovers to identify trend changes, with RSI acting as a confirmation tool to reduce false signals during periods of low momentum.

**[Level 3 – Advanced Multi-Factor Enhancements](notebooks/Level_3_Advanced_Multi_Factor.ipynb)** 

At this level, more advanced techniques are incorporated, including exponential moving averages (EMA), slope (first derivative) analysis, and layered RSI-based filters. These enhancements aim to refine entry and exit points, improve trend detection, and reduce false signals to better manage and minimize risk.

**Level 4 – Proprietary Multi-Dimensional Signal Optimization**

This is the most advanced iteration of the strategy, using higher-order derivatives and second-order momentum analysis to spot early market shifts and optimize trades. It adapts to changing market conditions using dynamic, multi-faceted filters for greater precision.          
**Note: This strategy is not publicly available as it is actively used for real-time trading.**


## Technologies Used

- Python
- Pandas
- Numpy
- Matplotlib / Seaborn (for data visualization)
- Backtesting frameworks (e.g., Backtrader)

## Next Steps

- Refactor and clean up code for better organization
- Add backtesting results and performance visualizations
- Continue building and trading on Level 4 strategies
