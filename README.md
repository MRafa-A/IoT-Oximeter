# Digital Pulse Oximeter with IoT Monitoring

![Project Banner](docs/images/system_diagram.png)

A comprehensive IoT pulse oximeter system built with ESP8266 NodeMCU and MAX30100/MAX30102 sensors to measure heart rate (BPM) and blood oxygen saturation (SpO₂). It supports three interface options: an I2C LCD display, the Blynk mobile app for cloud monitoring, and a built-in web server dashboard over Wi-Fi.

## Table of Content

* [Features](#features)
* [What is IoT?](#what-is-iot)
* [Hardware Requirements](#hardware-requirements)
* [Software Requirements](#software-requirements)
* [Getting Started](#getting-started)
* [Three Implementation Options](#three-implementation-options)
* [Installation Guide](#installation-guide)
* [Troubleshooting](#troubleshooting)
* [Contributing](#contributing)
* [License](#license)

## Features

* Real-time Monitoring: Continuous heart rate and SpO2 measurement
* LCD Display: 16x2 12C LCD for local data visualization
* loT Connectivity: Remote monitoring via Blynk mobile app
* Cloud Integration: Data logging and historical tracking
* Beat Detection: Visual/audio feedback on heartbeat detection
* Automatic Calibration: Self-calibrating sensor readings
* Low Power: Optimized for extended operation

## What is IoT?
Internet of Things (IoT) connects physical devices to the internet, enabling remote
monitoring and control. In this project:

Traditional Oximeter: You must be physically present to read values

IoT Oximeter: You can:

* Monitor readings from anywhere with internet
* Receive alerts on your smartphone
* Track historical data in the cloud
* Access from multiple devices simultaneously

IoT System Components

1. Hardware/Things: Sensors (MAX30100) and actuators
2. Internet: WiFi connectivity via ESP8266
3. Cloud/Server: Blynk servers or local web server
4. Application: Mobile app or web browser interface
