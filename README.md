# Week 2 Data Wrangling & Hygiene

Completed Week 2 data wrangling and hygiene assignment for Ioannis Tzalas, continuing the Week 1 five-asset universe (SPY, EUR/USD, BTC, GLD, ETH).

The executed notebook covers the extended hygiene audit (six-point audit, stale-price streaks, weekday coverage and real-volume anomalies), the ETH masking tournament with 20 imputation estimators scored on MAE, RMSE, sMAPE and variance ratio, the weekend question and look-ahead bias, the MNAR and flash-crash laboratories, KNN and MICE imputation with a cost ledger, and the Cleaning Agent's Rulebook v1.0 with a negative control on the raw panel.

Price data is embedded in the notebook, so it runs offline. `W2_cleaned_panel.csv` is the cleaned 2,218-row intersection panel; `W2_cleaned_panel.parquet` is the Snappy-compressed copy from the Parquet round-trip bonus.
