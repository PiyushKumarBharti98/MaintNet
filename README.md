Advanced Predictive Maintenance with Deep Learning and NLP

This project implements an advanced predictive maintenance system for HVAC assets, using an LSTM autoencoder to detect anomalies in time-series sensor data and a natural language query interface to enhance usability. It is designed to align with Xempla’s mission of deploying autonomous decision systems for asset management, supporting real-world applications like fault detection, prioritized alerts, and human-AI collaboration.

Project Overview

The system analyzes building management system (BMS) data (e.g., temperature, pressure, energy consumption) to predict equipment failures early, reducing downtime and improving asset lifespan. Key components include:





LSTM Autoencoder: Detects anomalies by learning temporal patterns in sensor data.



Prioritized Alerts: Categorizes anomalies by severity (Low, Medium, High) for actionable insights.



Maintenance Schedules: Generates daily recommendations for maintenance actions.



FDD Integration: Formats outputs for compatibility with fault detection and diagnostics (FDD) systems.



Natural Language Queries: Allows engineers to ask questions like “How many anomalies were detected yesterday?” using a DistilBERT-based interface.

This project demonstrates proficiency in Python, PyTorch, Hugging Face, and time-series modeling, tailored to Xempla’s focus on applied ML and explainable AI.

Features





Anomaly Detection: Identifies subtle patterns in sensor data using dynamic thresholding.



Explainability: Visualizes anomalies and contributing features (e.g., pressure, temperature) to support human-in-the-loop decision-making.



Actionable Outputs: Generates CSV files for alerts, maintenance schedules, and FDD integration.



Natural Language Interface: Processes queries like “What’s the system status?” or “What are the high-severity anomalies?” using DistilBERT and fuzzy matching.



Edge Compatibility: Lightweight model design suitable for real-world deployment
