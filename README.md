YOLO is a state-of-the-art object detection model that is fast and accurate.

It runs an input image through a CNN which outputs a 19x19x5x85 dimensional volume.

The encoding can be seen as a grid where each of the 19x19 cells contains information about 5 boxes.

You filter through all the boxes using non-max suppression. Specifically:
-Score thresholding on the probability of detecting a class to keep only accurate (high probability) boxes
-Intersection over Union (IoU) thresholding to eliminate overlapping boxes.
