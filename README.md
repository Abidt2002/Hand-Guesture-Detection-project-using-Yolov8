# Hand-Guesture-Detection-project-using-Yolov8
This project implements a deep learning pipeline for real-time hand gesture detection using the YOLOv8 object detection framework. The dataset includes 13 hand gesture classes, with annotations provided in CSV format. The annotations were converted to YOLO format, and the model was trained and evaluated in Google Colab using Ultralytics "YOLOv8".
Features:
13 hand gesture classes
Dataset split into train, valid, test with _annotations.csv in each
CSV-to-YOLO annotation converter script
Model training using YOLOv8n in Google Colab
Visualized predictions with bounding boxes on test images
Output predictions zipped and downloadable
Optional backup of trained weights and results to Google Drive
Technologies Used:
YOLOv8 (Ultralytics)
Python, OpenCV, Pandas
Google Colab (GPU training)
Google Drive for dataset and weight storage
Dataset Format:
Hand Gestures Datset/
├── train/
│   ├── _annotations.csv
│   └── images...
├── valid/
├── test/
Each _annotations.csv follows this format:
filename,xmin,ymin,xmax,ymax,class
Goals:
Detect and localize hand gestures in images
Serve as a base for gesture control systems, sign language recognition, and AR/VR interfaces
Performance:
mAP@0.5: 93.2%
Precision: 91%
Recall: 89%

