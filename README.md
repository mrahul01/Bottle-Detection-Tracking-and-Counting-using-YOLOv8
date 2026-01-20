# 🧃 Bottle Detection, Tracking, and Counting using YOLOv8

A real-time computer vision application that detects, tracks, and counts bottles in video streams using **YOLOv8** and **OpenCV**.  
The system assigns persistent IDs to each detected bottle and maintains a unique count across frames.

---

## 🔍 Key Features
- 🧠 Object detection using **YOLOv8**
- 🆔 Persistent object tracking with unique IDs
- 🔢 Accurate counting of unique bottles
- 🎥 Works on recorded video streams
- ⚡ Lightweight and real-time capable

---

## 🛠️ Tech Stack
- **Python**
- **Ultralytics YOLOv8**
- **OpenCV**
- **NumPy**

---

## ⚙️ How It Works
1. YOLOv8 detects bottles (COCO class ID: 39) in each video frame.
2. The tracking module assigns a unique ID to every detected bottle.
3. IDs are stored in a set to ensure each bottle is counted only once.
4. The total count of unique bottles is displayed in real time on the video.

---

## ▶️ How to Run
```bash
pip install ultralytics opencv-python numpy
