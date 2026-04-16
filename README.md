# Crowd Monitoring System using YOLOv8 and OpenCV

## 📌 Overview
A real-time **Crowd Monitoring System** built using **YOLOv8 and OpenCV** to detect, track, and count people from video streams.

This system enables **accurate crowd estimation and flow analysis** by detecting line crossings and displaying live **In/Out counts** on video frames.

---

## 🎯 Key Features
- 🔍 Real-time **person detection** using YOLOv8
- 🧭 **Multi-person tracking** across frames
- 📊 **Line-based counting** (In/Out flow analysis)
- 🎥 Live video annotation with bounding boxes
- ⚡ Optimized for **surveillance & crowd management scenarios**

---

## 🧠 Use Case:
- 🛕 Temple crowd monitoring

---

## 🛠️ Tech Stack
- **Python**
- **YOLOv8 (Ultralytics)**
- **Supervision (Line Zone Counting)**
- **OpenCV**
- **NumPy**

---

## 📂 Project Structure
```text
├── app.py                  # People counting script for crowd detection, tracking, and counting
├── yolov8s.pt              # YOLOv8 small model weights
├── yolov8m.pt              # YOLOv8 medium model weights
├── requirements.txt        # Python dependencies
├── temple_footage.mp4      # Sample crowd counting video
└── README.md               # Project documentation
```

---

## ⚙️ Installation

### 🔹 Prerequisites
- Python 3.8+
- pip

### 🔹 Setup
```bash
# Clone repository
git clone https://github.com/Tolety-Jayasree/Crowd-Monitoring-System.git

cd Crowd-Monitoring-System

# Create virtual environment
python -m venv venv

# Activate environment
# Windows
venv\Scripts\activate

# macOS/Linux
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

Place your input video (e.g., temple_footage.mp4) in the project directory if not already available.

Usage
Run the following command:

python app.py

The script will:

Load YOLOv8 model (e.g., yolov8s.pt or yolov8m.pt).
Detect person in each frame.
Track and count people crossing a virtual line.
Display real-time annotated output.
Press ESC to exit the video window.
```
