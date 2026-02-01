# Predict-Future-Stock-Prices

**1: Overview**

This project predicts the **next day’s closing stock price** using historical market data from Yahoo Finance.  
It uses a **Linear Regression** model trained on features like Open, High, Low, and Volume.

**2: Dataset**
- *Source:* Yahoo Finance (`yfinance` Python library)  
- *Stock Used:* Apple Inc. (AAPL)  
- *Columns:* Open, High, Low, Close, Volume  

**3: Features and Target**
- *Features:* Open, High, Low, Volume  
- *Target:* Next day’s Close price (`Target_Close_Next_Day`)  

**4: Tools & Libraries**
- Python  
- pandas, numpy  
- yfinance  
- matplotlib  
- scikit-learn  

**5: Workflow**
1. Download historical stock data using `yfinance`  
2. Preprocess data and create target variable  
3. Split data into training and testing sets  
4. Train a Linear Regression model  
5. Evaluate using MAE and RMSE  
6. Plot Actual vs Predicted closing prices  

**6: Result**
- Model predicts short-term stock price trends  
- Visualization shows how close predictions are to actual prices  

# Conclusion
This project demonstrates a complete end-to-end Machine Learning workflow for short-term stock price prediction.  
Using historical data from Yahoo Finance, a Linear Regression model was trained to predict the next day’s closing price.  
The model’s performance was evaluated using MAE and RMSE, and results were visualized to show how closely predictions match actual prices.  
This project highlights how market features like Open, High, Low, and Volume can be used for practical short-term stock forecasting.
