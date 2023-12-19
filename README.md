# Car Counting System using YOLO and OpenCV

## Overview
This project implements a real-time car counting system using computer vision techniques. The system utilizes the YOLO (You Only Look Once) object detection model for accurate car detection and the SORT (Simple Online and Realtime Tracking) algorithm for tracking the detected cars.

## Features
- Real-time car counting
- Object detection using YOLO
- Object tracking using SORT

## Dependencies
Make sure you have the following dependencies installed:
- [Ultralytics YOLO](https://github.com/ultralytics/yolov5)
- [OpenCV](https://pypi.org/project/opencv-python/)
- [cvzone](https://github.com/cvzone/cvzone)
- [SORT (Simple Online and Realtime Tracking)](https://github.com/abewley/sort)

## How to Use
1. Clone the repository: `git clone https://github.com/your-username/your-repository.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Download the YOLO weights (`yolov8n.pt`) from [here](https://your-yolo-weights-link) and place them in the project directory.
4. Run the script: `python car_counting.py`

## Project Structure
- `car_counting.py`: Main script for the car counting system.
- `videos/cars.mp4`: Input video file for testing the system.
- `yolo-weights/yolov8n.pt`: YOLO pre-trained weights file.
- `mask.png`: Mask image for region of interest.

## Notes
- Adjust the paths and parameters in the script as needed.
- Make sure to have the necessary video file and YOLO weights before running the script.
