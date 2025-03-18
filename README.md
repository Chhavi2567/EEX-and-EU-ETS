# EEX and EU ETS - EUA Price Analysis & Prediction  

## 📌 Overview  
This project analyzes **European Union Allowance (EUA) Futures** historical data, focusing on **price trends, volatility, and trading patterns** in the **EU Emissions Trading System (EU ETS)**.  
The study also implements **LSTM (Long Short-Term Memory) models** for **predicting EUA prices** based on historical data.  

## 📊 About the Dataset  
- **Dataset Name:** European Union Allowance (EUA) Yearly Futures Historical Data  
- **Total Records:** 3,912  
- **Columns:**  
  - `Date` (Trading date)  
  - `Price` (Closing price)  
  - `Open` (Opening price)  
  - `High` (Highest price during the trading session)  
  - `Low` (Lowest price during the trading session)  
  - `Vol.` (Trading volume)  
  - `Change %` (Percentage change in price)  
- **Data Range:** **January 4, 2010 - March 17, 2025**  
- **Missing Values:** 21 (in `Vol.` column)  

## ⚙️ Methodology  
1. **Data Preprocessing:**  
   - Handled missing values.  
   - Converted `Date` column to datetime format.  
   - Normalized price-related columns for better model performance.  

2. **Exploratory Data Analysis (EDA):**  
   - **Trend Analysis:** EUA prices show a rising trend over time.  
   - **Volatility Study:** Significant price fluctuations influenced by policy changes, industrial demand, and economic factors.  
   - **Correlation Analysis:** Price correlations between `Open`, `High`, `Low`, and `Close` values.  

3. **LSTM-Based Time Series Forecasting:**  
   - Implemented **LSTM (Long Short-Term Memory) model** for price prediction.  
   - Used **scaled data** for better convergence.  
   - **Model captured long-term trends** but struggled with short-term fluctuations due to market volatility.  

## ✅ Results  
- **EUA prices have shown an increasing trend**, indicating growing carbon trading value.  
- **LSTM model effectively captured long-term trends**, providing valuable insights for trading strategies.  
- **Short-term fluctuations remain unpredictable**, highlighting the need for hybrid models.  

## 🚀 Conclusion  
- **EU ETS plays a vital role in carbon pricing**, affecting energy and industrial sectors.  
- **LSTM-based forecasting helps identify price trends**, assisting in risk management.  
- **Future improvements:**  
  - Enhance forecast accuracy with **hybrid models** (e.g., **LSTM + ARIMA**).  
  - Incorporate **external factors** like **energy prices and regulatory shifts**.  
  - Apply **advanced deep learning models** for better volatility analysis.  

