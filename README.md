# weather-station
Developed a weather station capable of measuring wind speed, temperature, humidity, and UV radiation

Project Overview
This project involves the development of an IoT-based weather station using the **ESP8266 microcontroller**, aimed at real-time environmental monitoring.  

The system integrates multiple sensors:
- **DHT11** → Temperature & Humidity
- **BMP180** → Atmospheric Pressure & Altitude
- **Custom Anemometer (DC Generator)** → Wind Speed via analog input

Sensor data is transmitted to the **Blynk IoT platform** via Wi-Fi, enabling real-time visualization through a mobile app. Readings are updated every **1 second**.

 Technologies Used
- ESP8266 (NodeMCU)
- DHT11 Sensor
- BMP180 Sensor
- Custom Anemometer (DC generator → ESP8266 A0)
- Blynk IoT Cloud
- Arduino IDE (C++)
- (Optional) Python + MySQL for data logging

---

 Features
- Real-time monitoring of:
  -  Temperature (°C)
  -  Humidity (%)
  -  Wind Speed (m/s)
  -  Atmospheric Pressure (hPa)
  -  Altitude (m)
- Simple, low-cost design using minimal components
- Remote access & visualization via **Blynk mobile app**
- Scalable: Can log data into a **MySQL database** with a Python server

---

 Repository Contents
- `/code` → Arduino sketch for ESP8266 (main firmware)
- `/server_logger` → Python + SQL files for local data logging
- `/circuit_diagram` → wiring diagrams 

---
Developed by Yogeshwar reddy desireddi
