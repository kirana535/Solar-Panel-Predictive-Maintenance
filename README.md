# IoT-Enabled Predictive Maintenance of Solar Panels

An IoT and Machine Learning based system for real-time monitoring,
power-performance prediction, and anomaly detection in solar panels.

## Overview

This project combines IoT sensors, ESP32, cloud connectivity, and
Machine Learning to monitor solar-panel parameters and identify
abnormal operating conditions.

The system collects parameters such as irradiance, voltage, current,
temperature, and power, sends the data to the cloud, and applies
Machine Learning models for performance prediction and anomaly detection.

## Objectives

- Monitor solar-panel parameters in real time
- Predict expected power output
- Detect abnormal operating conditions
- Reduce manual inspection
- Support predictive maintenance
- Provide cloud-based monitoring

## System Architecture

Solar Panel → Sensors → ESP32 → Wi-Fi → Firebase → ML Models
→ Prediction & Anomaly Detection → Dashboard

## Hardware

- ESP32
- Solar Panel
- Temperature Sensor
- LDR / Irradiance Sensor
- Voltage Sensor
- Current Sensor

## Technologies

- Python
- ESP32
- Machine Learning
- Firebase
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- SHAP

## Machine Learning Models

### Random Forest
Used for fault classification and handling nonlinear sensor data.

### Gradient Boosting
Used for power-performance prediction.

### Isolation Forest
Used for detecting abnormal operating conditions without requiring
labelled anomaly data.

## Input Parameters

| Parameter | Unit |
| Irradiance | W/m² |
| Voltage | V |
| Current | A |
| Temperature | °C |
| Power Output | W |

## Results

The project evaluated Random Forest, Gradient Boosting, and Isolation
Forest models for solar-panel performance analysis and anomaly detection.

Reported results from the project:

- Gradient Boosting: 96.1%
- Random Forest: 94.6%
- Isolation Forest: 92.1%

## Analysis

The project includes:

- Actual vs Expected Power
- Irradiance vs Power
- Confusion Matrix
- ROC Curve
- SHAP Feature Importance

## Key Features

- Real-time sensor monitoring
- Solar power prediction
- Machine Learning based anomaly detection
- Cloud data storage
- Dashboard-based monitoring
- Explainable ML using SHAP

## Future Scope

- Camera-based fault detection
- TinyML implementation on ESP32
- Large-scale solar-farm deployment
- Automated fault alerts
- Advanced degradation prediction

