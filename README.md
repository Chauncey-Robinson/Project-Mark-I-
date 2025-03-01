# Project Mark I 🚀

## Overview
Project Mark I is an AI-powered robotic system designed for **voice interaction, autonomous movement, and remote control**.  
It is built on a modified **1980s Tomy Verbot**, integrating modern AI and IoT capabilities to enhance functionality and interactivity.

## Features
- 🎙️ **AI-Powered Voice Recognition** – Enables interaction using **natural language processing**.
- 📱 **Remote Control via Mobile App** – Allows movement and function execution through a **smartphone**.
- 🤖 **Autonomous Navigation** – Uses **sensors** for obstacle detection and route planning.
- 🗣️ **Text-to-Speech (TTS) Output** – Provides **verbal feedback and responses**.
- 🛠️ **Modular Design** – Easily **upgradable** with additional features such as **cameras and machine learning models**.

---

## ⚙️ Hardware Base
Project Mark I is a **modernized version of the Tomy Verbot**, a 1980s voice-controlled toy robot.  
This project replaces the original circuits with **AI-driven Raspberry Pi controls, new motors, and expanded functionality**.

## 🔧 Hardware Requirements
- 🖥️ **Raspberry Pi 5 (8GB RAM)**
- ⚙️ **L298N Motor Driver**
- 🚀 **High-Torque DC Motors (x2)**
- 🔋 **Li-Ion Battery Pack (7.4V, 3000mAh)**
- 🎵 **MAX98357A DAC Audio Module**
- 🔊 **Mini Speaker (3W)**
- 🌐 **Wi-Fi + Bluetooth Module**
- 🔌 **Jumper Wires & Connectors**
- 🛠️ **Soldering Kit & Multimeter**

---

## 🖥️ Software Requirements
- **Raspberry Pi OS (64-bit)**
- **Python 3.9+**
- **OpenCV** (for vision processing, if applicable)
- **SpeechRecognition** (for voice commands)
- **pyttsx3** (for text-to-speech output)
- **Flask** (for mobile app integration)

---

## 📦 Installation

### 1️⃣ Clone the repository:
```bash
git clone https://github.com/Chauncey-Robinson/Project-Mark-I.git
cd Project-Mark-I
```

### 2️⃣ Install dependencies:
```bash
pip install -r requirements.txt
```

### 3️⃣ Configure voice recognition and motor control scripts:
```bash
python setup.py
```

### 4️⃣ Run the main application:
```bash
python main.py
```

---

## 🔮 Future Enhancements
✅ **AI-Powered Vision** – Integration of **computer vision for facial/object recognition**.  
✅ **Advanced Navigation** – Improved **obstacle avoidance using LiDAR**.  
✅ **Cloud Connectivity** – Syncing data with a **cloud server for analytics and remote monitoring**.  
✅ **Expanded Voice Control** – More **interactive and context-aware speech processing**.  

---

## 🤝 Contributing
Contributions are **welcome**! Please **submit a pull request** or **open an issue** for discussion.

---

## 📜 License
This project is licensed under the **MIT License**. See [`LICENSE`](LICENSE) for more details.

---

## 📬 Contact
For inquiries, reach out via **GitHub Issues** or **Discussions**.
