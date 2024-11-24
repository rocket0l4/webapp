# webapp

# Crypto Trading Dashboard with Backtesting and Visualization

This Streamlit-based application provides an interactive dashboard for analyzing cryptocurrency price data, implementing trading strategies, and visualizing results. It includes features for uploading custom datasets, applying filters, and evaluating performance metrics using backtesting. The application is designed to help traders and analysts make data-driven decisions.

---

## Features

- **Upload Custom Data**: Upload your CSV file with columns: `Date`, `Open`, `High`, `Low`, and `Close`.
- **Price Filtering**: Filter data by specifying a minimum and maximum price range.
- **Moving Average Strategy**: Generate buy/sell signals based on moving average crossover strategies.
- **Backtesting**: Simulate trading strategies and calculate:
  - Total Return
  - Maximum Drawdown
  - Sharpe Ratio
- **Interactive Charts**:
  - Line chart with buy/sell signals
  - Portfolio equity curve
  - Candlestick chart
- **Default Data**: Use pre-loaded data (`data.pkl`) as a fallback for convenience.

---

## How to Run

### Prerequisites
1. **Python 3.9+** installed on your machine.
2. Install the required Python packages using `requirements.txt`.

### Setup Instructions
1. Clone this repository:
   ```bash
   git clone <repository_url>
   cd <repository_folder>

2. Install the dependencies:
   ```bash
   pip install -r requirements.txt

3. Run the application:
   ```bash
   streamlit run app.py 
  



