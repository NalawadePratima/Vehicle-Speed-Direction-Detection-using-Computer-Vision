#  Vehicle Detection, Tracking & Speed Estimation using Computer Vision

##  Project Overview
This project implements a **real-time vehicle detection, tracking, and speed estimation system** using **computer vision and deep learning techniques**.  
It demonstrates two different approaches for speed calculation:
- **Pixel-based speed estimation**
- **Homography-based real-world speed estimation**

The system is designed for **traffic surveillance, intelligent transportation systems, and smart city applications**.

---

##  Key Features
- Real-time vehicle detection from video streams
- Multi-object vehicle tracking with unique IDs
- Speed estimation using:
  - Pixel displacement method
  - Homography transformation for real-world accuracy
- Supports traffic surveillance video analysis
- Well-structured and easy-to-extend codebase

---

##  Tech Stack
- **Programming Language:** Python  
- **Computer Vision:** OpenCV  
- **Deep Learning:** YOLO / PyTorch  
- **Mathematics:** Homography & Perspective Transformation  
- **Visualization:** Matplotlib  

---

  Project Structure
Vehicle-Speed-Detection/
├── notebooks/
│   ├── Vehicle_Detection_Tracking_Speed_Pixel.ipynb
│   └── Vehicle_Detection_Tracking_Speed_Homography.ipynb
│
├── train_test_dataset/
│   ├── train/
│   ├── test/
│   ├── valid/
│   └── data/
│
├── demo/
│   ├── output_video.mp4
│   └── screenshot.png
│
├── requirements.txt
├── README.md
└── .gitignore
