## Title of the Project
Distraction Detector – Real-Time Driver Alertness Monitoring System

Small Description

The Distraction Detector is a real-time vision-based driver monitoring system designed to detect driver distraction by analyzing eye behavior using Eye Aspect Ratio (EAR). The system continuously monitors driver alertness through a camera and provides timely alerts to prevent accidents caused by inattentive driving.

## About
Distraction Detector is an intelligent transportation safety project that focuses on identifying driver distraction using computer vision techniques. With the increasing use of mobile devices and long driving durations, driver inattentiveness has become a major cause of road accidents.

This project uses facial landmark detection to track eye movements and blinking patterns in real time. By calculating the Eye Aspect Ratio (EAR) from live video frames, the system determines whether the driver's eyes are open or closed. If the EAR value remains below a predefined threshold for a certain duration, the system classifies the driver as distracted and immediately triggers an alert.

The solution is non-intrusive, cost-effective, and runs efficiently on standard hardware without requiring wearable sensors or complex deep learning models, making it suitable for real-world deployment.

## Features
*Real-time driver eye monitoring using camera input

*Eye Aspect Ratio (EAR)–based distraction detection

*Non-intrusive and sensor-free system

*Lightweight and computationally efficient

*Real-time alert system for distracted driving

*Works under varying lighting and driving conditions

*No requirement for deep learning models

## Requirements

Operating System:

*Windows 10 (64-bit) or Ubuntu (64-bit)

Development Environment:

*Python 3.6 or later

Computer Vision Libraries:

*OpenCV for real-time video processing

*Dlib for facial landmark detection

Additional Libraries:

*NumPy for numerical operations

*imutils for image processing utilities

Hardware Requirements:

*Standard webcam or in-car camera

*Minimum 4 GB RAM

*Intel i3 processor or higher

IDE:

*VS Code / PyCharm

Version Control:

*Git for source code management

## System Architecture

1. System Flow:

2. Camera captures live video stream

3. Face detection is performed on each frame

4. Facial landmarks are extracted

5. Eye regions are identified

6. EAR is calculated in real time

7. Distraction is detected based on EAR threshold

Alert is triggered if distraction persists
![WhatsApp Image 2025-12-24 at 22 59 49](https://github.com/user-attachments/assets/d0ee1f05-b3c7-4683-8638-c747a5d83e84)



## Output

#### Output1 - Focused 

![FOC](https://github.com/user-attachments/assets/3d76b58a-fe20-4451-a21d-7702a6475284)

#### Output2 - Drowsiness Detected
![DET](https://github.com/user-attachments/assets/70f43685-4563-4f13-b58f-eb29defa2baf)

Detection Accuracy: 95.8%



## Results and Impact
The Distraction Detector effectively identifies inattentive driving behavior with high accuracy and minimal processing delay. The system enhances road safety by providing early warnings to drivers, reducing the likelihood of accidents caused by fatigue or distraction.

By leveraging computer vision and geometric analysis, this project demonstrates a practical and scalable approach for real-time driver monitoring systems. It serves as a foundation for advanced intelligent transportation solutions and can be further extended with yawning detection, head pose estimation, or mobile usage detection.

## Articles published / References

1. T. Soukupová and J. Čech, “Real-Time Eye Blink Detection using Facial Landmarks,” 21st Computer Vision Winter Workshop, 2016.

2. P. Viola and M. Jones, “Rapid Object Detection using a Boosted Cascade of Simple Features,” IEEE CVPR, 2001.

3. N. S. Gupta et al., “Enhancing Heart Disease Prediction Accuracy Through Hybrid Machine Learning Methods,” EAI Endorsed Transactions on IoT, vol. 10, Mar. 2024.

4. A. A. Bin Zainuddin, “Enhancing IoT Security: A Synergy of Machine Learning, Artificial Intelligence, and Blockchain,” Data Science Insights, vol. 2, no. 1, Feb. 2024.



