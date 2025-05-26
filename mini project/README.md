# 🎨 Air Canvas - Virtual Drawing App with Hand Gestures

## 🧠 Problem Statement
Allow users to draw on a virtual canvas using their hand gestures captured via webcam — no touch or mouse input needed!

## 🔍 Approach & Solution
Using real-time computer vision techniques with **MediaPipe** and **OpenCV**, the application detects hand landmarks and tracks the index fingertip to simulate drawing. Gesture-based interactions allow users to change colors, erase, and more.

## ✨ Features
- Draw using index finger
- Change brush color using gestures
- Erase or clear the canvas
- Save your creation as an image
- Real-time hand tracking via webcam

## 🛠 Tech Stack
- Python
- OpenCV
- MediaPipe
- NumPy

## 🖼 Screenshots

| Drawing Mode | Color Selection |
|--------------|------------------|
| ![](screenshots/tools.png) | ![](screenshots/tools.png) |

## ▶️ Run Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/sakshibirajdar09/air-canvas.git
cd air-canvas
