# Stock-Market-Anomaly-Detection
Analyze stock market anomalies using Python (Z-Score, Isolation Forest). Includes Jupyter Notebook, Streamlit app, and requirements.txt.
This project focuses on detecting anomalies in the stock price data of GameStop (GME) using multiple machine learning techniques. We implement and compare various anomaly detection methods to identify unusual patterns or events in the stock's behavior, providing insights into market dynamics and potential trading opportunities.

Features
Data retrieval using yfinance
Comprehensive Exploratory Data Analysis (EDA)
Implementation of multiple anomaly detection techniques:
Z-Score
Isolation Forest
DBSCAN (Density-Based Spatial Clustering of Applications with Noise)
LSTM (Long Short-Term Memory) Neural Networks
Autoencoder
Performance comparison of different methods
Interactive Streamlit app for result visualization
Installation
Clone the repository:

git clone https://github.com/yourusername/stock-anomaly-detection.git
cd stock-anomaly-detection
Create a virtual environment (optional but recommended):

python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install required packages:

pip install -r requirements.txt
Usage
Run the Jupyter Notebook for detailed analysis:

jupyter notebook Stock_Anomaly_Detection.ipynb
Launch the Streamlit app:

streamlit run app.py
Project Structure
Stock_Anomaly_Detection.ipynb: Main Jupyter notebook containing the analysis
app.py: Streamlit app for interactive visualization
requirements.txt: List of required Python packages
data/: Directory for storing downloaded stock data (if applicable)
models/: Directory for saving trained models (if applicable)
Methodology
Data Collection: Retrieve GME stock data using yfinance library.
Preprocessing: Clean data, handle missing values, and calculate additional features (e.g., returns, volatility).
Exploratory Data Analysis: Visualize stock price trends, volume, returns, and volatility.
Anomaly Detection Methods:
Z-Score: Identify outliers based on standard deviations from the mean.
Isolation Forest: Detect anomalies using isolation in the feature space.
DBSCAN: Cluster data points and identify outliers.
LSTM: Predict stock prices and flag significant deviations as anomalies.
Autoencoder: Learn normal patterns and detect anomalies based on reconstruction error.
Model Comparison: Evaluate and compare the performance of each method using precision, recall, and F1-score.
Visualization: Create interactive plots to display detected anomalies and compare results.
Results
The project provides insights into:

Periods of unusual activity in GME stock
Effectiveness of different anomaly detection techniques for stock market data
Comparative analysis of model performances
Detailed results and visualizations are available in the Jupyter notebook and Streamlit app.

Streamlit App Features
The Streamlit app offers an interactive interface for exploring the anomaly detection results:

Stock data input and date range selection
Interactive EDA visualizations
Individual plots for each anomaly detection method
Combined visualization of all methods' results
Performance metrics comparison
Summary statistics of detected anomalies
Future Work
Incorporate additional features (e.g., sentiment analysis, market indicators)
Experiment with ensemble methods for improved anomaly detection
Extend the analysis to other stocks or financial instruments
Implement real-time anomaly detection for live stock data
Contributing
Contributions to this project are welcome! Please fork the repository and submit a pull request with your proposed changes.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
yfinance library for providing easy access to Yahoo Finance data
Streamlit for enabling interactive data visualization
The open-source community for the various machine learning libraries used in this project
Contact
For any queries or discussions related to this project, please open an issue in the GitHub repository.
