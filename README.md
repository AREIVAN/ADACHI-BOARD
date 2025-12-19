# ADACHI-BOARD  
### Custom Embedded Control Board for Mini Sumo Robotics  
**ESP32-S3 | PCB Design | Motor Control | Embedded Systems**

---

## 📍 Overview

**ADACHI-BOARD** is a **custom-designed embedded control board** developed for **Mini Sumo robotic applications**, focused on **real-time control**, **compact PCB design**, and **competition-grade reliability**.

This project was created as part of my professional and academic development in **Robotics, Embedded Systems, and Industrial Electronics**, and it is intended to serve as both a **functional robotic platform** and a **technical portfolio project**.

---

## 🎯 Project Objectives

- Design a **compact and robust PCB** for competitive robotics
- Implement **reliable motor control** using discrete drivers
- Apply **best practices in embedded hardware design**
- Demonstrate skills in:
  - PCB design
  - Power regulation
  - Microcontroller integration
  - Robotics-oriented system architecture

---

## ⚙️ System Architecture

- **Main MCU:** ESP32-S3 Mini-1U  
- **Motor Control:** Dual DRV8871 DC motor drivers  
- **Sensors:** Support for up to 10 external sensors  
- **Actuators:** 2 servo outputs  
- **User Interface:** Hardware buttons for strategy selection  
- **Programming Interface:** TTL (UART)  

The board is designed to minimize latency and allow fast response times, which are critical in competitive robotics environments.

---

## 📐 Technical Specifications

| Feature | Description |
|------|------------|
| Board Size | 60 mm × 30 mm |
| Max Input Voltage | 24 V |
| MCU | ESP32-S3 Mini-1U |
| Motor Drivers | DRV8871 |
| Voltage Regulation | 5 V / 3.3 V |
| LEDs | SK0605 2427 |
| Programming | UART (TTL) |
| Target Application | Mini Sumo Robot |

---

## 🔘 Hardware Controls

- **RESET** – Microcontroller reset  
- **BOOT** – Programming mode access  
- **STRATEGY 1** – Strategy selection input  
- **STRATEGY 2** – Strategy selection input  

These buttons allow strategy changes without reflashing firmware, improving usability during competitions or testing.

---

## 🧠 Design Considerations

- Compact footprint optimized for Mini Sumo chassis
- Separation of power and logic domains
- Component selection focused on availability and reliability
- Design prepared for iterative improvement and future expansion

---

## 📂 Repository Structure
![image](https://github.com/user-attachments/assets/93abe474-f247-4b41-89b1-24b944a14025)
![image](https://github.com/user-attachments/assets/013f5bd1-25bb-41d6-ab42-1ba63af5e245)


*(Structure may evolve as the project progresses)*

---

## 🚧 Project Status

- ✔ PCB design completed  
- ✔ Component selection validated  
- 🔄 Firmware development in progress  
- 🔄 Testing and optimization phase  

---

## 🔮 Planned Improvements

- Encoder feedback integration
- Power efficiency optimization
- Enhanced firmware architecture
- Step-by-step replication documentation
- Optional telemetry and data logging

---

## 👨‍💻 About the Author

**Areivan**  
Industrial Robotics Engineering Student  
Industrial Maintenance Technician  

- Experience in embedded systems and PCB design  
- Background in industrial automation and maintenance  
- Focused on robotics, electronics, and applied engineering  

🔗 GitHub: https://github.com/AREIVAN

---

## 📜 License & Usage

This project is intended for **educational and experimental purposes**.  
You may reference or reuse the design with proper credit to the author.
