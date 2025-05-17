# 🧠 NSFET Performance Prediction using ML, CNN, and SNN

This project presents a benchmarking study of **Machine Learning (ML)**, **Convolutional Neural Networks (CNN)**, and **Spiking Neural Networks (SNN)** models for predicting the performance of **multi-stacked Nanosheet Field-Effect Transistors (NSFETs)**.

## 📌 Overview

With the rise of nanosheet FETs as the future of semiconductor technology, this work explores how modern data-driven approaches can:

* Reduce dependence on complex TCAD simulations,
* Accurately predict electrical characteristics, and
* Enable energy-efficient modeling.

## 📊 Models Used

* **Random Forest Regression (RFR)**
* **Convolutional Neural Networks (CNN)**
* **Spiking Neural Networks (SNN)**

Each model is trained on a **custom dataset** generated using **Sentaurus TCAD** simulations by varying device parameters like width, height, and length.

## 🔍 Key Metrics Predicted

* Threshold Voltage (Vth)
* Transconductance (gm)
* Saturation Current (IDSAT)

## ⚡ Key Findings

* All models achieved **R² scores close to 99%**.
* **SNNs** stood out for their **energy efficiency** due to their event-driven design.
* This work sets a **benchmark** for applying ML to nanoelectronic device modeling.

## 📂 Project Structure

```
.
├── data/               # TCAD-simulated dataset
├── models/
│   ├── rfr_model.py    # Random Forest implementation
│   ├── cnn_model.py    # CNN implementation
│   └── snn_model.py    # SNN implementation
├── notebooks/          # Jupyter notebooks for training and evaluation
├── results/            # Evaluation metrics, plots, and comparisons
└── README.md           # Project overview
```

## 🧪 Requirements

* Python 3.x
* scikit-learn
* TensorFlow / PyTorch (depending on CNN/SNN implementation)
* NumPy, Matplotlib, Pandas

## 📄 Paper

This work was accepted at **IEEE ICMLAS 2024**.
**Title:** *A Benchmarking Investigation of ML, CNN, and SNN models for Optimization and Prediction of Performance Metrics of Multi-Stacked NSFETs*.
