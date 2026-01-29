This project predicts Dogecoin (DOGE-USD) closing prices using a State-Space Time Series model (SARIMAX) with engineered market features to improve forecasting accuracy.

Historical price data is preprocessed by handling missing values, setting a time-based index, and performing correlation analysis. Key volatility and liquidity-based features such as gap, High/Low ratio (a), and volume-weighted range (b) are created to better capture market behavior.

A SARIMAX model with order (2,1,1) is trained using both price history and exogenous variables (Volume, gap, a, b). The model is evaluated on recent data to generate short-term forecasts, and actual vs predicted prices are visualized to assess performance.

This approach improves accuracy by combining time-series dynamics with market-driven features, making it suitable for short-term cryptocurrency price prediction.
