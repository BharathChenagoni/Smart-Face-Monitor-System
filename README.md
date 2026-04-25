 Smart Face Monitor System
(Customer Behavior & Emotion Detection using OpenCV)

 Overview
This project is a real-time computer vision system that detects human facial features and classifies behavior into:
- Happy 
- Active 
- Drowsy 

 Problem Statement
Traditional feedback systems are slow and inaccurate. This project provides real-time automated customer behavior analysis using OpenCV.

 Features
- Face Detection (Haar Cascade)
- Eye Detection (Alertness Monitoring)
- Smile Detection (Happiness Indicator)
- Real-time Behavior Classification
- Drowsiness Alert System (Beep Sound)

 Tech Stack
- Python
- OpenCV
- NumPy
- Winsound

 Working Logic
- Smile detected → Happy
- No eyes detected → Drowsy (Alert)
- Eyes detected → Active

 System Architecture
Camera → Frame Capture → Grayscale → Face Detection → Feature Detection → Behavior Classification → Output

 Results
- Real-time detection achieved
- Works best in good lighting conditions
- Effective basic emotion recognition

 Limitations
- Less accurate than deep learning models
- Sensitive to lighting
- Cannot detect complex emotions

 Future Enhancements
- Deep Learning (CNN-based emotion detection)
- Multiple emotion classification
- Dashboard integration


 Author
Bharath_Chenagoni
