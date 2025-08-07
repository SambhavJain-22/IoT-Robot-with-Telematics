# 🤖 Obstacle Avoiding Robot with Telematics Feature (ESP32-Based)

This project is a smart robot built using an **ESP32** that can autonomously **avoid obstacles** and monitor **temperature and humidity** in real-time. The data is displayed on a self-hosted **web dashboard**, accessible from any device on the same Wi-Fi network.

---

## 🚀 Features

- ✅ **Obstacle Avoidance** using Ultrasonic Sensor
- ✅ **Environmental Monitoring** with DHT11 (Temp + Humidity)
- ✅ **Wi-Fi Connectivity** using ESP32 Dev Module
- ✅ **Real-Time Web Dashboard** (auto-refresh every 5 seconds)
- ✅ **Motor Control** via L298N Driver
- ✅ **Clean and Modular Arduino Code**

---

## 📷 Preview

### 🔧 Robot Setup
![Robot Front View](Images/robot_front_view.jpg)

### 📊 Web Dashboard
![Web Dashboard](Images/dashboard_screenshot.png)

---

## 🔌 Components Used

| Component            | Quantity | Purpose                          |
|----------------------|----------|----------------------------------|
| ESP32 Dev Module     | 1        | Main controller + Wi-Fi          |
| Ultrasonic Sensor    | 1        | Obstacle detection               |
| DHT11 Sensor         | 1        | Temp & humidity monitoring       |
| L298N Motor Driver   | 1        | Drive DC motors                  |
| DC Motors            | 2        | Movement                         |
| Chassis + Wheels     | 1 set    | Robot structure                  |
| Battery              | 1        | Power supply                     |

---

## 📁 Folder Structure
```bash
├── Arduino_Code/                  # Main Arduino .ino sketch
├── Images/                        # Photos, screenshots, diagrams
├── Documents/                     # PDF report or supporting docs
├── README.md                      # This file
└── LICENSE                        # (Optional) Open-source license
