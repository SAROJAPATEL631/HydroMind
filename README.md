# 🌱 HydroMind – Intelligent Hydroponics Management System

HydroMind is a smart IoT-based hydroponics management system developed using NodeMCU ESP8266 and Arduino IDE. The system enables real-time environmental monitoring, automation, and remote control via a web-based interface.



## 📌 Project Overview

This project integrates sensors, automation hardware, and Wi-Fi connectivity to monitor and control hydroponic farming conditions efficiently and sustainably.

The system monitors:
- Water Turbidity
- Temperature
- Humidity

It automates:
- Water Pump
- Ventilation Fan
- Lighting System
- Servo-controlled valve



## 🛠 Hardware Components

- NodeMCU ESP8266
- DHT11 Temperature & Humidity Sensor
- Turbidity Sensor
- DS18B20 Temperature Sensor
- Servo Motor
- Relay Module
- Water Pump
- Ventilation Fan
- 12V Battery
- Solar Panel
- Power Supply Module



## 💻 Software & Libraries Used

- Arduino IDE
- ESP8266WiFi.h
- Servo.h
- DHT.h
- SPI.h
- OneWire.h
- DallasTemperature.h

---

## 🌐 System Architecture

The system uses ESP8266’s built-in Wi-Fi to host a web server. Users can access the dashboard using the ESP’s IP address.

Sensors collect real-time data → ESP8266 processes it → Displays on web page → Controls devices via HTTP requests.



## ⚙ Functional Features

- Real-time sensor monitoring
- Web-based control interface
- Automatic response within 2 seconds
- Solar-powered energy integration
- Remote access via IP address


## 📊 Results

- Temperature Precision: ±0.5°C
- Automation Response Time: < 2 seconds
- Solar Backup Duration: 8 hours under moderate sunlight

## 🔮 Future Improvements

- Add pH and nutrient sensors
- Machine learning for crop prediction
- Mobile app integration
- Hybrid renewable energy
- IoT cloud integration
- Water recycling module


## 📷 System Diagram

(Refer to circuit_diagram folder)


## 👨‍💻 Author

SAROJA PATEL
IoT & Embedded Systems Enthusiast  
