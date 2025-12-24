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

System Flow:

Camera captures live video stream

Face detection is performed on each frame

Facial landmarks are extracted

Eye regions are identified

EAR is calculated in real time

Distraction is detected based on EAR threshold

Alert is triggered if distraction persists
![Screenshot 2023-11-25 133637](https://github.com/<<yourusername>>/Hand-Gesture-Recognition-System/assets/75235455/a60c11f3-0a11-47fb-ac89-755d5f45c995)


## Output

<!--Embed the Output picture at respective places as shown below as shown below-->
#### Output1 - Name of the output

![FOC](https://github.com/user-attachments/assets/3d76b58a-fe20-4451-a21d-7702a6475284)

#### Output2 - Name of the output
![DET](https://github.com/user-attachments/assets/70f43685-4563-4f13-b58f-eb29defa2baf)

Detection Accuracy: 95.8%
Note: These metrics can be customized based on your actual performance evaluations.


## Results and Impact
The Distraction Detector effectively identifies inattentive driving behavior with high accuracy and minimal processing delay. The system enhances road safety by providing early warnings to drivers, reducing the likelihood of accidents caused by fatigue or distraction.

By leveraging computer vision and geometric analysis, this project demonstrates a practical and scalable approach for real-time driver monitoring systems. It serves as a foundation for advanced intelligent transportation solutions and can be further extended with yawning detection, head pose estimation, or mobile usage detection.



