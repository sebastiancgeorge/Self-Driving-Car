# 🚗 Self-Driving Car Vision System

A modular, open research project focused on building a **vision-based perception system** for self-driving cars — starting from raw dashcam footage and iteratively progressing toward lane detection, object detection, tracking, and semantic understanding of driving scenes.

---

## 🎯 Project Goal

To develop a prototype vision pipeline that enables a self-driving agent to:
- Understand road environments visually
- Detect and track lanes and objects
- Make foundational decisions based on sensory input
- Expand into localization, SLAM, and behavior modeling

---

## 🧱 Phase-wise Development Roadmap

### ✅ Phase 0: Setup
- Organize dataset from dashcam footage
- Build utility tools for frame extraction and annotation
- Set up project structure and environment

### 🛣️ Phase 1: Classical Lane Detection
- Edge detection using Canny
- Region of Interest (ROI) masking
- Hough Transform-based lane line extraction

### 🧠 Phase 2: Object Detection
- Integrate YOLOv8 for detecting vehicles, pedestrians, signals
- Visualize object classes and confidence scores on video frames

### 🔁 Phase 3: Object Tracking
- Add Deep SORT for consistent object IDs
- Track vehicle positions and movements over time

### 🧠 Phase 4: Deep Learning-based Lane Detection
- Add UltraFast Lane Detection or LaneNet
- Support for curved lanes and complex road layouts

### 🧪 Phase 5: Real-World Dataset & Training
- Annotate custom driving footage
- Fine-tune detection and segmentation models

---

## 🧰 Tech Stack

- Python 3.10+
- OpenCV
- YOLOv8 (Ultralytics)
- Deep SORT
- Torch / TensorFlow (for deep lane models)
- Matplotlib, NumPy, tqdm

---

## 📂 Project Structure

self-driving-vision/ │
├── data/ # Raw videos and extracted frames 
├── notebooks/ # Dev and visualization notebooks 
├── models/ # Pretrained weights 
├── utils/ # Preprocessing and visualization tools 
├── detectors/ # Lane and object detection modules 
├── tracker/ # Object tracking components 
├── main.py # Main pipeline runner 
├── requirements.txt 
└── README.md


---

