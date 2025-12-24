This repository serves as a comprehensive portfolio demonstrating a
progression from classical image processing techniques to
state-of-the-art deep learning architectures. The collection explores
various methodologies for object detection, feature engineering, and
real-time video analysis using Python, OpenCV, and PyTorch.

**[Projects Overview]{.underline}**

**1. YOLO-based Real-Time Object Detection**

**Technology:** YOLOv8 (Ultralytics), OpenCV, and PyTorch.

**Description:** Implements a high-performance deep learning model to
detect and track objects in high-definition traffic videos.

**Key Features:** Utilizes the yolov8x.pt (extra-large) model for high
accuracy.

**Functionality:** Processes video frames to detect multiple
classes---including cars, trucks, airplanes, boats, and traffic
lights---while overlaying bounding boxes with real-time confidence
scores.

**2. Haar Cascade Object Detection (Video & Image)**

**Technology:** OpenCV and Haar Cascades.

**Description:** Demonstrates the classical \"Haar-like features\"
approach for object detection, specifically targeting vehicle detection.

**Video Processing:** Reads traffic footage, applies a pre-trained car
cascade (cars.xml), and exports the results as a processed AVI file.

**Image Processing:** Detects vehicles in static images using localized
feature matching and pre-trained XML classifiers.

**3. HOG (Histogram of Oriented Gradients) Feature Extraction**

**Technology:** Scikit-Image, Matplotlib, and exposure rescaling.

**Description:** A fundamental project focused on feature engineering,
demonstrating how to transform raw images into mathematical descriptors
to capture structural shapes.

**Key Features:** Visualizes gradient orientations and utilizes
intensity rescaling to improve feature visibility.

**Application:** Showcases how image data is prepared for traditional
machine learning classifiers by capturing essential silhouettes, such as
human faces.

**[Tech Stack]{.underline}**

Languages: Python.

Libraries:

OpenCV: For video/image I/O and classical detection.

Ultralytics: For deep learning inference.

Scikit-image: For image processing and feature extraction.

Matplotlib: For data visualization.
