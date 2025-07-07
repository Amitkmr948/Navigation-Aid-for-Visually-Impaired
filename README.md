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

## 🏗️ System Architecture

### 🔌 Hardware Flow


# [Camera] → [Raspberry Pi 5 + YOLOv8] → Object Detection
# ↓
# [ESP32 Microcontroller + Sensors (LiDAR, Ultrasonic)]
# ↓
# [Vibration Motors] + [Bluetooth Audio Output]
