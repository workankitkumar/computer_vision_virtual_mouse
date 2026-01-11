# Virtual Mouse Using Computer Vision 🖱️📷

A computer vision–based virtual mouse that allows users to control the mouse cursor using hand gestures captured through a webcam. This project eliminates the need for a physical mouse by leveraging real-time hand tracking.

## Features
- Control mouse cursor movement using hand gestures
- Left-click and right-click using finger gestures
- Real-time hand tracking with high accuracy
- No additional hardware required (only a webcam)
- Smooth and responsive cursor control

## Technologies Used
- Python
- OpenCV
- MediaPipe
- PyAutoGUI
- NumPy

## How It Works
1. The webcam captures real-time video frames.
2. Hand landmarks are detected using MediaPipe.
3. Specific finger gestures are mapped to mouse actions.
4. Cursor movement and clicks are performed using PyAutoGUI.

## Gestures Supported
- **Move Cursor:** Index finger movement
- **Left Click:** Index finger + thumb
- **Right Click:** Index finger + middle finger
- **Scroll (optional):** Hand movement up/down

## Installation
```bash
pip install opencv-python mediapipe pyautogui numpy
