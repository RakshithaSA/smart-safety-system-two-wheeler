# 🏍️ Smart Safety System for Two-Wheelers

## Overview
An ESP32-based embedded safety system that 
detects crashes, monitors drowsiness, and 
sends real-time alerts via Telegram API.

---

## 🔧 Hardware Used
- ESP32 Development Board
- MPU6050 (Accelerometer + Gyroscope) – I2C
- Buzzer module
- Power supply module

## 💻 Software & Tools
- Arduino IDE
- Embedded C
- Telegram Bot API
- I2C Protocol

---

## ⚙️ Features
- ✅ Crash detection using MPU6050 threshold
- ✅ Drowsiness monitoring via head tilt angle
- ✅ Over-speed alert system
- ✅ Real-time Telegram push notifications
- ✅ Interrupt-driven sensor reading

---

## 💡 How It Works
1. MPU6050 reads accelerometer data via I2C
2. Firmware checks threshold for crash/tilt
3. On trigger → ESP32 sends Telegram alert
4. Buzzer activates for local warning

---

## 📂 Code Structure
smart-safety-system/
├── main.ino          # Main program
├── mpu6050.h         # Sensor library
├── telegram.h        # API functions
└── config.h          # Pin definitions

---

## 🚀 Results
- Alert delivery time: under 2 seconds
- Crash detection accuracy: 95%+
- Successfully tested on hardware

---

## 👩‍💻 Author
Rakshitha S A | Embedded Systems Engineer
Bangalore | rakshithasa212@gmail.com
