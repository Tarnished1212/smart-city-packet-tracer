# smart-city-packet-tracer
Design and build an intelligent urban environment for city monitoring, incorporating smart surveillance and intelligent street lighting within Cisco Packet Tracer. Automate the system with sensor-triggered actions for surveillance and lighting
# 🏙️ Smart City IoT Simulation – Cisco Packet Tracer

---

## 🎯 Aim

To design a smart urban simulation with:
- Motion-triggered automation of security devices
- Smartphone-based control of AC and fan
- Wi-Fi-only device communication with **no MCU scripting**

---

## 📌 Problem Statement

Traditional urban systems consume unnecessary power and lack responsiveness to real-time events. This project aims to solve that using IoT components that:
- **React to motion**
- **Let users control appliances wirelessly**
- **Demonstrate scalable automation logic**

---

## 🧠 Scope

- Built entirely in Cisco Packet Tracer
- Uses **IoT Monitor** rules (no code or microcontroller)
- All devices connected via Wi-Fi 
- Easily extendable for future systems like smart traffic lights or energy tracking

---

## 🏗️ Architecture Overview
[MOTION SENSOR] ───┐
[TEMP SENSOR] ─────┼────► [IoT HOME GATEWAY (192.168.25.1)]
                   │
          [SMARTPHONE / TABLET]
                   │
        ┌──────────┼────────────────────┐
        ▼          ▼                    ▼
    [LAMP]     [SIREN]             [AC / FAN] (Triggered via Rules or Manual)


---

## 🧰 Requirements

- Cisco Packet Tracer v8.2 or newer
- Devices used:
  - IoT Home Gateway
  - Smart Motion Sensor
  - Smart Lamp
  - Smart Siren
  - Smart Camera (optional)
  - Smart Fan
  - Smart Air Conditioner
  - Smartphone / Tablet for IoT Monitor access

---

## ⚙️ How It Works

- **Motion Sensor** triggers **Lamp**, **Siren**, and **Camera**
- **Fan** and **Air Conditioner** are switched manually via **IoT Monitor**
- All interactions handled via the **Smartphone interface** at `192.168.25.1`
- Simulation runs in **Realtime Mode** for instant feedback

---

## 🧪 Execution Steps

1. Connect all devices to ssid `HomeGateway` via Wi-Fi
2. Register each device to IoT Home Gateway at `192.168.25.1`
3. Open IoT Monitor via smartphone
4. Trigger motion → automated device response
5. Toggle fan & AC manually from the mobile UI

---

## 👨‍💻 Author

**Santhosh SK**  
B.Tech Mechatronics Engineering  
[VIT Chennai]





                     




