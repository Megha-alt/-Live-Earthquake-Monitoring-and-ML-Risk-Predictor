# -Live-Earthquake-Monitoring-and-ML-Risk-Predictor
A Machine Learning model using RandomForestRegressor to analyze live recent earthquake data, detect risk spikes, and predict risk scores.
This project focuses on monitoring recent real-time earthquake activity and estimating the risk level based on seismic parameters.
Using live earthquake data, the model analyzes magnitude and depth, detects whether activity is normal or spiked, and predicts a continuous risk score.
It also visualizes risk trends and magnitude–risk patterns to make seismic behavior easy to understand.

# 🔎 Project Summary

The purpose of this project is to track recent live seismic readings and interpret the risk associated with them.
The model uses:

Live magnitude data

Live depth readings

Recent seismic fluctuations

- Based on this, the system generates:

A risk score

Spike vs Normal activity status

A risk-rate trend graph

This helps in understanding how risky the current seismic environment is in real time.


#  Key Features

Live Seismic Data Monitoring

Risk Score Prediction using RandomForestRegressor

Spike Detection for abnormal seismic rises

Risk Trend Visualization for recent activity

Magnitude–Risk Pattern Analysis to explain behavior

Clean and simple ML pipeline



#  Technologies Used

Python

RandomForestRegressor (Scikit-Learn)

Pandas & NumPy

Matplotlib (for visualizations)

Live Earthquake Dataset API / Recent CSV Feed (whichever you used)



#  Workflowm 

Fetch live recent earthquake data (magnitude, depth, etc.)

Clean and preprocess the incoming seismic values

Use RandomForestRegressor to predict a risk score

Compare the result with recent values to detect spikes


