# Stock Market Anomaly Detection: GME Analysis


## Project Structure

- `Stock_Anomaly_Detection.ipynb`: Main Jupyter notebook containing the analysis
- `app.py`: Streamlit app for interactive visualization
- `requirements.txt`: List of required Python packages
- `data/`: Directory for storing downloaded stock data (if applicable)
- `models/`: Directory for saving trained models (if applicable)

## Methodology

1. **Data Collection**: Retrieve GME stock data using yfinance library.
2. **Preprocessing**: Clean data, handle missing values, and calculate additional features (e.g., returns, volatility).
3. **Exploratory Data Analysis**: Visualize stock price trends, volume, returns, and volatility.
4. **Anomaly Detection Methods**:
   - Z-Score: Identify outliers based on standard deviations from the mean.
   - Isolation Forest: Detect anomalies using isolation in the feature space.
   - DBSCAN: Cluster data points and identify outliers.
   - LSTM: Predict stock prices and flag significant deviations as anomalies.
   - Autoencoder: Learn normal patterns and detect anomalies based on reconstruction error.
5. **Model Comparison**: Evaluate and compare the performance of each method using precision, recall, and F1-score.
6. **Visualization**: Create interactive plots to display detected anomalies and compare results.

## Results

The project provides insights into:
- Periods of unusual activity in GME stock
- Effectiveness of different anomaly detection techniques for stock market data
- Comparative analysis of model performances

Detailed results and visualizations are available in the Jupyter notebook and Streamlit app.
