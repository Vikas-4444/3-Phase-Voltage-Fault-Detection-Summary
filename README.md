# 🔌 3-Phase Voltage Fault Detector (ESP32 + Firebase)

A voltage monitoring and alert system for 3-phase power lines using ESP32 and ZMPT101B sensors. Designed to track low-voltage conditions in real-time and alert users when the DG (Diesel Generator) is active.

---

## 🧠 Features
- Voltage monitoring from 3-phase supply + DG using 4 ZMPT101B sensors
- Logs live voltage data to Firebase every 1 second
- Web app and PWA using Firebase Hosting
- Sends push notifications via Python FCM if DG is on and voltage drops

---

## 🔁 Flowchart

![Flowchart](Assets/3-Ph Fault Detector.drawio.png")

---

#NOTE:

This is a **summary-only** repo. Code is kept private.

🔒 To request access:
- Open an issue [here](https://github.com/Vikas-4444/3-Phase-Voltage-Fault-Detection-Summary/issues/new?title=Request+for+code+access&body=Hi%2C+please+grant+me+access+to+the+private+code+repo+for+this+project.)
- Or email me at **vikas.vivekanathan@gmail.com**

---

## 🧰 Tech Used
- **ESP32** with PlatformIO
- **ZMPT101B voltage sensors**
- **Firebase Realtime DB**, Hosting, and FCM
- **HTML, CSS, JS** frontend
- **Python** script for push notifications
