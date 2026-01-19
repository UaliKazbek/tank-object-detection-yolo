# Tank Object Detection (YOLOv8)

Object detection project for detecting tanks in game footage using YOLOv8.

## Task
Detect tanks in images and videos.

## Model
- YOLOv8n
- Ultralytics
- PyTorch

## Dataset
- Custom dataset in YOLO format
- Images collected from gameplay footage
- Single class: tank
- Train / Test
- this dataset - https://www.kaggle.com/datasets/ualikazbek/tank-detection-yolo

## Training
```bash
yolo detect train model=yolov8n.pt data=data.yaml imgsz=640 epochs=50 batch=16 workers=0
