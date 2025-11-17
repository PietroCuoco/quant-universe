# QT2 — Mean Reversion Statistical Arbitrage (Equities/ETFs)

## Objective
Design and backtest a market-neutral mean reversion strategy on equity/ETF pairs:
- Identify cointegrated or highly correlated pairs.
- Construct z-score based mean-reversion signals.
- Implement a realistic backtest with transaction costs and slippage.
- Evaluate performance, drawdowns, and robustness.

## Structure
- `data/`: raw and cleaned OHLCV data.
- `notebooks/`: exploratory analysis and experiment notebooks.
- `src/`: implementation of signals, backtest and metrics.
- `tests/`: unit tests for core functions.
- `report/`: LaTeX report and final figures.
