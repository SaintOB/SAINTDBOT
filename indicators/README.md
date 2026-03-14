# Deriv TradingView Indicator

Saved indicator file:

- `deriv_proper_analysis_indicator.pine`

## How to use (Deriv TradingView)

1. Open Deriv chart (TradingView).
2. Open **Pine Editor**.
3. Paste the script from `deriv_proper_analysis_indicator.pine`.
4. Click **Add to chart**.
5. (Optional) Create alerts from `Deriv Buy Alert` and `Deriv Sell Alert`.

## Signal logic (v2)

- **Trend direction:** fast EMA vs slow EMA.
- **Entry context:** pullback/rejection at fast EMA.
- **Momentum filter:** RSI threshold + RSI slope direction.
- **Trend quality filter:** ADX must be above minimum threshold.
- **Noise control:** cooldown bars between signals.

## Risk guide

- ATR-based suggested stop.
- Configurable risk-reward based target (default `2.0R`).

> This indicator is a decision-support tool, not financial advice. Backtest and optimize settings per symbol/timeframe before live trading.
