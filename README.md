# aapl-stock-prediction
Predictive model for Apple stock using Machine Learning and Linear Regression.

## 📂 Project Overview

- Predicts next-day **closing price** of AAPL stock using over **60 technical indicators** and market features.
- Implements a **Linear Regression** model with strong accuracy and evaluation.
- Uses **chronological train/validation/test split** to simulate real-world forecasting.
- Evaluates model performance using **R²**, **MAPE**, **RMSE**, **MAE**, and more.
- Visualizes actual vs. predicted prices using **Matplotlib**, **Seaborn**, Numpy and Pandas.

------------------------------------------------------------------------------------------
## 🔧 Technologies Used

- **Python** (pandas, numpy, matplotlib, seaborn)
- **Jupyter Notebook**
- **scikit-learn** (LinearRegression, train_test_split, metrics)
- Time-series feature engineering
- Git/GitHub for version control

------------------------------------------------------------------------------------------
## 📁 Dataset

- Source: `[AAPL.csv](https://github.com/user-attachments/files/22682698/AAPL.csv)`
- Contains **3732 rows**, covering AAPL stock from **2005 to 2020**.
- Includes over 60 features: technical indicators (RSI, MACD, EMA), market indices (S&P500, DJIA, QQQ), lag features, and more.

------------------------------------------------------------------------------------------
## 🧠 Machine Learning Approach

- **Target Variable:** `Close_forecast` (next-day close price)
- **Features:** 60+ stock indicators and lagged variables
- **Model:** Linear Regression
- **Split:**
  - Training: 88%
  - Validation: 10%
  - Testing: 2%

-------------------------------------------------------------------------------------------
## 📈 Model Performance

| Metric         | Training Set | Validation Set | Test Set  |
|----------------|--------------|----------------|-----------|
| R² Score       | 0.999        | 0.99           | 0.96      |
| MAPE (%)       | 1.45         | 1.68           | 1.77      |
| RMSE           | 1.22         | 5.91           | 8.90      |
| MAE            | 0.76         | 3.75           | 6.50      |

------------------------------------------------------------------------------------------
