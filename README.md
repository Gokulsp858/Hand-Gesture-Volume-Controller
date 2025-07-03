# 🖐️ Hand Gesture Volume Controller

Control your system's audio volume using hand gestures in real-time!  
This project uses your webcam to detect your hand and adjust the volume by measuring the distance between your **thumb** and **index finger**.

---

[![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue?style=flat-square&logo=python)](https://www.python.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-enabled-green?style=flat-square&logo=opencv)]
[![Mediapipe](https://img.shields.io/badge/Mediapipe-Hands-orange?style=flat-square&logo=google)]
[![Live Demo](https://img.shields.io/badge/Live%20Demo-Netlify-brightgreen?style=for-the-badge&logo=netlify)](https://clinquant-sfogliatella-964b54.netlify.app)
Control your system's audio volume using hand gestures in real-time!
---

## 🎯 Features

- 🖐️ Real-time hand detection using Mediapipe
- 📏 Distance measurement between thumb & index finger
- 🔊 Control volume by pinching in/out
- 🖥️ Works on Windows using Pycaw for system audio

---

## 🛠️ Technologies Used

- [OpenCV](https://opencv.org/)
- [Mediapipe](https://google.github.io/mediapipe/)
- [Pycaw](https://github.com/AndreMiras/pycaw)
- Python 3.9+

---

## 📂 Folder Structure

Hand-Gesture-Volume-Controller/
├── main.py # Main script to run the controller
├── HandTrackingModule.py # Custom hand detection module
├── requirements.txt # Dependencies
└── README.md


---

## ▶️ How to Run

1. Clone the repo:

```bash
git clone https://github.com/Gokulsp858/Hand-Gesture-Volume-Controller.git
cd Hand-Gesture-Volume-Controller

Install dependencies:
pip install -r requirements.txt


Run the project:
python main.py

✅ Allow webcam access
✅ Start using pinch gestures to increase/decrease volume

Requirements
Here’s your requirements.txt (make sure to include this file):

txt
Copy code
opencv-python
mediapipe
pycaw
comtypes
numpy




