# Face Effect & Air Pen — Real-Time MediaPipe Tracking

An interactive real-time computer vision web application built with **Google MediaPipe Face Mesh & Hands**. Features a luminous golden cyber aesthetic inspired by Ramadan calligraphy, allowing users to draw in the air using face and hand motions.

🌟 **Live Demo:** [https://abdulmoiz0portfolio.github.io/Camera-Effect/](https://abdulmoiz0portfolio.github.io/Camera-Effect/)

---

## ✨ Features

### 👤 Face Mode (`index.html`)
- **468-Point Golden Face Mesh:** Real-time facial landmark detection with delicate golden tessellation, highlighted eyes, contours, and lips.
- **Nose Tip Motion Tracking:** Smooth pointer tracking attached to the nose tip (`landmark 4`).
- **Mouth Gesture Drawing:** Slightly open your mouth to draw hands-free in the air!
- **Mesh & Draw Toggles:** Toggle the facial mesh or drawing mode with top buttons.

### 🖐️ Hand Modes
- **Dual Control (`hand.html`):** Button toggle + double-pinch gesture to toggle drawing.
- **Pinch Only (`pinch.html`):** Natural pinch-to-draw (pinch thumb and index finger together).
- **Original Shift (`shift-original.html`):** Hold keyboard `Shift` key to draw.

---

## 🚀 How to Run Locally

```bash
# Start a local HTTP server
python -m http.server 5000
```
Open [http://localhost:5000](http://localhost:5000) in your browser and allow camera permissions.

---

## 🛠️ Built With
- **MediaPipe Face Mesh**
- **MediaPipe Hands**
- **HTML5 Canvas & Web API**
- **Vanilla JavaScript & CSS3**
