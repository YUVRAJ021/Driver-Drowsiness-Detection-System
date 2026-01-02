# Driver-Drowsiness-Detection-System
Real-time Driver Drowsiness Detection System built using OpenCV and Python. The project monitors eye closure through webcam-based face and eye detection and triggers alerts when prolonged eye closure is detected, helping improve road safety and prevent fatigue-related accidents.
# 🚗 Driver Drowsiness Detection System (OpenCV)

A real-time computer vision project that detects driver drowsiness using facial and eye detection.  
The system continuously monitors eye closure through a webcam and triggers an alert if the driver appears sleepy for a predefined duration.

---

## 🔍 Problem Statement
Driver fatigue and drowsiness are among the leading causes of road accidents.  
This project aims to improve road safety by monitoring driver alertness using computer vision techniques.

---

## 💡 Solution Overview
- Detects the driver's face and eyes in real time
- Monitors eye closure duration
- Triggers an alert if eyes remain closed beyond a threshold
- Works with a standard webcam

---

## 🛠 Tech Stack
- Python 3.13
- OpenCV
- NumPy
- Windows built-in `winsound` module

---

## ⚙️ How It Works
1. Captures live video from the webcam
2. Detects face using Haar Cascade classifier
3. Detects eyes within the face region
4. If eyes are not detected continuously:
   - Calculates eye-closure duration
   - Triggers an alert sound if threshold is exceeded

---

## 📂 Project Structure
