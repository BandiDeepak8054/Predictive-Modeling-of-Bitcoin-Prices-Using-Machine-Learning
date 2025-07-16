#  Predictive Modeling of Bitcoin Prices Using Machine Learning

## Overview
This project focuses on building robust machine learning models to predict Bitcoin prices using historical price data and sentiment analysis. The goal is to forecast the closing price of Bitcoin, helping investors and analysts make informed decisions in the volatile cryptocurrency market.

## Objectives
- Analyze historical Bitcoin price data
- Build predictive models using machine learning algorithms
- Integrate sentiment analysis from news and social media
- Compare model performance using statistical evaluation metrics

## Dataset
- **Source:** Historical BTC-USD data was collected from [Yahoo Finance](https://finance.yahoo.com/).
- **Fields include:**
  - Date
  - Open, High, Low, Close
  - Volume
  - Sentiment score

## Technologies & Libraries
- Python 3
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Random Forest Regressor
- Matplotlib, Seaborn
- Natural Language Toolkit (NLTK) or TextBlob (for sentiment)
- Jupyter Notebook

## Machine Learning Models
- **XGBoost Regressor**
- **Random Forest Regressor**
- **Linear Regression (Baseline)**

These models were selected and tuned to find the best fit for Bitcoin's volatile pricing trends.

## Data Preprocessing
- Checked for and handled missing values
- Created lag features and moving averages
- Normalized/standardized data
- Conducted exploratory data analysis (EDA)
- Visualized trends, outliers, and volume-price relationships

## Sentiment Analysis
- Collected news headlines or Reddit/Twitter content (can be replaced with dummy sentiment data)
- Performed sentiment scoring using TextBlob or VADER
- Merged sentiment scores with market data based on date

## Evaluation Metrics
- Mean Absolute Error (MAE)
- Root Mean Square Error (RMSE)
- R² Score

## Results
- XGBoost and Random Forest models outperformed others with an R² score up to **0.98**.
- Sentiment integration improved the predictive performance slightly by capturing market psychology.

## Key Takeaways
- Historical price trends and sentiment can both influence Bitcoin forecasting.
- XGBoost showed strong performance in handling non-linear patterns and volatility.
- This project demonstrates the practical use of data science in financial time series prediction.
