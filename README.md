# Radar-Tracking-System
Arduino-powered radar turret with ultrasonic detection, LED alerts, and processing-based visualisation.
# Arduino Radar Tracking System

A real-time radar turret simulation using Arduino and Processing. This project integrates servo control, ultrasonic sensing, and a custom radar-style UI to emulate object detection, similar to early-stage autonomous surveillance and defense systems.

---

##  Features

- Servo-mounted ultrasonic sensor sweeping from 0°–180°
- Real-time object detection rendered in Processing
- **Green LED** when **object is detected**
- **Red LED** when **no object is detected**
- Serial communication between Arduino and Processing
- Live display of angle and distance on-screen

## 💻 Technologies Used

| Component       | Description                            |
|----------------|----------------------------------------|
| **Arduino UNO** | Microcontroller handling servo + sensor |
| **HC-SR04**     | Ultrasonic sensor for range detection   |
| **Servo Motor** | Sweeps radar field                      |
| **LEDs (x2)**   | Green (detection), Red (no detection)   |
| **Processing 4**| Custom radar visual and serial interface |


## 🧠 What I Learned

- Microcontroller-to-PC serial data handling
- Real-time visualisation in Processing
- Debugging sensor noise and UI lag
- System integration: hardware, code, and communication

## 🚀 Future Enhancements

- Add buzzer or LCD alert system
- Improve UI with distance markers and signal trails
- Implement object tracking or camera integration
- Wireless comms (e.g., Bluetooth)
- Modular toggle modes (manual, auto, target lock)
