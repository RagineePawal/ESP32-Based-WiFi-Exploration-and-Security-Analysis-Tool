ESP32-Based WiFi Exploration and Security Analysis Tool
Overview

This project is a portable and cost-effective ESP32-based tool designed to analyze WiFi networks and study security vulnerabilities. It provides real-time monitoring and a web-based interface for user interaction.

Objective

To scan nearby WiFi networks, analyze their security parameters, and help users understand wireless security in an ethical manner.

Features
Access Point (AP) Scanning
WiFi Traffic Sniffing (PCAP support)
Beacon Spamming (testing purpose)
Deauthentication Detection and Testing
Web-Based Control Interface (ESP32 AP mode)
NAT Routing
SD Card Data Storage
Real-time display using TFT
Hardware Requirements
ESP32-WROOM-32
TFT Display (ST7735)
SD Card Module
Push Buttons
Software Used
C / C++
Espressif IDF Framework
lwIP Stack
Embedded Web Server
Working

The ESP32 scans nearby networks, processes the data, and displays results in real time. Users can control features and access data through a web interface hosted on the ESP32.

Input and Output
Input: Wireless network signals
Output: Network analysis, security insights, packet capture data
Disclaimer

This project is intended only for educational and ethical purposes. Unauthorized use is not allowed.
