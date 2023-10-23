# Azure Multivariate Anomaly Detector Lab

## Introduction

The "Azure Multivariate Anomaly Detector Lab" is a comprehensive guide to leveraging Azure's Multivariate Anomaly Detection (MVAD) capabilities. This lab provides hands-on experience with training a multivariate anomaly detection model using the SKAB benchmark dataset and making inferences using both synchronous and asynchronous APIs.

## Prerequisites

- **IDE**: Either VSCode with the Jupyter extension installed or Anaconda.
- **Environment**: Python 3.x

## Dataset

The lab uses the [SKAB benchmark dataset](https://www.kaggle.com/datasets/caesarlupum/benckmark-anomaly-timeseries-skab), which contains the following columns:

- datetime: Dates and times of the moment when the value is written to the database (YYYY-MM-DD hh:mm:ss)
- Accelerometer1RMS, Accelerometer2RMS: Vibration acceleration (Amount of g units)
- Current: Amperage on the electric motor (Ampere)
- Pressure: Pressure in the loop after the water pump (Bar)
- Temperature: Temperature of the engine body (The degree Celsius)
- Thermocouple: Temperature of the fluid in the circulation loop (The degree Celsius)
- Voltage: Voltage on the electric motor (Volt)
- RateRMS: Circulation flow rate of the fluid inside the loop (Liter per minute)
- anomaly: Indicates if the point is anomalous (0 or 1)
- changepoint: Indicates if the point is a changepoint for collective anomalies (0 or 1)


## Notebook Content

### 1. Data Preparation

- **Loading Data**: The data is loaded using pandas and visualized using Plotly.
- **Data Transformation**: The data is transformed and split into training and test sets.
- **Service Client Initialization**: The Azure Anomaly Detector client is initialized.

### 2. Model Training

- **Data Feed Generation**: The data is packed, zipped, and uploaded to Azure Blob Storage.
- **Training Progress Tracking**: The training progress of the model can be tracked and visualized.

### 3. Inference

- **Asynchronous Detection**: The notebook demonstrates how to perform anomaly detection asynchronously.
- **Synchronous Detection**: The notebook also showcases synchronous anomaly detection.

### 4. Visualization and Evaluation

- **Result Processing**: The results from the anomaly detection are processed and visualized.
- **Performance Metrics**: Precision, recall, and F1 score are calculated to evaluate the model's performance.

## Setup and Configuration

1. Install the required Python packages:

```bash
pip install --upgrade pandas azure-ai-anomalydetector
```

2. Ensure you have the necessary credentials and configurations in place, such as the `mvad_endpoint`, `mvad_key`, and `storage_account`.

## Languages Used

- [Jupyter Notebook](https://github.com/ShaoXiangChien/azure-mvad-lab/blob/master/MVAD_lab.ipynb) (99.8%)
- [Python](https://github.com/ShaoXiangChien/azure-mvad-lab/search?l=python) (0.2%)
