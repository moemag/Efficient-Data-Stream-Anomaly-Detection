# Efficient-Data-Stream-Anomaly-Detection
  ## **SH-ESD (Seasonal Hybrid ESD)**

SH-ESD is a statistical method for detecting anomalies in time series data. It works by first decomposing the time series into its seasonal, trend, and residual components. Then, it applies the Generalized ESD test to the residual component to identify potential anomalies. The "hybrid" aspect refers to its ability to handle both seasonal and non-seasonal data.

**Effectiveness:** SH-ESD is effective in detecting anomalies that deviate significantly from the expected pattern. It's particularly good at identifying global anomalies, which are points that are outliers compared to the entire dataset. Due to its reliance on statistical properties, SH-ESD is computationally efficient, as demonstrated in the execution time comparison you included.

  ## **Why SH-ESD is a suitable choice:**

**Time Series Focus:** The code simulates time series data with seasonality and noise, which SH-ESD is designed to handle.

**Computational Efficiency:** SH-ESD is relatively fast compared to LOF and Robust Covariance, making it suitable for real-time anomaly detection in streaming data.

**Simplicity:** It's relatively easy to understand and implement compared to more complex machine learning-based approaches.
