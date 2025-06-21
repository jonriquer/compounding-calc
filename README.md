# Aggressive Compounding Calculator for SPX Iron Condors

## 📈 Strategy Overview

This tool supports an **SPX Iron Condor** strategy with an **aggressive compounding** model. The strategy involves:

- Selling **1-day-to-expiration (1DTE) SPX Iron Condors**
- Collecting **small, consistent premiums** with high probability of max profit
- Reinvesting profits into larger position sizes (more contracts) as capital grows
- Minimizing exposure by maintaining defined risk per level

The goal is to **scale up rapidly** using compounding gains while strictly managing max risk at each stage.

---

## 🎯 Purpose of This Calculator

This calculator is designed to:

- Dynamically determine how many contracts to trade at each level
- Show potential **profit at level exit** and **maximum risk per level**
- Track **cumulative capital risked** from the starting level to the max level
- Aid in **position sizing** based on available capital and user-defined inputs

---

## 🧮 Key Inputs

- **Capital**: Total capital available for this strategy
- **IC Premium**: Net premium collected per Iron Condor (after commissions)
- **IC Fees**: Commission/fees per Iron Condor
- **Starting Level**: Which level the user wants to begin compounding from

---

## 📊 Output Definitions

| Term | Description |
|------|-------------|
| **Contracts** | Number of Iron Condor contracts traded at each level |
| **Level Exit Profit** | Total net premium collected at that level |
| **Level Max Risk** | Maximum potential loss at that level if the position goes against you |
| **Cumulative Risk** | Total capital at risk across all levels from starting level onward |

---

## ⚠️ Risk Disclaimer

This strategy is highly aggressive and not suitable for all investors. Losses at higher levels can be significant. Always trade with capital you can afford to lose and understand the risk of selling options.

---

## 🛠️ Built For

- Options traders scaling a 1DTE SPX strategy
- Traders seeking structured position sizing rules
- Users looking to automate or discipline their risk management process

---

