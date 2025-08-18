# 🔥 Fire Extinguisher Robot

An autonomous fire detection and suppression robot developed to identify and extinguish small-scale fires using sensor feedback and a motor-controlled extinguishing mechanism.

---

## 🔍 Project Overview

Fire accidents are dangerous, especially in enclosed or hazardous environments. This project presents a **low-cost, Arduino-based robotic system** that can:

- **Detect fire** using infrared (IR) or flame sensors  
- **Navigate** toward the fire source  
- **Extinguish fire** using a mounted pump/fan or CO₂ sprayer  
- Operate **autonomously or via remote control**

---

## 🧠 Features

- 🔎 **Flame Detection** using IR/Flame sensor array
- 🧭 **Autonomous Navigation** with obstacle avoidance
- 💨 **Fire Suppression System** using pump or fan
- 🚨 **Buzzer/LED Alert System**
- 🔋 **Battery Powered**

---

## ⚙️ Hardware Components

| Component            | Function                                 |
|---------------------|------------------------------------------|
| Arduino Uno          | Main microcontroller                    |
| Flame/IR Sensor      | Detects fire presence                   |
| Ultrasonic Sensor    | Avoids obstacles                        |
| Motor Driver (L298N) | Controls robot movement                 |
| DC Motors & Wheels   | Mobility                                |
| Pump                 | Extinguishes fire                       |
| Buzzer & LEDs        | Alerts for fire detection               |
| Power Supply (Battery)| Mobile power source                    |

---

## 🚀 Getting Started

### ✅ Requirements

- Arduino IDE installed
- Flame Sensor
- L298N Motor Driver
- Power source (9V/12V battery)

### 🔧 Setup Instructions

1. Connect sensors and modules as per `circuit_diagram.png`.
2.The arduio code mentioned in`codes` should be used in Arduino IDE.
3. Download the Mentioned libraries in Code.
4. Donload BLYNK IOT app from playstore and Create virtual pins for movement and displa of sensor values.
5. Paste the neccesary blynk template id and wifi name and password which is connected .
6. Upload the code to your Arduino board.
7. Power the robot and test in a controlled environment.

---
## 🔐 Safety Disclaimer

> ⚠️ This robot is designed for **educational purposes only** and **small, controlled fires**.  
> It is **not** intended for commercial or industrial fire fighting applications.
---

## 👤 Author
- **Varnan Reddy Pininti**  
  Member, The Robotics Club – SNIST  
---

> 🚒 Building smart safety systems with robotics and innovation!

