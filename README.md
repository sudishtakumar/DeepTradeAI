# DeepTradeAI
## 📈 Deep Reinforcement Learning for Stock Trading  


## Overview
This project applies **Deep Reinforcement Learning (DRL)** techniques to stock trading using a subset of the **Dow Jones Industrial Average (DJIA)** companies.  
The DRL agent learns to **Buy / Sell / Hold** based on stock market data to maximize cumulative returns.  

This project explores the use of Deep Reinforcement Learning (DRL) to develop and evaluate stock trading strategies. The project is based on cutting-edge research and aims to leverage advanced DRL techniques to optimize trading decisions.

## 🏢 Companies (Ticker → Full Name)  

| Ticker | Company Name |
|--------|--------------|
| AAPL   | Apple Inc. |
| AXP    | American Express Company |
| BA     | The Boeing Company |
| CAT    | Caterpillar Inc. |
| CSCO   | Cisco Systems, Inc. |
| CVX    | Chevron Corporation |
| DIS    | The Walt Disney Company |
| DOW    | Dow Inc. |
| GS     | The Goldman Sachs Group, Inc. |
| HD     | The Home Depot, Inc. |
| IBM    | International Business Machines Corporation |
| INTC   | Intel Corporation |
| JNJ    | Johnson & Johnson |
| JPM    | JPMorgan Chase & Co. |
| KO     | The Coca-Cola Company |

## 🧠 Deep Reinforcement Learning Setup  
### **Environment**
- **State (Observation):**
  - Historical prices (OHLCV data: Open, High, Low, Close, Volume)
  - Technical indicators (SMA, RSI, MACD, Bollinger Bands, etc.)
  - Portfolio status (cash balance, holdings)

- **Action Space:**
  - `0 = Hold`
  - `1 = Buy`
  - `2 = Sell`
- Implement and compare various DRL agents for stock trading.
- Evaluate the performance based on return, volatility, and Sharpe ratio.
- Include transaction costs in the trading environment for realistic simulations.

**Reward Function:**
  - Profit/Loss for each step
  - Can be enhanced with **Sharpe Ratio** or **Risk-Adjusted Return**

### **Algorithms Used**
- **DQN** (Deep Q-Network)  
- **PPO** (Proximal Policy Optimization)  
- **A2C / A3C** (Advantage Actor-Critic)  
- **DDPG** (Deep Deterministic Policy Gradient)  

---

## Environment Setup
1. **Install Dependencies**:
    - Install necessary packages such as
 ## ⚙️ Libraries & Tools  

- `Python 3.9+`  
- `pandas`, `numpy`, `matplotlib` – Data Handling & Visualization  
- `stable-baselines3` – RL Algorithms  
- `FinRL` – Financial Reinforcement Learning Library  
- `yfinance` – Stock price data  
- `gymnasium` – RL Environments  

2. **Clone the Repository**:
    - Clone the GitHub repository and navigate to the project directory.
    ### 1. Clone Repository
```bash
git clone https://github.com/yourusername/stock-drl.git
cd stock-drl

