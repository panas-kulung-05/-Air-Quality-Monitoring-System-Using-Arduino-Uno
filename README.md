🌱 **Air Quality Monitoring System Using Arduino Uno
📌 Project Description**

This project presents an Air Quality Monitoring System using Arduino Uno that measures air quality, temperature, and humidity in real time. The system uses an MQ-135 gas sensor to monitor air pollution levels, a DHT sensor to measure ambient temperature and humidity, and an OLED display with I2C interface to visually display the measured parameters.

The project is designed as a beginner-friendly embedded systems and environmental monitoring application, suitable for academic mini projects, Arduino learners, and basic IoT system foundations.

🎯 **Project Objectives**

• To monitor air quality using the MQ-135 gas sensor<br>
• To measure temperature and humidity using the DHT sensor<br>
• To display real-time sensor data on an OLED display using I²C communication<br>
• To understand sensor interfacing and I²C protocol<br>
• To develop a basic environmental monitoring system using Arduino<br>

🧰 **Components Required**

• Arduino Uno<br>
• MQ-135 Air Quality Sensor<br>
• DHT11 / DHT22 Temperature & Humidity Sensor<br>
• OLED Display (SSD1306) with I2C Module<br>
• Breadboard<br>
• Jumper Wires<br>
• USB Cable<br>

⚙️ **Working Principle**

The MQ-135 sensor detects harmful gases and provides an analog output proportional to air pollution concentration. The DHT sensor measures temperature and humidity using a digital signal.

Arduino Uno reads the sensor data, processes the values, and displays air quality level, temperature, and humidity on the OLED display via I2C communication, enabling real-time monitoring without the need for a computer.

🧠 Pin Configuration
| Component            | Arduino Pin            |
| -------------------- | ---------------------- |
| MQ-135 Analog Output | A0                     |
| DHT Data Pin         | Digital Pin (e.g., D2) |
| OLED SDA             | A4                     |
| OLED SCL             | A5                     |
| VCC                  | 5V                     |
| GND                  | GND                    |

💻 Software Requirements

Arduino IDE

DHT Sensor Library

Adafruit SSD1306 Library

Adafruit GFX Library

🧾 Code Overview

Initializes MQ-135, DHT sensor, and OLED display

Reads air quality, temperature, and humidity values

Processes sensor data

Displays real-time values on OLED display

Optional serial monitor output for debugging

📊 Output

Air Quality Level (Analog value / PPM approximation)

Temperature (°C)

Humidity (%)

Displayed in real time on OLED screen

🚀 Applications

Indoor air quality monitoring

Environmental monitoring systems

Smart home applications

Academic mini projects

IoT system prototypes

📚 Learning Outcomes

Interfacing analog and digital sensors with Arduino

Understanding I²C communication protocol

Real-time data visualization using OLED display

Embedded system programming fundamentals

🔮 Future Enhancements

Integrate IoT platforms (ESP8266 / ESP32)

Add mobile or web dashboard

Implement air quality alert system

Data logging and cloud storage

📜 License

This project is open-source and intended for educational use.
