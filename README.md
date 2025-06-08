# Dual-Axis Solar Tracker

A servo-based tracker using four LDR sensors to automatically align a solar panel with the sun in both azimuth and elevation to improve total daily energy capture.

---

### ⚙️ Hardware Design
- 2x Servo motors (X and Y axis)
- Arduino UNO + 4 LDR sensors
- 10W solar panel + voltmeter for output tracking

---

### 🧠 Control/Software Features
- Differential LDR sensor logic
- Sweep correction every 10 seconds
- Energy measurement using voltage divider + analogRead

---

### 📊 Results (Expected)
- ±5° tracking error max
- ~15% energy gain over static mount
- Diurnal cycle logging (sunrise to sunset)

---

### 🧰 Tools Used
- Arduino IDE, Embedded C++
- Excel, Python (matplotlib)
- Tinkercad + Fusion 360 for mount design

---

### 🚧 Project Status
🛠️ Status: In Progress – Summer 2025
