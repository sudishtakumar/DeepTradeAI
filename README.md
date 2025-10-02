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
git clone https://github.com/sudishtakumar/DeepTradeAI.git
cd stock-drl




## Steps to Run the Project
1. **Prepare the Stock Data**:
    - Ensure your stock data is in a suitable format (e.g., CSV files).
    - Load the data into the environment.

2. **Define the Trading Environment**:
    - Create a custom trading environment (`StockTradingEnv`) that includes transaction costs.
    - Define the observation and action spaces for the environment.

3. **Implement DRL Agents**:
    - Implement various DRL agents using algorithms such as PPO, A2C, DDPG, SAC, TD3.
    - Train the agents on the custom trading environment.

4. **Evaluate the Agents**:
    - Calculate daily returns, standard deviation, and Sharpe ratio for each agent.
    - Compare the performance of the agents based on these metrics.

5. **Plot the Results**:
    - Visualize the performance metrics using bar charts.
    - Highlight the best-performing agents based on the Sharpe ratio.

## Results
- **DDPG Agent** showed the highest return and Sharpe ratio, despite higher volatility.
- **TD3 Agent** and **Ensemble Agent** also performed well, balancing return and risk.
- **PPO Agent** underperformed, indicating the need for further optimization.
##📊 Output

Portfolio value growth over time

Cumulative rewards vs baseline (Buy & Hold)

Trading decisions (Buy/Sell points on chart)
## Key Takeaways
- Advanced DRL algorithms like DDPG and TD3 can significantly enhance trading strategies.
- Including transaction costs makes simulations more realistic.
- Continuous improvement and testing are essential for refining these models.

## Research Paper
This project was inspired by the research paper [Deep Reinforcement Learning for AutomatedStock Trading: An Ensemble Strategy ](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3690996). The paper provides a comprehensive overview of using DRL in financial markets and guided the development of the agents and environment in this project.



##📜 License

**MIT License © 2025**

---
Would you like me to also **add sample Python code (train_agent.py + evaluate_agent.py)** so the README links directly to working code for AAPL, JPM, KO?



