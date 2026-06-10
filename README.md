# 💧 Intelligent IoT-Based Water Leakage Detection System Using Machine Learning

## 🔍 Overview

The Intelligent IoT-Based Water Leakage Detection System is designed to monitor water flow in pipelines and detect leakage in real time using dual flow sensors and an ESP32 microcontroller.

The system continuously compares inlet and outlet flow rates, analyzes the data, and identifies abnormal flow conditions. Leakage information is displayed locally and can be monitored remotely through an IoT dashboard.

## 🚀 Features

- Real-time water flow monitoring
- Leakage detection using dual flow sensors
- ESP32-based IoT connectivity
- Machine Learning-based leakage analysis
- Cloud dashboard visualization
- Event logging and monitoring
- Automated alert notifications
- LCD status display

## 🛠️ Hardware Components

- ESP32 Development Board
- 2 × Hall-Effect Water Flow Sensors
- 16×2 LCD Display
- Buzzer
- Power Supply Unit
- PVC Pipeline Setup

## 💻 Software & Technologies Used

| Category | Technology |
|-----------|------------|
| Programming | Arduino C/C++ |
| Microcontroller | ESP32 |
| Machine Learning | Random Forest |
| Development Tool | Arduino IDE |
| Dashboard | IoT Cloud Dashboard |
| Data Analysis | Python |

## ⚙️ Working Principle

1. The inlet and outlet flow sensors continuously measure water flow.
2. ESP32 collects and processes the sensor data.
3. Flow rates are compared to identify possible leakage.
4. Machine Learning logic analyzes the flow difference.
5. Leakage status is displayed on the LCD.
6. Alerts and monitoring data are sent to the IoT dashboard.
7. Users can monitor the system remotely in real time.

## 📊 Machine Learning Model

A Random Forest-based Machine Learning model is used to classify water flow conditions as:

- Normal Flow
- Leakage Detected

The model analyzes flow-rate variations and differential flow values to improve detection accuracy and reduce false alarms.

## 📈 Results

- Achieved **93.2% leakage detection accuracy**
- Real-time monitoring and alert generation
- Automated leakage identification
- Remote dashboard visualization
- Reliable performance for smart water management applications

## 🖥️ Dashboard Output

### Real-Time Monitoring Dashboard

![Dashboard Output](Images/Dashboard_Output.png)

## 🔧 Hardware Setup

### Prototype Setup

![Hardware Setup](Images/Hardware_Setup.jpg)

## 🎯 Future Enhancements

- Mobile application integration
- Advanced leak severity prediction
- Cloud database storage
- Predictive maintenance analytics
- Smart city water management integration

