# IoT-Based Smart Irrigation System

This repository contains the code and resources for an IoT-based smart irrigation system, designed to monitor soil moisture and automate irrigation using Arduino. The system uses the ThingSpeak platform to collect, visualize, and analyze data remotely, while also providing real-time moisture level display on an LCD screen.

## Features
- **Real-Time Monitoring:** Continuously tracks soil moisture levels and updates them to the ThingSpeak cloud for real-time data visualization.
- **LCD Display:** Shows live moisture readings directly on a connected LCD, allowing users to monitor data without needing to check ThingSpeak.
- **Automated Irrigation:** Automatically activates a water pump when the soil moisture falls below a predefined threshold.
- **Remote Control & Analytics:** Access and control the system remotely via ThingSpeak, and view historical data trends.
- **Low Power:** Energy-efficient design ideal for long-term field use.
  
## Components
- Arduino (any compatible board)
- Soil moisture sensor
- Water pump relay
- LCD display (16x2 or 20x4)
- ThingSpeak IoT platform
- Wi-Fi module (ESP8266 or similar)
  
## Getting Started
1. Clone this repository and upload the Arduino code to your board.
2. Connect your hardware according to the provided circuit diagram.
3. Configure your ThingSpeak API key and Wi-Fi credentials in the Arduino code.
4. View soil moisture data on the LCD display and monitor it remotely via ThingSpeak.

## Prerequisites
- Basic knowledge of Arduino and IoT.
- ThingSpeak account and API
