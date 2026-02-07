# ✋ Air Sketch  
## 🎨 Draw in the Air using Hand Gestures | Computer Vision Project

<p align="center">
A real-time, touch-free drawing application powered by computer vision that lets users sketch in the air using natural hand gestures and a webcam.
</p>

---

## 📌 Project Overview

**Air Sketch** is an interactive computer vision–based drawing system that allows users to draw on a virtual canvas using only their hand movements.  
By leveraging hand landmark detection and gesture recognition, the project eliminates the need for traditional input devices like a mouse, stylus, or touchscreen.

This project demonstrates practical implementation of:
- Human–Computer Interaction (HCI)
- Real-time video processing
- Gesture-based control systems

---

## ✨ Key Highlights

✔️ Real-time hand gesture recognition  
✔️ Touchless drawing experience  
✔️ Smooth and responsive air sketching  
✔️ Gesture-controlled canvas clearing  
✔️ Clean and modular Python implementation  
✔️ Beginner-friendly yet industry-relevant project  

---

## 🔥 Features

- ✋ **Hand Tracking**  
  Detects and tracks hand landmarks accurately using a webcam.

- 🤏 **Pinch-to-Draw Gesture**  
  Drawing activates when the thumb and index finger come close together.

- 🟥 **Virtual CLEAR Button**  
  Clears the entire canvas using a gesture-based interaction.

- 🎯 **Smooth Drawing Algorithm**  
  Reduces jitter by interpolating finger movements.

- 🖥️ **Touch-Free Interface**  
  No physical interaction required — fully gesture-controlled.

---

## 🧠 System Architecture & Working

### 🔹 Workflow
1. Webcam captures live video frames  
2. Frames are processed using OpenCV  
3. MediaPipe detects hand landmarks  
4. Index finger and thumb positions are tracked  
5. Distance between fingers determines pinch gesture  
6. Drawing strokes are rendered on a virtual canvas  
7. Canvas is blended with live video output  

### 🔹 Gesture Logic
- **Pinch Detected** → Drawing Mode ON  
- **Finger Movement** → Line Rendering  
- **Pinch on CLEAR Button** → Canvas Reset  

---

## 🛠️ Technology Stack

| Technology | Purpose |
|---------|--------|
| **Python** | Core programming language |
| **OpenCV** | Video capture & image processing |
| **MediaPipe** | Hand landmark detection |
| **NumPy** | Numerical operations |

---

## 🧪 Installation & Setup

### 🔹 Prerequisites
- Python 3.8+
- Webcam-enabled system
- macOS / Windows / Linux

---

### 🔹 Install Dependencies
```bash
pip install opencv-python mediapipe numpy
