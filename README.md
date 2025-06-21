# Time-series-forecasting

### 🔹 **1. ARIMA / SARIMAX (Baseline Statistical Model)**

* **Purpose**: Benchmark traditional time series model

### 🔹 **2. Facebook Prophet (with regressors)**

* **Purpose**: Seasonality/trend-based forecasting with regressors

### 🔹 **3. XGBoost or LightGBM (ML Model)**

* **Purpose**: Gradient boosting with time-aware feature engineering
* Include lagged prices, rolling means, feed/inflation values as features

### 🔹 **4. LSTM (Deep Learning #1)**

* **Purpose**: Learn time-based dependencies via sequences
* Input sequences of historical values + multivariate exogenous variables

### 🔹 **5. GRU (Deep Learning #2)**

### 🔹 **6. NBEATS (Deep Learning #3)** from **Darts library**

* **Purpose**: Deep learning model with strong performance on small/medium series
* Pretrained versions or light tuning can work well on single-series

### 🔹 **6. Hybrid Model: ARIMA Residuals + LSTM (Deep Learning #3)**
