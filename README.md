# Stock-Market-Portfolio-Optimization
This project aims to optimize a stock market portfolio by analyzing historical stock data and identifying the optimal allocation of assets to maximize returns and minimize risk. Using Python, we employ various data analysis and visualization techniques to achieve this goal.

## 📊 Features
Historical Data Retrieval: Fetches data from Yahoo Finance for selected stocks.
Visual Analysis: Provides visualizations for stock prices, moving averages, and trading volumes.
Return Analysis: Analyzes and visualizes daily returns.
Correlation Insights: Examines correlations between different stocks' returns.
Portfolio Optimization: Simulates and identifies optimal portfolio allocations based on risk-return trade-offs.

## 📈 Dataset
The dataset includes:

Date: Date of the record

Ticker: Stock symbol

Adj Close: Adjusted closing price

Close: Closing price

High: Highest price of the day

Low: Lowest price of the day

Open: Opening price

Volume: Number of shares traded

## 🔧 Installation
#### Prerequisites
Ensure you have Python 3.x installed. You will need the following libraries:

pandas

yfinance

matplotlib

seaborn

numpy

Install the required packages using pip:
pip install pandas yfinance matplotlib seaborn numpy

#### Clone the Repository
git clone https://github.com/Bajaj-Apurva/Stock-Market-Portfolio-Optimization.git
cd Stock-Market-Portfolio-Optimization

## 📈 Usage
#### Data Collection
Data is retrieved for the following stock tickers:

Reliance Industries (RELIANCE.NS)

Tata Consultancy Services (TCS.NS)

Infosys (INFY.NS)

HDFC Bank (HDFCBANK.NS)

The dataset spans the past year and is used for subsequent analysis.

#### Data Visualization
Adjusted Close Prices: Plots the adjusted close prices over time.

Moving Averages: Shows 50-day and 200-day moving averages for each stock.

Trading Volume: Visualizes the volume of trades over time.

Daily Returns: Distributes daily returns for each stock.

Correlation Matrix: Analyzes and visualizes correlations between daily returns of stocks.

#### Portfolio Optimization
###### Simulation: Generates 10,000 random portfolios with varying asset allocations.

###### Efficient Frontier: Plots the trade-off between risk (volatility) and return.

###### Optimal Portfolio: Identifies the portfolio with the highest Sharpe Ratio, providing the optimal stock weights.

## 🎯 Results
Efficient Frontier: Displays portfolios' risk-return profiles.

Optimal Allocation: Details the best asset allocation to achieve the highest Sharpe Ratio.

## 📝 Conclusion
This project successfully demonstrates how historical stock data can be used to optimize a stock market portfolio. By leveraging the power of data analysis and visualization, we've identified key insights into stock performance and risk. The analysis of moving averages, daily returns, and portfolio simulations provides a comprehensive view of investment opportunities. The optimal portfolio allocation identified through the simulation process offers a balanced approach to achieving high returns while managing risk. This project lays the groundwork for further exploration into advanced optimization techniques and real-time data integration, providing a robust foundation for informed investment decisions.

## 🚀 Future Work
#### Expand Stocks: Analyze additional stocks or asset classes.

#### Advanced Techniques: Implement Monte Carlo simulations or Machine Learning models.

#### Real-time Integration: Incorporate real-time data for dynamic adjustments.

## 📜 License
This project is licensed under the MIT License. 

## 🙌 Acknowledgements
Yahoo Finance: For providing historical stock data.
Matplotlib and Seaborn: For creating visualizations.

