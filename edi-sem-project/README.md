# EDI semester project
Vishwakarma Institute of Technology, DESH. Academic year 2026–27, semester 1, division CSE-DS B, group 12. Form FF 180.
Source file: [FF_180_Printfinal.pdf](FF_180_Printfinal.pdf)
## Title
AI Adaptive Multisensor (Hardware + Software) Platform for Sensor Integration, Reliability Assessment and Intelligent Data Fusion.
## Project areas
1. Multisensor hardware integration
2. Sensor abstraction and adaptive configuration
3. Multivariate time-series analysis
4. AI-based anomaly and drift detection
5. Sensor reliability and intelligent data fusion
6. Explainable AI and monitoring dashboard
## Team
| Roll no. | Name |
| --- | --- |
| 250 | Rashi Pusdekar |
| 251 | Pranav Rathod |
| 252 | Reva Upare |
| 253 | Rishikesh Tekam |
Internal guide is not filled in on the form.
## Problem statement
Environmental and safety monitoring systems may produce unreliable decisions when abnormal measurements are interpreted without considering sensor health and relationships among sensor readings. The project aims to develop an AI-based multisensor hardware–software platform that analyses single-sensor and multisensor time-series data to distinguish likely genuine environmental changes from sensor-specific faults, gradual drift, sudden spikes, stuck-at values, excessive noise, and other unreliable measurements.
## Aim
Design and develop a modular AI-adaptive multisensor hardware–software platform that integrates supported sensors and uses anomaly detection, time-series analysis, sensor reliability assessment, intelligent data fusion, and explainable AI to improve the interpretation of sensor measurements.
## Objectives
1. Hardware data acquisition for multiple supported sensors.
2. Modular sensor interface so new compatible sensors can be added through drivers and configuration profiles.
3. Preprocessing for timestamp alignment, missing data, noise, unit conversion, and inconsistent sampling.
4. Detect spikes, stuck-at values, excessive noise, and gradual drift.
5. Use relationships among related sensors to separate environmental changes from sensor-specific faults.
6. Time-varying sensor-health score from observable reliability indicators.
7. Sensor fusion for compatible measurements.
8. Explainable alerts.
9. Dashboard for live monitoring, history, sensor health, and maintenance indications.
10. Evaluate under normal conditions, controlled faults, missing data, noise, and unseen tests.
## Stack named in the synopsis
Python, NumPy, Pandas, scikit-learn, Matplotlib or Plotly, Streamlit, optional FastAPI. Acquisition hardware such as an ESP32, plus a computer or Raspberry Pi-class device and two or more sensors.
## Expected outcomes
