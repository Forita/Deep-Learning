- Implemented a fast and accurate object detection system for self-driving vehicles using YOLO model.

- Model can detect 80 classes of objects with 5 anchor boxes.

- It run input images through a deep CNN followed by the encoding that can be seen as a grid where each cell contains information about 5 anchor boxes.

- Bouding boxes were filtered through non-max suppression. Specifically:

- Score thresholding on the probability of detecting a class to keep only accurate (high probability) boxes

- Intersection over Union (IoU) thresholding to eliminate overlapping boxes.
