# Smart Laboratory Safety System

An IoT-based Smart Laboratory Safety System developed using **ESP32, Firebase Realtime Database, and MIT App Inventor** for real-time laboratory monitoring and safety management.

---

## 📌 Project Overview

The Smart Laboratory Safety System continuously monitors laboratory conditions and alerts users during hazardous situations such as:

* High temperature
* Gas leakage
* Fire detection
* Unauthorized motion detection

Sensor data is transmitted to Firebase Realtime Database and monitored through a mobile application developed using MIT App Inventor.

---

## 🚀 Features

* Real-time temperature monitoring
* Humidity monitoring
* Gas leakage detection
* Fire detection
* Motion detection
* Automatic alarm activation
* Relay control
* Firebase cloud integration
* Mobile application monitoring
* Safety status indication
* Emergency alerts

---

## 🛠 Hardware Components

| Component                 | Quantity    |
| ------------------------- | ----------- |
| ESP32 Dev Module          | 1           |
| DHT22 Sensor              | 1           |
| MQ2 Gas Sensor            | 1           |
| PIR Motion Sensor         | 1           |
| Push Button (Fire Sensor) | 1           |
| Relay Module              | 1           |
| Buzzer                    | 1           |
| LED                       | 1           |
| Jumper Wires              | As required |

---

## 📡 Software Used

* Arduino IDE
* Wokwi Simulator
* Firebase Realtime Database
* Firebase Authentication
* MIT App Inventor
* GitHub

---

## 🔌 Pin Connections

| Component   | ESP32 Pin |
| ----------- | --------- |
| DHT22       | GPIO 27   |
| PIR Sensor  | GPIO 15   |
| Fire Button | GPIO 4    |
| MQ2 Sensor  | GPIO 35   |
| Relay       | GPIO 2    |
| Buzzer      | GPIO 14   |
| LED         | GPIO 13   |

---

## ☁ Firebase Database Structure

```json
Laboratory
{
  "temperature": 24,
  "humidity": 40,
  "gas": 3628,
  "motion": 0,
  "fire": 0,
  "relay": 0,
  "status": "Safe"
}
```

---

## 📱 Mobile Application Features

* User Login Screen
* Real-time sensor monitoring
* Status monitoring
* Safe/Danger indication
* Color-based alerts
* Firebase data synchronization

---

## 🚨 Safety Conditions

| Condition          | Status |
| ------------------ | ------ |
| Temperature > 50°C | Danger |
| Gas > 3800         | Danger |
| Motion detected    | Danger |
| Fire detected      | Danger |

---

## 📂 Project Structure

```
Smart-Laboratory-Safety-System
│
├── ESP32_Code
│   └── SmartLabSafety.ino
│
├── MIT_App
│   └── SmartLabSafety.aia
│
├── APK
│   └── SmartLabSafety.apk
│
├── Wokwi
│   ├── diagram.json
│   └── wokwi-link.txt
│
├── Images
│   ├── circuit.png
│   ├── app.png
│   └── firebase.png
│
└── README.md
```

---

## ▶ How to Run

### ESP32

1. Open Arduino IDE.
2. Install required libraries:

   * DHTesp
   * Firebase ESP Client
3. Upload the code to ESP32.
4. Connect to WiFi.
5. Data will be uploaded to Firebase.

### Mobile Application

1. Install the APK.
2. Login using valid credentials.
3. Monitor laboratory conditions in real time.

---

## 🔥 Wokwi Simulation

Add your Wokwi project link here:

```
https://wokwi.com/projects/YOUR_PROJECT_ID
```

---

## 📸 Screenshots

* Wokwi Simulation
* Firebase Database
* Mobile Dashboard
* Login Screen

---

## 🎓 Academic Information

**Project Title:** Smart Laboratory Safety System

**Domain:** IoT and Embedded Systems

**Technologies:**

* ESP32
* Firebase
* MIT App Inventor
* IoT
* Embedded Systems

---

## 👨‍💻 Developer

**Ch. Sanjay Kumar**

Electronics and Communication Engineering

Aditya University

IEEE SPS Student Branch Chapter

---

## 📄 License

This project is developed for academic and educational purposes.
