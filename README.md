# 🎯 Real-Time Color Detection using OpenCV

This project uses **OpenCV** and **Python** to detect a specific color in real-time using your webcam. Once detected, the colored object is highlighted with a green rectangle.

---

## 🚀 Features

- Live webcam feed
- Detects specific color (default: Yellow)
- Highlights the object with a bounding box
- Easily customizable for any color

---

## 🧠 How It Works

1. The script converts each video frame from BGR to HSV color space.
2. It uses HSV limits to create a mask.
3. Using that mask, it checks where the selected color exists.
4. If detected, it draws a green rectangle around the colored object.

---

## 🔧 Requirements

- Python 3.7+
- OpenCV
- Pillow (for bounding box logic)

Install dependencies:

```bash
pip install opencv-python pillow numpy
