### **📊 RSI EA Backtest: Before & After Optimization**  

| **Metric**              | **Baseline Test** (Default Settings) | **Optimized Test** (Adjusted Settings) | **Change**  |
|-------------------------|---------------------------------|--------------------------------|------------|
| **Total Net Profit**     | **+464.20**                      | **-722.84**                    | 🔴 **Worse** |
| **Profit Factor**        | **2.49**                         | **0.59**                        | 🔴 **Worse** |
| **Win Rate**            | **60%** (12/20)                  | **23%** (51/223)               | 🔴 **Worse** |
| **Total Trades**        | **20**                           | **223**                        | 📈 **More Trades** |
| **Max Drawdown (Balance)** | **1.81% ($182.85)**             | **7.23% ($722.84)**            | 🔴 **Higher Risk** |
| **Max Drawdown (Equity)**  | **2.56% ($259.08)**             | **7.30% ($730.44)**            | 🔴 **Higher Risk** |
| **Expected Payoff**      | **$23.21 per trade**             | **-3.24 per trade**            | 🔴 **Negative** |
| **Sharpe Ratio**         | **2.44**                         | **-5.00**                      | 🔴 **Worse** |
| **Long Trades Win %**    | **60%** (6/10)                   | **26.73%** (101/223)           | 🔴 **Worse** |
| **Short Trades Win %**   | **60%** (6/10)                   | **19.67%** (122/223)           | 🔴 **Worse** |

---

### **📉 Why Did the Optimized Test Fail?**
 **Increased Trades (223 vs. 20)**  
   - More trades don’t always mean better performance—quality matters over quantity.  
 **Lower RSI Overbought/Oversold Levels (75/25 vs. 80/20)**  
   - This may have led to more **false signals**, entering bad trades.  
 **Fixed Stop Loss & Take Profit (50 SL, 100 TP)**  
   - Stop Loss may have been **too tight**, causing premature exits.  
 **Higher Lot Size (0.2 vs. 0.1)**  
   - Increased position size led to **higher drawdowns**.  
 **Adjusted Trading Hours (9-17 vs. 7-19)**  
   - The time filter may have **cut off profitable hours** from the base test.  

### ** Key Takeaway**  
The optimized test didn’t improve performance—it **overfitted** and caused worse results. **The original settings worked better** with a 60% win rate and 2.49 profit factor.  

