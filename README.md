# Tank Volume Measurement System

This project measures and displays the **volume of water in a tank** using an **ultrasonic sensor** and an **Arduino UNO**.

## 📌 Overview
The ultrasonic sensor measures the distance from the sensor to the water surface.  
Using the known **height of the tank**, the **height of the water** is calculated as:


The volume is then calculated by multiplying the **height of water** by the **area of the tank’s base**.  
The calculated volume is displayed on an **LCD screen**.

---

## 🛠 Components Used
- Ultrasonic Sensor
- Arduino UNO
- Switch
- Battery
- LCD Display

---

## ⚙ Working Principle
1. **Distance Measurement** – The ultrasonic sensor measures the distance from its position to the water surface.
2. **Water Height Calculation** – The height of the water is determined by subtracting the measured distance from the total height of the tank.
3. **Volume Calculation** – The water height is multiplied by the area of the tank’s base to find the volume.
4. **Display** – The calculated volume is displayed on the LCD.

---

## 📂 Files in Repository
- **Code** – Arduino program to read the ultrasonic sensor, calculate the volume, and display it on the LCD.
- **Circuit Diagram** – Shows wiring between the Arduino, ultrasonic sensor, LCD, switch, and battery.
- **Project Photo** – Real-world image of the assembled system.


## 🚀 How to Use
1. Assemble the circuit as shown in the diagram.
2. Upload the Arduino code to the Arduino UNO.
3. Power the system using the battery.
4. The LCD will display the current water volume in the tank.


---
