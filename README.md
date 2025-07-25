This project implements a simple yet effective time series anomaly detection model to identify abnormal CPU usage patterns using the ARIMA (AutoRegressive Integrated Moving Average) algorithm.

📌 Overview
This notebook uses a time-stamped CPU usage dataset and applies the following steps:

Data Preprocessing:

Reads CPU usage data from a CSV file.

Parses timestamps and sets them as the index.

Sorts the data chronologically.

Modeling:

Fits an ARIMA(1,1,1) model on the CPU usage data.

Generates predictions using the trained model.

Anomaly Detection:

Computes residuals (actual - predicted).

Flags anomalies where residuals exceed 3 standard deviations.

Visualization:

Plots the CPU usage time series.

Highlights detected anomalies in red.

📂 Files
cpu-test-a.csv – Sample dataset with CPU usage logs.

cpu_arima_anomaly_detection.ipynb – Jupyter notebook with code and results.

🛠️ Technologies Used
Python

Pandas

NumPy

Statsmodels (ARIMA)

Matplotlib

Google Colab

📊 Output Preview
A plot showing CPU usage over time.

Red dots indicating detected anomalies (unexpected spikes or drops).

✅ Use Cases
Server & infrastructure monitoring

Resource usage analysis

Detecting performance bottlenecks

Predictive maintenance

🚀 Future Work
Experimenting with SARIMA, Prophet, or LSTM models.

Adding real-time anomaly alerts.

Deploying the model with a dashboard using Streamlit or Flask.

📥 How to Use
Upload your time series data (CSV with datetime and cpu columns).

Run the notebook in Google Colab.

Analyze the visual outputs to identify CPU anomalies.

🙌 Author
Akash Mohanraj
Data & AI Enthusiast | Exploring Time Series & Anomaly Detection


📢 License
This project is open source and available under the MIT License.

