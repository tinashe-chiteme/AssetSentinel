# AssetSentinel

An ESP32-based prototype exploring low-cost vibration monitoring for infrastructure disturbance detection.

## Overview

AssetSentinel is an embedded systems prototype developed to explore how low-cost sensing and IoT technologies can be used to detect physical disturbances on infrastructure assets.

The current prototype combines an ESP32 microcontroller, an MPU6050 motion sensor, MQTT messaging, and a Node-RED dashboard to demonstrate how vibration events can be detected, classified, and communicated in real time.

Originally developed under the name VibeCheck, the project has since evolved into AssetSentinel as its scope expanded beyond an initial proof of concept.

## Motivation

Infrastructure theft and tampering remain significant challenges in many regions, particularly where electrical and communication infrastructure is widely distributed.

AssetSentinel investigates whether a compact, modular sensing device could contribute toward earlier awareness of unusual physical disturbances by combining embedded sensing with lightweight IoT technologies.

This project is intended as an engineering prototype rather than a commercial security product.

## Features
ESP32-based embedded platform
MPU6050 vibration sensing
Dual-threshold disturbance detection
OLED local status display
Audible alarm output
MQTT communication
Node-RED dashboard
Remote event monitoring
Modular firmware architecture
Designed as a learning and research prototype
## System Architecture

Physical Disturbance
          │
          ▼
     MPU6050 Sensor
          │
          ▼
        ESP32
          │
 ┌────────┴────────┐
 │                 │
 ▼                 ▼
Local Alarm     MQTT Broker
                     │
                     ▼
                Node-RED
                     │
                     ▼
              Dashboard & Alerts

## Hardware

The prototype currently consists of:

ESP32 Development Board
MPU6050 Accelerometer/Gyroscope
SSD1306 OLED Display
Relay Module
Active Buzzer
Push Button
Breadboard Prototype
Supporting wiring and power supply

See the hardware/ folder for further details.

## Software Stack
Arduino IDE
C++
ESP32 Arduino Framework
MQTT
HiveMQ
Node-RED
GitHub
Demonstration

This repository includes:

Prototype photographs
Dashboard screenshots
Demonstration videos

These media illustrate the prototype's current capabilities and development progress.

## Current Status

Current development focuses on improving:

Detection reliability
Firmware architecture
Calibration
System robustness
Cloud integration
Scalability

The project remains under active development.

## Lessons Learned

Developing AssetSentinel has involved much more than writing firmware.

Key learning areas have included:

Embedded systems integration
Sensor calibration
Modular firmware design
MQTT communication
Dashboard development
Engineering documentation
Iterative prototyping
Communicating technical work to both engineers and non-technical audiences
## Repository Structure
media/
hardware/
dashboard/
firmware/
Disclaimer

AssetSentinel is an educational engineering prototype developed to explore embedded sensing concepts.

It has not been certified, field validated, or evaluated for commercial deployment.

## Acknowledgements

This project benefited from publicly available documentation, open-source libraries, and AI-assisted development tools used to accelerate learning, debugging, and documentation. All engineering decisions, system integration, testing, and project direction remained the responsibility of the project developer.
