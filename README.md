# Devices-Price-Classification
## Overview
This repo is part of a job application for the AI Engineer position at maids.cc.
The goal is to develop a price prediction for the devices, and accordingly classify it into four categories; low, medium, high, and very high cost.
The prediction should take into consideration the device specifications which include categorical factors and numerical range factors

## Notebook Contents
* **Setup**: The notebook starts with importing necessary libraries and setting up the environment.
* **Data Loading**: using the data provided by maids.cc
* **Data Analysis**: Applying some analysis to get an insight into the data.
* **Data Preprocessing**: Encoding the data.
* **Model Definition**: A simple neural network model is defined using Keras API.
* **Model Training**: The model is trained using the loaded data.
* **Model Saving**: Once training is complete, the model is saved using Keras' save method.

To run this notebook, follow these steps:

Open the notebook in Google Colab using the provided link.
Run each cell sequentially to execute the code.
Provide necessary input data if required during the execution.
Once training is complete, verify the saved model file in the Colab environment.

## **Dependencies**
* Python 3.x
* TensorFlow
* Keras
* NumPy
* matplotlib
* pandas
