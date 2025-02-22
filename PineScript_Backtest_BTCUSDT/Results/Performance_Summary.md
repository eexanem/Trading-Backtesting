### **Performance Summary - SMA Crossover Strategy (Before Optimization)**  

#### **Overview**  
The SMA crossover strategy was tested using a 50-period short SMA and a 200-period long SMA. The backtest was executed on TradingView using historical data. The strategy places long trades when the short SMA crosses above the long SMA and closes positions when the reverse occurs.  

#### **Key Performance Metrics**  
- **Net Profit:** +37,567.84 USDT (+3.76%)  
- **Profit Factor:** 2.09  
- **Win Rate:** 40.00% (12/30 trades were profitable)  
- **Max Drawdown:** 15,865.35 USDT (1.51%)  
- **Gross Profit:** 72,037.76 USDT  
- **Gross Loss:** 34,469.92 USDT  
- **Largest Winning Trade:** 19,214.00 USDT (29.21%)  
- **Largest Losing Trade:** 4,199.98 USDT (5.14%)  
- **Average Winning Trade:** 6,003.15 USDT (10.05%)  
- **Average Losing Trade:** 1,915.00 USDT (2.48%)  
- **Sharpe Ratio:** 0.138  
- **Sortino Ratio:** 0.259  

#### **Performance Analysis**  
The strategy achieved a **net profit of 37,567.84 USDT** with a **profit factor of 2.09**, indicating that the strategy generates approximately twice as much profit as loss. However, the **win rate is relatively low at 40%**, meaning most trades resulted in losses. Despite this, the high **average win-to-loss ratio (3.135)** suggests that the winning trades were significantly larger than the losing trades.  

The **maximum drawdown of 1.51%** shows that the strategy had a moderate level of risk. However, the **buy & hold return (+132.92%) significantly outperformed the strategy's return (+3.76%)**, indicating that simply holding the asset would have yielded higher gains.  

#### **Next Steps**  
While the strategy is profitable, it has room for improvement. Some potential optimizations include:  
- **Adjusting SMA lengths** (e.g., testing 20/100 or 100/200 combinations)  
- **Filtering trade signals** using additional indicators (e.g., RSI or volume analysis)  
- **Incorporating stop-loss and take-profit levels** to manage risk more effectively  

The next step will be to **optimize the parameters** and compare the results to this baseline performance.  


