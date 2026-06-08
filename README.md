# 💧 Aqua Sense

Aqua Sense is a simple water quality monitoring system that uses a **turbidity sensor** to measure water clarity and display the results using **LED indicators** and an **OLED display**. The system helps classify water quality into three levels: clean, moderate, and dirty.

---

## 📌 Project Overview

This project measures water turbidity and provides real-time feedback:

- 🟢 **Green LED** → Clean water
- 🟡 **Yellow LED** → Moderate turbidity
- 🔴 **Red LED** → Dirty water

In addition, an **OLED display** shows the turbidity value in **ppm (parts per million)** for more precise monitoring.

---

## ⚙️ Features

- Real-time water quality monitoring
- Turbidity-based classification system
- LED status indicators for quick visual feedback
- OLED display showing turbidity (ppm)
- Simple and low-cost hardware design

---

## 🧰 Hardware Used

- Microcontroller (e.g., Arduino / STM32)
- Turbidity Sensor Module
- OLED Display (I2C)
- Green, Yellow, Red LEDs
- Resistors
- Breadboard & jumper wires
- Power supply (USB / battery)

---

## 🔌 System Logic

| Water Condition | Turbidity Level | LED Indicator |
|----------------|----------------|--------------|
| Clean          | Low            | 🟢 Green     |
| Moderate       | Medium         | 🟡 Yellow    |
| Dirty          | High           | 🔴 Red       |

---

## 🧠 How It Works

1. Turbidity sensor reads water clarity level.
2. Microcontroller processes analog sensor value.
3. System compares value with predefined thresholds.
4. Corresponding LED is activated.
5. OLED displays turbidity reading in ppm.

---

