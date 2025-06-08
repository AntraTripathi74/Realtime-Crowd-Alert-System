# 🚨Real-Time Stream Simulation & Crowd Alert System 
This project focuses on simulating a live video stream to perform real-time object detection, specifically focusing on identifying and alerting for crowd occurrences. Leveraging modern YOLO models, it processes video frames, counts detected individuals, and triggers customizable alerts based on sustained crowd presence.

### ✨ Features
* Video Stream Simulation: Simulates a continuous video stream by processing frames from an .mp4 file using OpenCV.
* Intelligent Frame Sampling: Performs object detection on every 3rd frame to balance performance and detection frequency.
* YOLO-Powered People Detection: Integrates with a state-of-the-art YOLO (v8/v9) model to accurately identify and count people within each processed frame.
* Event-Driven Alerting: Triggers a "Crowd Detected" alert if 3 or more people appear in 5 consecutive frames, ensuring robust detection of sustained crowd presence.
* Comprehensive Alert Logging: Logs all triggered alerts with precise timestamps, frame numbers, and detection details into a .json file for easy review and analysis.
* Alert Timeline Visualization: Generates a visual timeline plot of alert occurrences, providing a clear overview of when and how often crowd events were detected during the simulation

### Dataset Used: <a href=https://www.kaggle.com/datasets/jayitabhattacharyya/social-distance> Kaggle</a>
