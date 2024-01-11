# CarCounter - Object-Detection
# Traffic Monitoring System with YOLO Object Detection 
This Python script combines the power of YOLO (You Only Look Once) object detection and SORT (Simple Online and Realtime Tracking) algorithm to create a real-time traffic monitoring system. The system processes a video feed, detects vehicles using YOLO, and tracks their movement with SORT. Additionally, it provides a count of vehicles crossing a specified region of interest.

#### Key Features:
- YOLO integration for robust vehicle detection.
- SORT algorithm for online tracking of detected vehicles.
- Utilizes Kalman filtering for smooth and accurate object tracking.
- Region of Interest (ROI) specified with limits for counting vehicles.
- Visual feedback with bounding boxes, unique IDs, and real-time count display.
- Customizable classes for filtering specific types of objects (e.g., cars, buses, trucks).

#### How to Use:
- Install the required dependencies (ultralytics, opencv, cvzone, and sort).
- Download YOLO weights and update the model = YOLO("path/to/yolov8l.pt") line.
- Adjust the video source (cap = cv2.VideoCapture("path/to/video.mp4")) if needed.
- Customize the region of interest limits and object classes as per your requirements.
- Run the script and monitor real-time vehicle tracking and counting.


This project serves as a starting point for building intelligent traffic monitoring systems, with the flexibility to extend functionalities and adapt to specific use cases. Feel free to explore, modify, and contribute to enhance its capabilities!
