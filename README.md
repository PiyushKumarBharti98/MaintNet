# 🔧 **Advanced Predictive Maintenance with Deep Learning**

This project implements an **advanced predictive maintenance system** for **HVAC assets**, combining **LSTM Autoencoders** for anomaly detection in **time-series sensor data** with a **Natural Language Query Interface** for seamless interaction. The system supports **real-world applications** like fault detection, **prioritized alerts**, and **human-AI collaboration**.

---

## 📌 **Project Overview**

The system analyzes **Building Management System (BMS)** data — such as **temperature**, **pressure**, and **energy consumption** — to **predict equipment failures** before they occur. This reduces downtime and extends asset lifespan.

### 🔑 **Key Components**

- **LSTM Autoencoder**  
  Learns temporal dependencies in sensor data to detect **subtle anomalies**.

- **Prioritized Alerts**  
  Flags anomalies based on **severity levels**: **Low**, **Medium**, and **High**, ensuring actionable insights for operators.

- **Maintenance Schedules**  
  Produces **daily maintenance recommendations** based on anomaly history.

- **FDD Integration**  
  Formats output to integrate smoothly with existing **Fault Detection and Diagnostics (FDD)** systems.

---

## 🚀 **Features**

### ✅ **Anomaly Detection**
Detects hidden faults by capturing **temporal patterns** using **LSTM Autoencoders** and applies **dynamic thresholding** for accurate identification.

### ✅ **Explainability**
Provides **visual explanations** of anomaly causes — such as **temperature spikes** or **pressure drops** — to aid in **human-in-the-loop decisions**.

### ✅ **Actionable Outputs**
Automatically generates structured reports:
- **CSV files** for anomaly alerts
- **Maintenance schedules**
- **FDD-compatible logs**
