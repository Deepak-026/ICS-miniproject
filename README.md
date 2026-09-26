# Secure Industrial Control System

ESP32-based Industrial Control System (ICS) security project integrating traffic monitoring, secure communication, honeypot-based detection, IDS/IPS, and ML-based threat detection.

## Features

- ESP32-based traffic light control
- YOLOv8 vehicle detection
- MQTT communication with TLS/SSL
- Honeypot for detecting unauthorized access
- Snort/Suricata for network monitoring
- Classical and Hybrid ML-based IDS
- Post-Quantum Cryptography (PQC)
- Wireshark-based packet analysis
- Automatic blocking of unauthorized IPs

## Technologies

- ESP32
- Python
- YOLOv8
- OpenCV
- PyTorch
- Flask
- MQTT / Mosquitto
- Snort / Suricata
- Wireshark
- XGBoost
- Random Forest
- LightGBM
- TLS/SSL
- Post-Quantum Cryptography

## System Workflow

```text
Traffic Detection
       ↓
ESP32 Traffic Control
       ↓
Secure MQTT Communication
       ↓
Network Monitoring
       ↓
Honeypot + IDS/IPS
       ↓
ML-Based Threat Detection
       ↓
Block Unauthorized IP
