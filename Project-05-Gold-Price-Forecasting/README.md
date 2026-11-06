# Gold Price Forecasting

Uses Prophet to model historical USD morning gold prices. The notebook includes an actual-versus-predicted chart, a chronological holdout, and a constant-price baseline.

## Source

- [gold_price_forecasting.py](gold_price_forecasting.py)

## How to explore

[Open the notebook](Gold-Price-Forecasting.ipynb). Install `pandas`, `prophet`, and `matplotlib` to rerun it. The saved run reports a Prophet MAE of $537.28 and a baseline MAE of $208.14 for the 2015–2019 holdout.
