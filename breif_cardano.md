# Cryptocurrency Comparison & Price Prediction — Project Summary

We built a Python-based **Cryptocurrency Comparison and Price Prediction** project using historical data from Yahoo Finance.

### Cryptocurrencies Analysed

1. Solana (SOL)
2. Cardano (ADA)

### What We Did

| Area             | Analysis Performed                                                           |
| ---------------- | ---------------------------------------------------------------------------- |
| Data Collection  | Downloaded approximately five years of cryptocurrency data using `yfinance`. |
| Data Inspection  | Checked dataset shape, columns, missing values, and statistics.              |
| Data Cleaning    | Checked missing values and prepared the datasets for analysis.               |
| Price Analysis   | Compared the closing prices of Solana and Cardano.                           |
| Returns Analysis | Calculated daily percentage returns.                                         |
| Volatility       | Measured price fluctuations using standard deviation.                        |
| Correlation      | Studied the relationship between the daily returns of both cryptocurrencies. |
| Trading Volume   | Visualized and compared trading volumes.                                     |
| Price Comparison | Compared normalized prices starting from a common value of 100.              |
| Machine Learning | Built separate Linear Regression models for Solana and Cardano.              |
| Model Evaluation | Evaluated predictions using MAE, RMSE, and R² Score.                         |
| Price Prediction | Estimated the next day's closing price for both cryptocurrencies.            |
| Final Output     | Saved cleaned datasets and prediction results as CSV files.                  |

### Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* yfinance
* Scikit-learn
* VS Code / Jupyter Notebook

### Final Output

We created comparison charts, statistical summaries, return and volatility analyses, correlation visualizations, and machine learning prediction results for Solana and Cardano. We also saved the important results into CSV files.

### Conclusion

This project helped us understand cryptocurrency price movements and compare Solana and Cardano using Python. We used data visualization and statistical analysis to study their performance and Linear Regression to estimate future closing prices. However, cryptocurrency prices are highly unpredictable, so the predictions are estimates rather than guaranteed future prices.
