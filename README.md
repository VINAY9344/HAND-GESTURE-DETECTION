Hand Gesture Recognition with Volume Control


This project implements a real-time hand gesture recognition system using OpenCV and MediaPipe. The system detects specific hand landmarks and uses gestures to control the system's audio volume dynamically.

Features
Real-Time Hand Tracking: Uses the camera feed to detect and track hand landmarks.
Volume Control: Adjusts system volume based on the distance between the thumb and index finger.
Responsive UI: Provides visual feedback for gestures, including volume level and hand landmarks.
High Performance: Optimized for real-time use with minimal latency.
Technologies Used
Python
OpenCV: For image processing and camera handling.
MediaPipe: For efficient hand landmark detection.
PyCaw: To interact with the system's audio endpoint.
NumPy: For mathematical calculations.

Usage
Launch the program and ensure your camera is accessible.
Show your hand to the camera; the application will detect and track your hand landmarks.
Adjust the system volume by moving your thumb and index finger closer or further apart.

Challenges and Learnings
Challenge: Accurate detection of hand landmarks in varying lighting conditions.
Solution: Tweaked detection confidence threshold and added robust error handling.
Learning: Enhanced understanding of image processing and real-time performance optimization.
Future Enhancements
Add gesture-based controls for additional system functions.
Integrate support for multiple hands and gestures simultaneously.
Optimize the application for lower-end systems.
