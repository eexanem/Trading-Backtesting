# **MT4/MT5 EA Backtest – RSI-Based Trading Strategy**  

## ** Project Overview**  
This project evaluates and optimizes an RSI-based trading Expert Advisor (EA) on **EUR/USD** using **MT4’s Strategy Tester**. The goal was to improve profitability by adjusting key parameters.  

## ** Backtest Results: Before vs. After Optimization**  
A **detailed performance comparison** is available in [`EA_Backtest_Report.md`](./EA_Backtest_Report.md), showing how the optimized settings performed against the default.  

| Metric                  | Baseline Test (Default) | Optimized Test (Adjusted) | Change  |
|-------------------------|------------------------|--------------------------|---------|
| **Total Net Profit**    | +464.20                | -722.84                  | 🔴 Worse |
| **Profit Factor**       | 2.49                   | 0.59                      | 🔴 Worse |
| **Win Rate**           | 60% (12/20)            | 23% (51/223)              | 🔴 Worse |
| **Total Trades**       | 20                     | 223                        | 📈 More Trades |
| **Max Drawdown (Balance)** | 1.81% ($182.85) | 7.23% ($722.84)           | 🔴 Higher Risk |
| **Expected Payoff**     | $23.21 per trade       | -$3.24 per trade          | 🔴 Negative |
| **Sharpe Ratio**        | 2.44                   | -5.00                      | 🔴 Worse |

The **optimized test did not improve performance**, highlighting the risk of **overfitting**.  

## ** Folder Structure**  

```
MT4_MT5_EA_Backtest_EURUSD/
│── README.md                 # This file (Project Overview)
│── EA_Backtest_Report.md      # Detailed before/after analysis
│── Results/                   # Stores all screenshots
│   │── baseline_main_graph.png
│   │── optimized_main_graph.png
│   │── ... (other images)
```

## **📸 Screenshots**  
All backtest results are stored in [`Results/`](./Results/), including:  
- Strategy Tester graphs  
- Backtest reports  
- Input settings  

