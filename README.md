## Portfolio Optimization with Reinforcement Learning

This project demonstrates portfolio optimization (trading) of the Dow Jones 30 stocks using Reinforcement Learning (RL) algorithms. We leverage the FinRL library and Stable-Baselines3 to build, train, and backtest two popular RL agents: Advantage Actor-Critic (A2C) and Proximal Policy Optimization (PPO).

### 📂 Project Structure

```
├── Portfolio (2).ipynb    # Jupyter Notebook containing the full implementation
└── README.md              # This file
```

### 🔑 Key Features

- **Data Acquisition:** Download historical price data for Dow Jones 30 tickers using `YahooDownloader`.
- **Feature Engineering:** Compute technical indicators and prepare data splits for training and testing.
- **Environment Setup:** Define a portfolio allocation environment (`StockPortfolioEnv`) for RL training.
- **Agent Training:** Train two RL agents (A2C and PPO) using `DRLAgent` from FinRL.
- **Backtesting:** Evaluate trained agents with backtesting statistics and performance plots (`backtest_stats`, `backtest_plot`).


### 📊 Results

- **A2C Backtesting:** Compare daily returns and cumulative performance against a baseline.
- **PPO Backtesting:** Similarly evaluate PPO agent performance.

Refer to the notebook sections **"Trading avec A2C"** and **"Trading avec PPO"** for detailed explanations and plots.

### 📋 Requirements

- Python 3.7+
- `condacolab`, `pandas`, `numpy`, `matplotlib`, `yfinance`
- `finrl` (Official [FinRL-Library](https://github.com/AI4Finance-Foundation/FinRL))
- `stable-baselines3`

You can install them via:

```bash
pip install pandas numpy matplotlib yfinance finrl stable-baselines3
```

### 🤝 Contributing

Feel free to open issues or submit pull requests to improve this project. Contributions are welcome!

---

*Developed by Houssem Aridhi*

