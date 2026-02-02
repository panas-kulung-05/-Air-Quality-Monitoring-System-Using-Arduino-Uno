🌱 Air Quality Monitoring System Using Arduino Uno
📌 Project Description

This project presents an Air Quality Monitoring System using Arduino Uno that measures air quality, temperature, and humidity in real time. The system uses an MQ-135 gas sensor to monitor air pollution levels, a DHT sensor to measure ambient temperature and humidity, and an OLED display with I2C interface to visually display the measured parameters.

The project is designed as a beginner-friendly embedded systems and environmental monitoring application, suitable for academic mini projects, Arduino learners, and basic IoT system foundations.

🎯 Project Objectives

• To monitor air quality using the MQ-135 gas sensor
• To measure temperature and humidity using the DHT sensor
• To display real-time sensor data on an OLED display using I²C communication
• To understand sensor interfacing and I²C protocol
• To develop a basic environmental monitoring system using Arduino

🧰 Components Required

• Arduino Uno
• MQ-135 Air Quality Sensor
• DHT11 / DHT22 Temperature & Humidity Sensor
• OLED Display (SSD1306) with I2C Module
• Breadboard
• Jumper Wires
• USB Cable

⚙️ Working Principle

The MQ-135 sensor detects harmful gases and provides an analog output proportional to air pollution concentration. The DHT sensor measures temperature and humidity using a digital signal.

Arduino Uno reads the sensor data, processes the values, and displays air quality level, temperature, and humidity on the OLED display via I²C communication, enabling real-time monitoring without the need for a computer.

🧠 Pin Configuration
| Component            | Arduino Pin            |
| -------------------- | ---------------------- |
| MQ-135 Analog Output | A0                     |
| DHT Data Pin         | Digital Pin (e.g., D2) |
| OLED SDA             | A4                     |
| OLED SCL             | A5                     |
| VCC                  | 5V                     |
| GND                  | GND                    |
