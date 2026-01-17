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
