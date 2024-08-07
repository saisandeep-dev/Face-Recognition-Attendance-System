# Face Recognition Attendance System

## Overview
The Face Recognition Attendance System is a Python-based application that automates attendance tracking using facial recognition technology. It leverages the face_recognition library for face detection and recognition, and OpenCV for image processing.

## Features
- Real-time Face Recognition: Automatically recognizes faces from a webcam feed.
- Attendance Tracking: Records attendance by matching recognized faces with a pre-defined list.
- CSV Report Generation: Generates an attendance report in CSV format.

## Requirements
- Python 3.6+
- OpenCV: For video capture and image processing.
- face_recognition: For face detection and recognition.
- numpy: For numerical operations.
- pandas: For generating CSV reports.

## Troubleshooting
- Face Not Recognized: Ensure that the images in the known_faces directory are clear and taken under similar lighting conditions to those of the live feed.
- Webcam Not Working: Check that the correct camera index is set in config.py and that the webcam is connected properly.

## Advantages
- **Increased Accuracy**: Reduces errors associated with manual attendance marking by automating the recognition process.
- **Efficiency**: Speeds up the attendance process by eliminating the need for manual entry.
- **Real-time Monitoring**: Provides immediate feedback and records attendance in real-time.
- **Scalability**: Can be used in various environments, including classrooms, offices, and events, with minimal adjustments.
- **Reduced Human Error**: Minimizes the risk of errors that can occur with manual attendance systems.

## References
- Build Face Recognition Attendance System Using Python: This article provides a comprehensive guide to building a face recognition-based attendance system using Python.

