# Object Detection System for Autonomous Vehicles

![image](https://www.google.com/url?sa=i&rct=j&q=&esrc=s&source=images&cd=&cad=rja&uact=8&ved=2ahUKEwi3-pr_qZrdAhUwWN8KHS5MDiEQjRx6BAgBEAU&url=https%3A%2F%2Fmedium.com%2F%40jonathan_hui%2Freal-time-object-detection-with-yolo-yolov2-28b1b93e2088&psig=AOvVaw1X0JBiGf7GOU3MsdzBLI5P&ust=1535909005700655)

- Implemented a fast and accurate object detection system for self-driving vehicles using YOLO model.

- Model can recognize 80 classes of objects.

- Model used 5 anchor boxes as bounding boxes.

- Model run input images through a deep CNN followed by the encoding that is a grid where each cell contains information about 5 anchor boxes.

- Detection accuracy was improved by filtering through all the boxes using non-max suppression. Specifically:

  - Score thresholding on the probability of detecting a class to keep only accurate (high probability) boxes

  - Intersection over Union (IoU) thresholding to eliminate overlapping boxes.
