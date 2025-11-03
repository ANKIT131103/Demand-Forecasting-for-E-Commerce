# 📦 Demand Forecasting for E-Commerce

<p align="center">
  <img src="assets/accurate-forecasting-helps-us-plan.png" width="100%">
</p>

## 📝 Abstract

In the fast-evolving e-commerce ecosystem, accurate demand forecasting plays a pivotal role in optimizing inventory, minimizing operational costs, and enhancing customer experience. This project applies machine learning and time-series forecasting techniques to predict product demand based on historical sales data and marketing performance indicators, such as clicks and impressions from Google Analytics and social media platforms.

Models developed include ARIMA, SARIMA, SARIMAX, and ML-based algorithms. The workflow covers data cleaning, feature engineering, model training, and performance evaluation using metrics like RMSE and MAPE. By capturing trends, seasonality, and demand variations, this project helps e-commerce businesses avoid stockouts, reduce overstocking, and improve supply chain efficiency—ultimately driving smarter, data-powered decisions.

---

## 🚀 Project Overview

The goal of this project is to build accurate demand-prediction models for e-commerce products using historical sales and digital marketing KPIs.

### 🔄 Workflow

1. **Data Collection**
   - Gathered historical sales data along with marketing KPIs (clicks, impressions, etc.).
2. **Data Preprocessing**
   - Cleaned and standardized data; resolved missing values.
   - Performed EDA to identify seasonal patterns and correlations.
3. **Feature Engineering**
   - Created lagged variables, moving averages, and seasonal indicators.
   - Selected important features based on statistical relevance and domain knowledge.
4. **Model Development**
   - Implemented forecasting models including:
     - **Time-Series Models:** ARIMA, SARIMA
     - **ML Models:** Random Forest, XGBoost
   - Performed hyperparameter tuning for optimal performance.
5. **Model Evaluation**
   - Measured performance using MAE, RMSE, and MAPE.
   - Dataset split: **80% train — 10% validation — 10% test**
6. **Visualization**
   - Plotting demand trends, seasonal behavior, and actual vs. predicted demand comparisons using Matplotlib.
---

## 🧠 Key Features

- ✅ Time-series forecasting for demand planning  
- ✅ Incorporation of marketing KPIs as external features  
- ✅ Automated feature engineering (lags, moving averages, seasonality)  
- ✅ Model evaluation & comparison  
- ✅ Visualizations for trends and forecasting impact  

---

## 🛠️ Technologies & Tools

| Category | Tools |
|--------|-------|
| Language | Python |
| Libraries | Pandas, NumPy, Scikit-Learn, Statsmodels, Matplotlib |
| Notebooks | Jupyter Notebook, Google Colab |

---

## 📊 Results

The models successfully predict future product demand with high accuracy and provide actionable insights for inventory planning. Businesses can use this system to:

- Avoid stockouts
- Reduce surplus inventory
- Improve customer satisfaction
- Allocate resources effectively

---

## 🔗 References

- https://www.ijmerr.com/v4n1/ijmerr_v4n1_10.pdf  
- https://www.kaggle.com/competitions/walmart-recruiting-store-sales-forecasting/data  
- https://www.researchgate.net/publication/354726783_A_Recent_Review_Article_on_Demand_Forecasting  
- https://www.sciencedirect.com/science/article/pii/S2405896318313272  

---

### ⭐ If you find this project helpful, consider starring the repo!
