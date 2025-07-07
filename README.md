# 🧭 Navigation Aid for Visually Impaired

A smart, wearable, and offline-capable navigation device built for visually impaired individuals. It uses real-time object detection, LiDAR-based depth sensing, and haptic/audio feedback to assist users in navigating indoor and outdoor environments independently and safely.

---

## 📌 Project Overview

This project provides a hands-free mobility solution for the visually impaired by integrating AI vision, depth sensing, and multi-modal feedback in a lightweight wearable format. Designed with affordability and usability in mind, it offers real-time obstacle detection without relying on internet or GPS.

---

## 🌟 Key Features

- ✅ **LiDAR and Ultrasonic Sensors** for real-time distance sensing
- ✅ **YOLOv8 Object Detection** (30+ classes)
- ✅ **Vibration Feedback** for obstacle proximity
- ✅ **Audio Guidance** using offline text-to-speech and Bluetooth
- ✅ **Offline Operation** (no internet or GPS required)
- ✅ **Low-Cost & Modular** (₹19,961 total fabrication cost)

---


![Project Status](./assets/project-status.png)


## 🏗️ System Architecture

### 🔌 Hardware Flow


#### [Camera] → [Raspberry Pi 5 + YOLOv8] → Object Detection
#### ↓
#### [ESP32 Microcontroller + Sensors (LiDAR, Ultrasonic)]
#### ↓
#### [Vibration Motors] + [Bluetooth Audio Output]


### 💻 Software Components

- `Python 3.10`
- `YOLOv8` (Ultralytics) + `OpenCV`
- `pyttsx3` for offline TTS
- `RPi.GPIO` for hardware control
- XML-labeled datasets for object training

---

## 🛠️ Hardware Components

| Component                          | Description                                 |
|-----------------------------------|---------------------------------------------|
| Raspberry Pi 5 (32GB RAM)         | Main processing and detection system        |
| ESP32 WROOM-32                    | Microcontroller for sensors and actuators   |
| TFMini-S LiDAR Sensors (×4)       | Accurate depth and distance sensing         |
| Ultrasonic Sensor (HC-SR04)       | Short-range object detection                |
| ERM Coin Vibration Motors (×6)    | Haptic feedback                             |
| Realtek AMB82-Mini AI Camera      | Live video feed for object detection        |
| Bluetooth Earphones               | Audio output for feedback                   |
| GPS NEO-6M Module (planned)       | Future outdoor navigation integration       |
| SanDisk 32GB MicroSD Card         | Storage for OS and models                   |
| 20000mAh Li-ion Power Bank        | Portable power source                       |
| 3D Printed Enclosure              | Lightweight housing                         |

---


## 📈 Project Status

- ✅ Real-time object detection with YOLOv8  
- ✅ Integrated LiDAR + ultrasonic sensing  
- ✅ Working haptic + audio feedback  
- ⏳ GPS integration planned  
- ⏳ Mobile app and cloud sync in development  

---

## 🔮 Future Roadmap

- 📍 GPS-based route navigation and landmark tracking  
- 📱 Companion mobile app (route setup, customization)  
- ☁️ Cloud sync for logging and updates  
- 🔁 Community support and open-source contributions  

---

## 👥 Team

**Project by students of IIITDM Jabalpur:**

- Archakam Sree Chaithanya (CSE)  
- Shreyansh Tripathi (ECE)  
- Satwik Baruri (Design)  
- Aman Dhoke (CSE)  
- Amit Kumar (ECE)  
- Aryan (Smart Manufacturing)  

**Guided by**: Dr. Dinesh Kumar V., Dept. of Electronic and Communication Engineering

---

## 📚 References
- [1 Research](https://www.ijraset.com/best-journal/smart-wearable-guiding-device-for-the-visually-impaired-people)
- [2 Research](https://www.mordorintelligence.com/industry-reports/assistive-technologies-for-visually-impaired-market)
- [3 Research](https://www.researchgate.net/publication/235005436_Guiding_Blind_People_with_Haptic_Feedback)
