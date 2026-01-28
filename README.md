# Lane-keeping-Assist-for-ADAS
🚗 Lane Keeping Assist System (LKA)

An advanced Lane Keeping Assist (LKA) system designed as part of an ADAS (Advanced Driver Assistance System), using computer vision and deep learning techniques to detect lane boundaries, estimate vehicle deviation, and assist in keeping the vehicle centered within its lane.

The system processes real-time camera input to identify the current driving lane only, calculate lane curvature and deviation, and issue visual and audio warnings when the vehicle drifts away from the lane.

🚀 Features

Detect only the two lane lines corresponding to the vehicle’s current lane

Supports straight and curved roads

Works with solid and dashed lane markings

Lane area and path highlighted in real-time

Vehicle deviation calculation from lane center

Direction indication (Left / Right / Straight)

Visual and audio lane departure warnings

Region of Interest (ROI) optimization

Smooth and stable lane tracking

🧠 Core Functionalities

Lane detection using Computer Vision / Deep Learning

Lane center estimation

Curvature calculation

Deviation measurement

Lane departure warning logic

Direction classification

🛠️ Tech Stack

Python

OpenCV

NumPy

YOLOv8 (for lane/path detection – optional)

Deep Learning / Image Processing

Real-time video processing
