- Implemented a fast and accurate object detection system for self-driving vehicles using YOLO model.

- Model can recognize 80 classes of objects.

- Model used 5 anchor boxes as bounding boxes.

- Model run input images through a deep CNN followed by the encoding that is a grid where each cell contains information about 5 anchor boxes.

- Detection accuracy was improved by filtering through all the boxes using non-max suppression. Specifically:

-- Score thresholding on the probability of detecting a class to keep only accurate (high probability) boxes

-- Intersection over Union (IoU) thresholding to eliminate overlapping boxes.
