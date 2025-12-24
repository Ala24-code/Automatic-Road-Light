# ESP32 Smart Road Lighting System (MicroPython)

## 📌 Project Overview
This project implements a **Smart Road Lighting System** using an **ESP32**, an **Infrared (IR) sensor**, an **LDR light sensor module**, and **4 LEDs**.

The system automatically turns ON the road lights **only at night** and **only when a vehicle or person is detected**, helping to reduce energy consumption and improve efficiency.

---

## 🚗 How It Works
1. The **LDR module** detects ambient light:
   - Day → Lights remain OFF
   - Night → System becomes active
2. The **IR sensor** detects a moving vehicle or person.
3. When motion is detected at night:
   - All 4 LEDs turn ON (simulating street lights)
4. If no motion is detected:
   - LEDs turn OFF automatically after a delay

---

## 🛠️ Components Required
- ESP32 Development Board  
- Infrared (IR) Obstacle Sensor  
- LDR Light Sensor Module (with potentiometer)  
- 4 × LEDs  
- 4 × 220Ω Resistors  
- Breadboard  
- Jumper Wires  

---

## 📷 Demo Video
👉 [Click here to watch the demo](https://youtu.be/IbgxXM6DQ8c)

---

## 🔌 Pin Connections
| Component | ESP32 Pin |
|---------|-----------|
| IR Sensor OUT | GPIO 26 |
| LDR Module DO | GPIO 27 |
| LED 1 | GPIO 14 |
| LED 2 | GPIO 12 |
| LED 3 | GPIO 13 |
| LED 4 | GPIO 15 |
| VCC | 3.3V |
| GND | GND |

⚠️ Adjust the **LDR module sensitivity** using the onboard potentiometer.

---

## 💻 Software Requirements
- MicroPython firmware installed on ESP32  
- Thonny IDE (or any MicroPython-compatible IDE)

---

## 🧾 MicroPython Code
- MicroPython: `Automatic-Road-Light..py`  

---

## 👩‍💻 Author

**Ala Toumi**
3rd-year Computer Engineering Student
Embedded Systems & IoT enthusiast

---

## 📎 License

MIT License – Free to use and modify.
