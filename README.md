# 🩺 Arduino Nano Pulse Oximeter & Heart Rate Monitor PCB

## 📌 Project Description
This repository features a custom PCB design for a portable health monitoring system. The project is designed to measure **Heart Rate (BPM)** and **Blood Oxygen Saturation (SpO2)** using the **MAX30102 biometric sensor** and display real-time data on an **SSD1306 OLED screen**.

The circuit is built around an **Arduino Nano**, ensuring a compact footprint suitable for wearable applications. It incorporates hardware-level signal filtering to ensure stable user interaction.

## ⚙️ Key Features
* **Real-Time Tracking:** Instantly reads and displays pulse and oxygen levels.
* **Noise Filtering (Debouncing):** Uses RC filters (Resistor-Capacitor) on control buttons to prevent false switching and ensure smooth menu navigation.
* **Efficient Communication:** Utilizes the I2C protocol for minimal wiring between the sensor, display, and microcontroller.
* **Compact Design:** Optimized 2-layer PCB layout for portability.

## 🛠️ Components Used
* **Microcontroller:** Arduino Nano V3
* **Sensor:** MAX30102 (Pulse Oximetry & Heart Rate)
* **Display:** 0.96" OLED (SSD1306 Driver)
* **Input:** 3x Tactile Buttons with Hardware Debouncing
* **Power:** 5V USB (via Arduino Nano)

## 📂 Files in This Repository
* **Gerber Files (.zip):** Manufacturing files ready for PCB fabrication.
* **Schematic Image:** Circuit diagram showing connections and filters.
* **PCB Layout Image:** Top and bottom layer routing view.
* **3D View:** A rendered visualization of the final assembled board.

---
**Author:** Sefa Turan
