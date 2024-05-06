# CAM-YOLO

This is a Two-stage model used to detect house numbers on mailbox in street view images. It uses Class Activation Map (CAM) for regional proposal generation and pre-trained YOLOv3 fine-tuned on the Street View House Number (SVHN) dataset for number detections.

## Example Detection

Please check out 'CAM+YOLOv3.ipynb' notebook for implementation and more visualization.

![Example1](example1.png)

## Resources and References

- **YOLOv3 Implementation**: The pre-trained YOLOv3 used is from Ultralytics. Visit their GitHub repository [here](https://github.com/ultralytics/yolov3) for more information.

- **Class Activation Mapping (CAM)**: The CAM implementation and visualization are adapted from [this GitHub repository](https://github.com/JimEverest/CAM) by Jim Everest.

- **Dataset**: Street View House Number (SVHN) dataset (format 1) used is from [here](http://ufldl.stanford.edu/housenumbers/).

- **Image Source**: Image examples used are from Google Street View and are **only for visualization purposes**.
