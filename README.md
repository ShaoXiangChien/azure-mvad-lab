# 🌌 Azure Multivariate Anomaly Detector Lab: Unraveling the Mysteries of Data

## 🌠 Introduction

Welcome aboard the "Azure Multivariate Anomaly Detector Lab" spaceship! 🚀 Navigate through the vast cosmos of Azure's Multivariate Anomaly Detection (MVAD) capabilities. This lab is your star map, guiding you through hands-on adventures with the SKAB benchmark dataset, and unveiling the secrets of both synchronous and asynchronous APIs.

## 🛸 Prerequisites

- **IDE**: Your trusty spaceship control panel - VSCode with the Jupyter extension or the ever-reliable Anaconda.
- **Environment**: The lifeblood of your journey - Python 3.x.

## 🌌 Dataset: The Cosmic Blueprint

Embark on your quest with the [SKAB benchmark dataset](https://www.kaggle.com/datasets/caesarlupum/benckmark-anomaly-timeseries-skab), a treasure trove of cosmic data:

- **datetime**: The fabric of space-time (YYYY-MM-DD hh:mm:ss).
- **Accelerometer1RMS, Accelerometer2RMS**: Vibrations echoing through the cosmos (Amount of g units).
- **Current**: The electric pulse of the universe (Ampere).
- **Pressure**: The force exerted by celestial bodies (Bar).
- **Temperature**: The warmth of distant stars (The degree Celsius).
- **Thermocouple**: The heat of interstellar fluids (The degree Celsius).
- **Voltage**: The energy surging through the cosmos (Volt).
- **RateRMS**: The flow of time and matter (Liter per minute).
- **anomaly**: The mysteries of the universe (0 or 1).
- **changepoint**: The turning points in our cosmic journey (0 or 1).

## 📜 Notebook Content: Your Galactic Guide

### 1. Data Preparation

- **Loading Data**: Harness the power of pandas and visualize the universe with Plotly.
- **Data Transformation**: Shape the cosmos and divide it into known and unknown realms.
- **Service Client Initialization**: Summon the Azure Anomaly Detector guardian.

### 2. Model Training

- **Data Feed Generation**: Pack, seal, and dispatch data to the Azure Blob Storage galaxy.
- **Training Progress Tracking**: Witness the evolution of your model, star by star.

### 3. Inference

- **Asynchronous Detection**: Unveil anomalies in the blink of a cosmic eye.
- **Synchronous Detection**: Delve deep into real-time anomaly revelations.

### 4. Visualization and Evaluation

- **Result Processing**: Witness the dance of data and stars.
- **Performance Metrics**: Measure the harmony of your cosmic symphony with precision, recall, and the F1 score.

## 🌐 Setup and Configuration

1. Equip your spaceship with essential tools:

```bash
pip install --upgrade pandas azure-ai-anomalydetector
```

2. Ensure your cosmic compass (`mvad_endpoint`, `mvad_key`, `storage_account`) is set and ready.

## 🪐 Languages Used

- [Jupyter Notebook](https://github.com/ShaoXiangChien/azure-mvad-lab/blob/master/MVAD_lab.ipynb): The universe's canvas (99.8%).
- [Python](https://github.com/ShaoXiangChien/azure-mvad-lab/search?l=python): The language of the stars (0.2%).
