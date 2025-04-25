🚦 Smart Traffic Management System
A real-time computer vision-based traffic management system that dynamically adjusts traffic signal timings based on vehicle density and prioritizes emergency vehicles like ambulances and fire trucks. Built using YOLOv8, OpenCV, and deep learning models for detection, classification, and intelligent decision-making.

📌 Problem Statement
Urban intersections suffer from heavy traffic congestion and fail to provide timely access for emergency vehicles due to fixed-timer-based signal systems. This project proposes a smart traffic management system that:

Dynamically allocates signal timing based on real-time traffic conditions.

Detects and prioritizes emergency vehicles.

Prevents and manages gridlock scenarios by halting traffic intelligently.


🖥️ User Interface Features
Live Traffic Feed: Real-time image/video stream from cameras.

Vehicle Count and Classification: Lane-wise detection by vehicle type.

Dynamic Signal Timing: Adaptive green/red light durations based on current conditions.

Emergency Vehicle Alerts: Detects and prioritizes ambulances, fire trucks, etc.

Congestion Warnings: Detects blockages/gridlocks and stops further traffic temporarily.


Metric | Purpose
Precision | Accuracy of emergency vehicle detection
Recall | Sensitivity in detecting actual emergency vehicles
mAP (mean Average Precision) | Overall detection quality
IoU (Intersection over Union) | Bounding box quality and overlap with ground truth


📂 Datasets Used
Traffic Detection Project Dataset: Real-time lane camera images with car, bus, cycle, and truck annotations.

Emergency vs Non-Emergency Vehicles Dataset: Labeled dataset of emergency and non-emergency vehicles.




Metric | Purpose
Precision | Accuracy of emergency vehicle detection
Recall | Sensitivity in detecting actual emergency vehicles
mAP (mean Average Precision) | Overall detection quality
IoU (Intersection over Union) | Bounding box quality and overlap with ground truth




Class | Precision | Recall | mAP50 | IoU
Car | 0.948 | 0.944 | 0.967 | 0.767
Truck | 0.896 | 0.859 | 0.903 | 0.590
Bus | 0.998 | 0.994 | 0.995 | 0.987
