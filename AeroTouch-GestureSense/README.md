# GestureSense 
### A Dual-Hand Gesture-Based Laptop Controller

GestureSense is a Python-based computer vision application that allows users to control laptop brightness and system volume using hand gestures captured through a webcam.

## Features

- Control screen brightness using the left hand.
- Control system volume using the right hand.
- Increase or decrease levels using thumb-index finger distance.
- Lock individual controls by raising the corresponding pinky finger.
- Track both hands simultaneously.
- Display real-time brightness, volume and hand-detection status.

## Gesture Controls

| Gesture | Action |
|---|---|
| Pinch thumb and index finger | Decrease level |
| Spread thumb and index finger | Increase level |
| Raise pinky finger | Lock control |
| Lower pinky finger | Unlock control |

## Technologies Used

- Python
- OpenCV – Webcam access and visual interface
- MediaPipe – Real-time hand landmark detection
- NumPy – Numerical calculations and smoothing
- Pycaw – Windows system volume control
- Screen Brightness Control – Screen brightness adjustment

## Project Structure

```text
GestureSense/
│
├── combined_controller_clean.py
├── hand_landmarker.task
├── requirements.txt
└── README.md
```

## Installation

1. Clone the repository.
2. Create and activate a Python virtual environment.
3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Ensure `hand_landmarker.task` is available in the project directory.

## Run the Application

```bash
python combined_controller_clean.py
```

Press **Q** to close the application.

## Platform

Designed for Windows laptops with a webcam.

## Future Enhancements

- Gesture-based media controls.
- Customizable gesture sensitivity.
- Improved desktop interface.
- Additional accessibility features.

---

**GestureSense  — Control your laptop with gestures.**
