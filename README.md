# Baby Crying Detector 👶🔊

An Arduino-based system that detects loud sounds (like a baby's cry) and alerts the user via an LED and LCD screen.

---

## 📌 Overview

This project was built as part of an academic electronics module at ENSTTIC. It simulates a basic baby monitoring device that reacts to sound levels crossing a set threshold.

When crying is detected:
- A **LED light turns ON**
- An **LCD displays "Sound Detected"**

When there is no crying:
- The LED turns OFF
- The LCD displays "No Sound Detected"

---

##  Components Used

- Arduino Uno
- Sound Sensor Module
- LED + 220Ω resistor
- 20x4 LCD screen
- Breadboard & jumper wires

---

##  How It Works

1. **Microphone** picks up sound waves.
2. Signal is **amplified** and passed to a **comparator**.
3. If the sound level exceeds the threshold (set by a **potentiometer**), output is HIGH.
4. Arduino reads the sensor signal:
   - If HIGH → Turn on LED & show "Sound Detected" on LCD
   - If LOW → Turn off LED & show "No Sound Detected"

---

##  Code Highlights

- Uses `setup()` to initialize pins and LCD
- Continuously reads the sound sensor in `loop()`
- Responds in real-time with feedback on LCD + LED

###  Code Screenshot
![Code Screenshot](code.jpg)

---

## 🔧 Circuit Diagram

![Circuit Diagram](circuit.jpg)

---

##  Simulation

This project was simulated using **Proteus** before real hardware deployment.

---

##  Contributors

this prject was a team project 

---

##  Built At

**ENSTTIC** – National Higher School of Telecommunications and ICT  
Electronics Project | Academic Year: 2025
