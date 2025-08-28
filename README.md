## 📸 Example Output

![Output Example](Screenshot%202025-08-28%20183553.png)


# Real-Time Object & Face Detection with Distance Estimation

This project demonstrates **real-time object detection, face detection, and distance estimation** using OpenCV, Haarcascade, and SSD MobileNet v3.  
It can also estimate the distance between two detected objects using Euclidean distance.

---
## 📌 Features

✅ Real-time **object detection** using SSD MobileNet v3  
✅ Real-time **face detection** using Haarcascade  
✅ **Camera-to-object distance estimation** (Focal Length Method)  
✅ **Object-to-object distance calculation** (Euclidean Distance)  
✅ Visualization with bounding boxes, labels, and warnings (e.g., *MOVE AWAY!!*)  

---
## 🚀 Getting Started

### 1. Create Virtual Environment
```bash
python -m venv venv
venv\Scripts\activate
pip install opencv-python numpy scipy
```
###▶️ Run the Project
```bash
python objectdetect.py
