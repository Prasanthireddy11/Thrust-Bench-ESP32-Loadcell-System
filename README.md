# Thrust-Bench-ESP32-Loadcell-System
Real-time thrust measurement system using ESP32, HX711 load cells, MAX6675 thermocouple, IR RPM sensor, and WebServer interface for drone propulsion testing.
## 🔧 Project Overview

This project is a fully functional thrust bench setup built using an ESP32 microcontroller to test and measure drone propulsion performance. It collects real-time data including thrust, torque, RPM, and temperature. The system is designed to help in evaluating motor-propeller-ESC combinations, especially for drone applications.

---

## 📦 Features

- 🧲 **Thrust & Torque Measurement** using HX711 and Load Cells (20kg, 40kg)
- 🌡 **Temperature Monitoring** via MAX6675 & K-Type thermocouple
- ⚙️ **ESC Control** using PWM signal from ESP32
- 🌀 **RPM Sensing** using IR sensor with signal filtering
- 🌐 **Web Interface** built with ESPAsyncWebServer for live monitoring and control
- 📟 **LCD I2C Display** support for local data readout
- 📤 **Wi-Fi Data Transmission** for remote monitoring

---

## 🛠 Hardware Used

- ESP32 (Wi-Fi + PWM control)
- HX711 Load Cell Amplifier
- Load Cells (20kg for thrust, 5kg or 40kg for torque)
- MAX6675 Thermocouple Module
- K-Type Thermocouple
- IR RPM Sensor (for optical RPM measurement)
- BLDC Motor + ESC
- LCD 16x2 with I2C
- 60V DC Power Supply

---

## 🧠 My Contribution

- Complete embedded code development in Arduino IDE
- Sensor interfacing, calibration, and filtering
- Web interface development using ESPAsyncWebServer
- Hardware integration and testing
- Debugging real-time sensor outputs and performance optimization

---




