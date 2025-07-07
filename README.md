AI-Powered Parking Space Detection System 

This project implements an AI-powered parking space detection system using YOLOv8, OpenCV, and Python. It detects and tracks parked vehicles in a video stream and highlights which parking spaces are occupied or free in real-time. This helps optimize urban parking and aids in smart city initiatives.

 Features
   Real-time vehicle detection using YOLOv8
   Custom-defined parking zones using mouse-drawn polylines
   AI-based detection of occupied vs empty spaces
   Dynamic frame processing for optimized performance
   Easy-to-use interface with visual feedback (green = free, red = occupied)
   Saves parking area layout using Pickle

📂 parking-space-detection/
├── test1.py               # Script to draw and save parking regions
├── test2.py               # Main detection script using YOLO
├── freedomtech            # Pickle file with saved parking layout
├── easy.mp4               # Sample parking video
├── coco.txt               # COCO class labels (used by YOLO)

 Technologies Used
    Python
    OpenCV
    YOLOv8 (ultralytics package)
    NumPy
    Pickle (for layout saving)
    Pandas (for frame data processing)

🚀 Getting Started

1. Install Thonny
   Download from https://thonny.org and install.

2. Create Project Folder
   Place these files in one folder:
   test1.py, test2.py, easy.mp4 (video), coco.txt (YOLO labels)

3. Install Required Libraries
   In Thonny:
   Go to Tools → Manage packages
    
    Install:
    opencv-python
    numpy
    cvzone
    ultralytics 
    pandas
  Or use Shell:
    pip install opencv-python numpy cvzone ultralytics pandas
 4. Run test1.py
    Draw parking zones with the mouse.
    Press s to save, q to quit.

 5. Run test2.py
    Starts detection using YOLO.

    Shows occupied (red) and free (green) spaces.

    📈 Future Enhancements
        Integrate with web dashboard for live monitoring.
        Store logs and analytics for parking trends.
        Add camera calibration for better zone alignment.
