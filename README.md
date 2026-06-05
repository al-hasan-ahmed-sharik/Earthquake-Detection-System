# Earthquake Detection System

ESP32-based IoT earthquake detection system using MPU6050 accelerometer, Telegram alerts, and a real-time web dashboard.

<img width="1600" height="1160" alt="earthquake" src="https://github.com/user-attachments/assets/409d4a4d-9d24-42da-b41c-3f9e470848c4" />


## Features

* Real-time vibration monitoring
* G-force calculation
* Earthquake magnitude estimation
* Telegram alert notification
* Live web dashboard
* Wi-Fi enabled operation

## Hardware Used

* ESP32 Dev Module
* MPU6050 Accelerometer
* Buzzer
* Jumper Wires
* USB Power Supply


## Working Principle

1. MPU6050 continuously measures acceleration.
2. The system calculates total G-force.
3. If the vibration exceeds the threshold:

   * Buzzer activates
   * Telegram alert is sent
   * Dashboard status changes to Alert
4. Live sensor data is displayed through the web interface.

## Applications

* Smart Homes
* Schools and Offices
* Industrial Monitoring
* Safety Automation

## Author

Al Hasan Ahmed Sharik

