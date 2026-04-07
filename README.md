#  ESP32-Based WiFi Exploration and Security Analysis Tool

## Overview

The **ESP32 WiFi Exploration and Security Analysis Tool** is a portable, cost-effective solution designed for analyzing wireless networks and understanding security vulnerabilities. It provides real-time WiFi monitoring and control through a web-based interface.

---

## Objective

To develop an ESP32-based system that:

* Scans nearby WiFi networks
* Analyzes security parameters
* Helps users learn wireless security concepts ethically

---

## Features

*  **AP Scanner** – Detects and lists nearby WiFi networks
*  **Beacon Spammer** – Generates multiple fake access points (for testing)
*  **WiFi Sniffer** – Captures network packets (PCAP supported)
*  **Deauthentication Detection & Testing**
*  **Web-Based Control Panel** (ESP32 AP mode)
*  **NAT Routing Support**
*  **SD Card Storage for Data Logging**
*  **Real-Time Display using TFT Screen**

---

##  Hardware Requirements

* ESP32-WROOM-32 Dev Board
* 1.44" TFT Display (ST7735)
* SD Card Module
* Push Buttons

---

##  Software & Technologies

* C / C++
* Espressif IDF Framework
* lwIP (NAT-enabled)
* Embedded Web Server

---

##  Working

1. ESP32 scans nearby WiFi networks
2. Data is processed and displayed in real-time
3. Users access the web interface via ESP32 AP mode
4. Advanced features like sniffing and routing can be controlled through the portal

---

##  Input & Output

* **Input:** Wireless network signals
* **Output:**

  * Real-time WiFi analysis
  * Security insights
  * Packet capture files (PCAP)

---

##  Testing & Validation

* Functional testing of modules
* Security analysis validation
* Ethical usage verification

---

##  Disclaimer

This project is intended **only for educational and ethical research purposes**. Unauthorized use on networks without permission is strictly prohibited.

---

##  References

* ESP32 Technical Reference Manual – Espressif
* IEEE 802.11 Wireless Standard
* lwIP NAT Implementation (Martin Ger)


## Future Improvements

* Mobile App Integration
* Advanced Threat Detection using ML
* Cloud-based Monitoring Dashboard


