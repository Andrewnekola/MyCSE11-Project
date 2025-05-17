# Timer and Voltage Monitor - Final Project (CSE211s, Spring 2025)

## 📌 Overview
This is the final project for the Embedded Systems course (CSE211s).  
The project demonstrates a real-time **timer** and **voltage monitor** using a **4-digit 7-segment display**, **Arduino multifunction shield**, and **analog input** from the onboard potentiometer.

### Key functionalities:
- Time display in MM:SS format
- Live voltage reading from a potentiometer (0–3.3V)
- Min/Max voltage tracking
- Button-controlled display switching (time vs. voltage)

---

## 🔧 Components Used
- NUCLEO-F401RE development board
- Arduino Multifunction Shield (with built-in 4-digit 7-segment display, buttons, potentiometer)
- 74HC595 shift register (integrated on the shield)
- Onboard buttons:  
  - **S1** → Reset timer  
  - **S3** → Display voltage
- Onboard potentiometer for analog voltage input

---

## 🧠 How It Works
- Timer starts on boot and increments every second.
- Pressing **S1** resets the timer.
- Pressing **S3** toggles the display to show the live voltage.
- Voltage values are scaled and shown in X.XX format (e.g., 2.47V → “2.47”).
- Tracks and stores the minimum and maximum voltage values recorded.

---

## 🧪 Features
- Accurate timekeeping (MM:SS format)
- Real-time analog voltage monitoring
- Efficient 7-segment display control using a shift register
- Clean, modular C++ implementation using the `mbed` platform
- Debounced button functionality and responsive switching


---

## 👨‍💻 Developed By
**Andrew Nekola** - **Mina Ashraf** - **Mario Medhat**


Ain Shams University – Mechatronics Department  
Spring 2025

---

## 📝 License
This project is for **academic and educational** purposes only.

