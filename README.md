# 🖱️ Gesture-Controlled Air Mouse

A real-time computer vision application that transforms hand gestures into touch-free mouse controls using **Python**, **OpenCV**, and **MediaPipe**. The system enables cursor navigation, click actions, and pinch-based zooming without requiring specialized hardware—only a standard webcam.

---

## 🚀 Features

- 🖱️ Real-time cursor control using index finger tracking
- 👆 Gesture-based left click
- 🔍 Pinch gesture for zoom in / zoom out
- 🎯 Finger-state based gesture recognition
- 📈 Exponential Moving Average (EMA) smoothing for stable tracking
- 🛡️ Gesture gating and cooldown logic to reduce false activations
- ⚡ Optimized for responsive CPU-only execution

---

## 🛠️ Tech Stack

- Python
- OpenCV
- MediaPipe Tasks API
- NumPy
- PyAutoGUI
- pynput

---

## 📂 Project Structure

```
Gesture-Controlled-Air-Mouse/
│
├── AirZoom.py
├── README.md
├── requirements.txt
└── assets/
    ├── demo.gif
    └── screenshots/
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/Madhuu-k/Gesture-Controlled-Air-Mouse.git
cd Gesture-Controlled-Air-Mouse
```

Install dependencies

```bash
pip install -r requirements.txt
```

Download the MediaPipe Hand Landmarker model (`hand_landmarker.task`) and update the model path inside `AirZoom.py`.

Run the project

```bash
python AirZoom.py
```

---

## ✋ Supported Gestures

| Gesture | Action |
|---------|--------|
| ☝️ Index Finger | Cursor Movement |
| 👆 Fold Index Finger | Left Click |
| 👍 + ☝️ Pinch | Zoom In / Zoom Out |

---

## ⚡ Key Highlights

- Real-time hand landmark detection using the MediaPipe Tasks API
- Finger-state analysis based on landmark geometry
- EMA smoothing for stable cursor movement
- Adaptive thresholding to reduce unintended gestures
- CPU-only implementation with responsive performance

---

## 📸 Demo

> Add a GIF or screen recording here.

Example:

```
assets/demo.gif
```

---

## 📌 Future Improvements

- Right Click
- Drag & Drop
- Scrolling
- Multi-monitor support
- Custom gesture mapping
- Dynamic sensitivity controls

---

## 👨‍💻 Author

**Madhu Sudhan Rao**

- GitHub: https://github.com/Madhuu-k
- LinkedIn: https://linkedin.com/in/madhu-m-k
