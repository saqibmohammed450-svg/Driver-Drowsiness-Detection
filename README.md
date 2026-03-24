# 🚗 DrowsyGuard - Driver Drowsiness Detection System

A **Progressive Web Application (PWA)** designed to enhance road safety by detecting driver fatigue in real-time using **computer vision and machine learning**.

DrowsyGuard uses a smartphone’s front camera to monitor **facial landmarks and eye movements**, triggering alerts when drowsiness is detected  helping prevent accidents and improve driver awareness. 

---

## 📌 Overview

Driver drowsiness is a major cause of road accidents worldwide. Traditional systems are expensive and require special hardware.

**DrowsyGuard solves this problem by providing:**

* A **low-cost** solution
* Works on **any smartphone**
* Requires **no external hardware**
* Ensures **complete user privacy**

All processing is done locally on the device, making it fast, secure, and reliable. 

---

## ✨ Key Features

### 👁️ Real-Time Face & Eye Detection

* Detects face using camera
* Tracks eye movement continuously
* Works using **MediaPipe FaceMesh (468 landmarks)**

### ⚠️ Drowsiness Detection & Alerts

* Uses **Eye Aspect Ratio (EAR)** algorithm
* Detects eye closure & micro-sleep
* Triggers:

  * 🔊 Audio alerts
  * 📳 Vibration alerts

### 📊 Session Monitoring & History

* Tracks full driving session
* Records:

  * Start & end time
  * Duration
  * Number of alerts
  * Driver alertness level
* Helps analyze driver behavior over time

### ⚙️ Customizable Settings

* Adjust sensitivity thresholds
* Control alert volume
* Enable/disable vibration

### 🔐 Secure Authentication

* Login system with user specific data
* OTP based verification
* Ensures **data privacy and isolation**

### 📱 Progressive Web App (PWA)

* Works offline
* Add to home screen
* No installation required
* Cross-platform (Android & iOS)

---

## 🛠️ Tech Stack

### Frontend

* React.js
* HTML5
* CSS3 / Tailwind CSS
* JavaScript (ES6+)

### Machine Learning & Computer Vision

* MediaPipe FaceMesh
* TensorFlow.js

### APIs Used

* MediaDevices API (Camera access)
* WebRTC (Real-time video)
* Web Audio API (Alerts)
* Vibration API
* Local Storage / IndexedDB

---

## ⚙️ How It Works

1. 📷 Captures real-time video from the front camera
2. 🙂 Detects face using facial landmark model
3. 👁️ Tracks eyes and extracts eye region
4. 📐 Calculates **Eye Aspect Ratio (EAR)**
5. 🧠 Determines if eyes are closed for too long
6. 🚨 Triggers alert if drowsiness is detected
7. 📊 Stores session data for analysis


---

## 📋 Functional Requirements

* Real-time face detection
* Eye tracking & EAR calculation
* Drowsiness detection logic
* Alert triggering system
* Adjustable sensitivity

---

## 📈 Performance

* ⚡ Real-time processing (<150 ms delay)
* 🎥 15–30 FPS detection
* 🔋 Optimized battery usage
* 📦 Lightweight (<30 MB storage)

---

## 🔐 Security & Privacy

* No video data stored
* No cloud processing
* All computation happens locally
* Complete user data confidentiality

---

## 🧪 Testing

The system was tested under various real-world conditions:

* ✔️ Different lighting conditions
* ✔️ Users with/without glasses
* ✔️ Head movements
* ✔️ Real-time driving simulation

### ✅ Results

* Accurate face & eye detection
* Reliable drowsiness detection
* Timely alert generation
* Consistent performance across devices 

---

## 🚀 Advantages

* Low-cost & hardware-free
* Portable and easy to use
* Works offline
* High accuracy
* Privacy-focused
* Cross-platform compatibility

---

## 🌍 Applications

* Personal vehicle drivers
* Commercial & truck drivers
* Public transport systems
* Fleet management
* Safety monitoring systems

---

## 🔮 Future Enhancements

* ❤️ Heart rate monitoring
* 🌙 Night mode & low-light optimization
* 🚗 Vehicle system integration
* ☁️ Cloud analytics & driver reports
* 🗣️ Voice-based emergency alerts
* ⌚ Wearable device integration



---

## 👨‍💻 Author

* **Mohammed Saqib**


---
