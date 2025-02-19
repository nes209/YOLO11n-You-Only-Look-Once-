# YOLO Real-Time Object Detection with Webcam
This project uses YOLO to detect objects in real time using a webcam. Ultralytics YOLO and OpenCV were used to capture video from the webcam and process it to identify detected objects in each frame.

## Main functions:
- Open webcam: Open webcam to capture real-time video.
- Object detection: Detect objects using trained YOLO models.
- Supported model types:
- `yolo11n-obb.pt`: Detect objects using oblique bounding boxes.
- `yolo11n.pt`: Generic YOLO object detection model.
- `yolo11n-cls.pt`: Detect objects with object classification.
- `yolo11n-seg.pt`: Detect objects with image segmentation.
- `yolo11n-pose.pt`: Detect pose estimation.

  ## Requirements:

- Python 3.x
- OpenCV for video and image processing.
- Ultralytics YOLO: to use the trained model for object detection.
