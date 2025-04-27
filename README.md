# -Human-Detection-Counting-Project-Using-Machine-Learning
This project focuses on detecting and counting the number of humans present in images and real-time video streams using machine learning and computer vision techniques. We use pre-trained models combined with OpenCV to detect humans, draw bounding boxes, and maintain a live count.
 We used Real-time human detection from webcam or video files. Accurate people counting with dynamic display on frames. Handles challenges like occlusion and lighting variations. Supports multiple detection models (HOG + SVM, YOLOv5, Haar Cascades, etc.). Easy-to-use Python scripts for quick testing and deployment.
We generally used different types of technology stack in this project Python: OpenCV, Machine Learning (HOG + SVM, optionally YOLOv5), NumPy, Matplotlib (for visualization)
We generally used different dataset in this project: Pre-trained models used: (example: HOG + SVM people detector, YOLOv5 model trained on COCO dataset)
No custom dataset was required unless training from scratch.
It genreally works: Capture video frame-by-frame using OpenCV. Apply human detection using machine learning model, Draw bounding boxes around detected humans, Count the number of detected humans and display the count on screen.
It gives results: Detection Accuracy: ~90% in simple environments.
Real-time processing speed: ~20-25 FPS (depending on hardware and model used).



