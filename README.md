# Malpractice Detection in Examination Halls

**Overview**

This project is a prototype that detects malpractice in examination halls using computer vision techniques. The prototype works with a webcam, while the real implementation is designed to work with CCTV cameras for large-scale monitoring. It utilizes MediaPipe, OpenCV, and YOLO to track eye movements, gaze direction, and hand gestures. The system alerts invigilators when suspicious activities, such as looking away or attempting to communicate, are detected.

**Features**

*Gaze Detection*: Identifies if students are looking at each other using gaze direction lines.
*Eye Movement Sensitivity*: Increased accuracy in detecting side glances and prolonged distractions.
*Hand Mesh and Object Detection*: Detects if a student is holding an unauthorized object.
*Hand Covering Face Detection*: Detects if a student is covering their mouth or eyes, possibly indicating communication.
*Real-time Alerts*: Displays messages only when a malpractice scenario is detected.

**Technologies Used**

Python
OpenCV
MediaPipe
YOLO (for object detection)
NumPy

**Installation**

*Clone the repository:*

git clone https://github.com/your-username/malpractice-detection.git
cd malpractice-detection

*Install dependencies:*

pip install -r requirements.txt

*Run the detection script:*

python main.py

**Usage**

Ensure the webcam is properly connected.
The system will track eye movements and hand gestures in real-time.
Alerts will be triggered when malpractice is detected.

**Future Enhancements**

Better Object Recognition: Improve YOLO’s accuracy in detecting unauthorized items.
Adaptive Alert System: Reduce false positives by incorporating machine learning.
Integration with CCTV Feeds: Extend the system to work with multiple cameras in an exam hall.

**Contributing**

Contributions are welcome! Please submit a pull request or open an issue for discussion.

**License**

This project is licensed under the MIT License.

**Acknowledgments**

Special thanks to the open-source contributors of MediaPipe, OpenCV, and YOLO for their powerful tools that made this project possible.

