# 🛡️ PrivacyGuard – AI Desktop Privacy Monitoring System

PrivacyGuard is an intelligent desktop security application that protects your screen from unauthorized viewers by continuously monitoring the surroundings using computer vision.

Unlike traditional screen-locking software, PrivacyGuard actively detects suspicious activity such as shoulder surfing, unknown faces and user absence. It provides real-time alerts, automatically captures faces and helps users maintain privacy while working in public or shared environments.

---

## 📌 Problem

Modern laptops contain sensitive personal and professional information, yet they remain vulnerable to:

- Shoulder surfing attacks
- Unauthorized screen viewing
- Identity theft
- Privacy leakage in public places
- Lack of intelligent monitoring while users are away

PrivacyGuard addresses these challenges using AI-powered face detection, gaze tracking, and real-time threat analysis.

---

## 🎯 Project Objective

The goal of PrivacyGuard is to build a smart desktop privacy assistant capable of:

- Monitoring nearby individuals in real time
- Detecting unauthorized viewers
- Identifying known and unknown faces
- Alerting users about privacy threats
- Capturing evidence of suspicious activity
- Providing privacy analytics and activity logs

---

# ✨ Features

### 👤 Face Recognition
- Detects multiple faces in real time
- Identifies authorized users
- Recognizes unknown visitors

### 👀 Shoulder Surfing Detection
- Detects prolonged screen observation
- Identifies suspicious viewing behavior
- Real-time privacy alerts

### 🎯 Gaze Tracking
- Estimates viewing direction
- Detects attention toward the screen
- Improves threat detection accuracy

### 🚨 Intelligent Threat Detection
- AI-based privacy risk analysis
- Unknown face detection
- Suspicious behavior monitoring
- Automatic event logging

### 📸 Evidence Capture
- Saves screenshots during security events
- Captures intruder images
- Stores incident history

### 📊 Privacy Analytics
- Threat statistics
- Event history
- User activity monitoring
- Privacy insights dashboard

### ⚙️ User Management
- Authorized user registration
- Settings management
- Configurable alert system

---

# Threat Levels:

🟢 Low — Only authorized user present
🟡 Medium — Multiple people nearby
🔴 High — Unknown person staring at screen

---

# 🏗 System Architecture

```
Webcam
      │
      ▼
Frame Capture Engine
      │
      ▼
Face Detection
      │
      ├──────────────► Face Recognition
      │
      ├──────────────► Gaze Tracking
      │
      ▼
Threat Detection Engine
      │
      ▼
Privacy Decision
      │
      ├────────► Alerts
      ├────────► Screenshot Capture
      ├────────► Database Logging
      └────────► Analytics Dashboard
```

---

# 🛠 Tech Stack

## Desktop Application

- Python
- PyQt6

## Computer Vision

- OpenCV
- MediaPipe
- Face Recognition
- NumPy

## Database

- SQLite

## Desktop Notifications 

- Plyer

## Other Libraries

- Pillow
- Threading
- JSON
- OS Utilities
- Matplotlib
- ReportLab

---

# ⚙ Installation

## 1. Clone Repository

```bash
git clone https://github.com/Ryzen-Starbit/PrivacyGuard.git

cd PrivacyGuard
```

## 2. Create Virtual Environment

```bash
python -m venv venv
```

## 3. Activate Environment

### Windows

```bash
venv\Scripts\activate
```

### Linux / macOS

```bash
source venv/bin/activate
```

## 4. Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶ Running the Application

Simply run:

```bash
python main.py
```

PrivacyGuard will initialize the camera, load settings, and launch the desktop monitoring interface.

---

# 📖 Usage

1. Launch PrivacyGuard.
2. Complete the initial setup.
3. Register authorized users.
4. Allow webcam access.
5. PrivacyGuard continuously monitors the environment.
6. Receive instant alerts whenever suspicious activity is detected.
7. Review captured incidents and analytics from the dashboard.

---

# 📂 Project Structure

```
PrivacyGuard/
│
├── alerts/
│   └── notification.py
│
├── assets/
│   ├── icons/
│   └── alert_sound.wav
│
├── core/
│   ├── capture_engine.py
│   ├── face_engine.py
│   ├── frame_processor.py
│   ├── gaze_tracker.py
│   └── threat_engine.py
│
├── data/
│   ├── authorized_faces/
│   ├── intruder_captures/
│   ├── screenshots/
│   └── settings.json
│
├── database/
│   ├── db_manager.py
│   └── privacy_guard.db
│
├── gui/
│   ├── analytics_panel.py
│   ├── log_viewer.py
│   ├── main_window.py
│   ├── overlay_window.py
│   ├── settings_panel.py
│   ├── setup_wizard.py
│   ├── tray_manager.py
│   └── user_manager.py
│
├── main.py
├── requirements.txt
└── README.md
```

---

# 🔒 Security Features

- Real-time face monitoring
- Unknown user detection
- Shoulder surfing alerts
- Automatic screenshot capture
- Event history logging
- Authorized user management
- Privacy-focused local processing

---

# 🤝 Contribution

Contributions, suggestions and improvements are welcome.

To contribute:

- Fork the repository
- Create a feature branch
- Commit your changes
- Push to your branch
- Submit a Pull Request

---
