# Object Detection System for Autonomous Vehicles

![Image of carDetection](https://www.google.com/url?sa=i&rct=j&q=&esrc=s&source=images&cd=&cad=rja&uact=8&ved=2ahUKEwikqpCJqZrdAhXyct8KHazgBMgQjRx6BAgBEAU&url=https%3A%2F%2Ftowardsdatascience.com%2Fyolo-v3-object-detection-53fb7d3bfe6b&psig=AOvVaw1X0JBiGf7GOU3MsdzBLI5P&ust=1535909005700655)

- Implemented a fast and accurate object detection system for self-driving vehicles using YOLO model.

- Model can recognize 80 classes of objects.

- Model used 5 anchor boxes as bounding boxes.

- Model run input images through a deep CNN followed by the encoding that is a grid where each cell contains information about 5 anchor boxes.

- Detection accuracy was improved by filtering through all the boxes using non-max suppression. Specifically:

  - Score thresholding on the probability of detecting a class to keep only accurate (high probability) boxes

  - Intersection over Union (IoU) thresholding to eliminate overlapping boxes.
