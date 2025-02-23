### **Performance Summary - SMA Crossover Strategy (Before & After Optimization)**  

#### **Overview**  
The SMA crossover strategy was tested using two different configurations:  
1. **Before Optimization** - Short SMA: 50, Long SMA: 200  
2. **After Optimization** - Short SMA: 20, Long SMA: 100  

The strategy enters long trades when the short SMA crosses above the long SMA and closes positions when the reverse occurs.  

---

### **Key Performance Metrics**  

| Metric                  | Before Optimization (50/200) | After Optimization (20/100) |
|-------------------------|----------------------------|-----------------------------|
| **Net Profit**          | +37,567.84 USDT (+3.76%)   | **+52,598.05 USDT (+5.26%)**  |
| **Profit Factor**       | 2.09                        | **2.07**                     |
| **Win Rate**           | 40.00% (12/30 trades)      | **42.11% (24/57 trades)**    |
| **Max Drawdown**       | 15,865.35 USDT (1.51%)     | **13,789.53 USDT (1.30%)**   |
| **Gross Profit**       | 72,037.76 USDT             | **101,598.05 USDT**          |
| **Gross Loss**         | 34,469.92 USDT             | **49,162.00 USDT**           |
| **Largest Win**        | 19,214.00 USDT (29.21%)    | **27,541.57 USDT (39.92%)**  |
| **Largest Loss**       | 4,199.98 USDT (5.14%)      | **4,240.02 USDT (6.33%)**    |
| **Avg. Win Trade**     | 6,003.15 USDT (10.05%)     | **4,240.00 USDT (7.02%)**    |
| **Avg. Loss Trade**    | 1,915.00 USDT (2.48%)      | **1,489.76 USDT (2.03%)**    |
| **Sharpe Ratio**       | 0.138                       | **0.237**                     |
| **Sortino Ratio**      | 0.259                       | **0.677**                     |

---

### **Performance Analysis**  
The optimized strategy (SMA 20/100) showed **better overall profitability**, increasing **net profit from +37,567.84 USDT to +52,598.05 USDT** and improving the **win rate from 40% to 42.11%**. Additionally, the **maximum drawdown decreased from 1.51% to 1.30%**, indicating a lower risk level.  

However, the **profit factor remained nearly the same (2.09 → 2.07)**, suggesting that while the strategy executed more trades and had a higher overall profit, the efficiency of wins vs. losses did not change significantly. The **Sharpe and Sortino ratios improved**, indicating slightly better risk-adjusted returns.  

One noticeable difference is that the **average winning trade was smaller in the optimized strategy** (6,003.15 USDT → 4,240.00 USDT), but the **average losing trade was also smaller**, meaning the optimization resulted in more frequent but slightly smaller profitable trades.  

### **Conclusion**  
- The optimized strategy **increased net profit** and **slightly improved the win rate**, while also **reducing drawdown and improving risk-adjusted returns**.  
- However, it did not significantly change the **profit factor**, meaning the balance between winning and losing trades remained similar.  

### **Potential Next Steps**  
- Further testing with **different SMA values** (e.g., 10/50, 100/200)  
- **Adding filters** (e.g., RSI, volume) to refine trade signals  
- **Exploring stop-loss/take-profit levels** to manage risk better  

This analysis provides a foundation for further refinement and optimization of the strategy.  

