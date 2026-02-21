# Trader-Sentiment-Analysis

Trader Performance vs Market Sentiment
Objective

This project analyzes how Bitcoin market sentiment (Fear vs Greed) relates to trader behavior and performance on Hyperliquid. The goal is to identify regime-dependent behavioral patterns and derive actionable trading insights.

Methodology

* Aggregated trade-level data to daily metrics (PnL, win rate, trade count, trade size, long ratio)

* Aligned daily trader activity with sentiment classification

* Collapsed sentiment into binary Fear vs Greed regimes

* Segmented traders into behavioral archetypes:

  * High-frequency traders

  * High-volatility traders

  * Consistent traders

* Compared segment-level performance across regimes

* Conducted exploratory next-day volatility prediction (bonus)

Key Insights

1. Fear regimes amplify volatility and trading activity.
Trade frequency increases significantly during Fear periods, and PnL dispersion rises sharply. Gains are driven more by volatility than by improved win rates.

2. Greed regimes favor structured and systematic traders.
High-frequency and consistent traders demonstrate improved performance and stability in Greed environments.

3. Trader archetypes respond asymmetrically to sentiment.
Volatility-driven traders benefit most during Fear, while systematic traders perform better during Greed.

Strategy Recommendations

* Allocate capital dynamically based on sentiment regime.

* Favor volatility-driven strategies during Fear, with controlled risk exposure.

* Increase allocation to systematic/high-frequency strategies during Greed.

* Introduce trade frequency controls during Fear to mitigate overtrading risk.

Bonus: Volatility Prediction

A logistic regression model was trained to predict next-day volatility using sentiment and behavioral features. While overall accuracy was high, class imbalance limited detection of low-volatility days. However, feature analysis suggests that win rate and sentiment contribute meaningfully to volatility forecasting.
