# 

In this assignment, you need to classify images into 2 classes using simple Neural Network.

At a high level, YOLO looks at an image **once** and predicts:
- *What objects are present*
- *Where they are (bounding boxes)*
- *What class each object belongs to*

Unlike older object detection approaches that work in multiple steps, YOLO processes the entire image in a single pass. This makes it fast, efficient, and practical for real-time applications like self-driving cars, surveillance, robotics, and more. YOLOv8 is a modern and improved version that is easier to use, faster, and more flexible, which is why we’ll be exploring it here.

> Don’t worry about the internal architecture right now. The goal is to first understand *what YOLO does* and *how it thinks about images*. The details will make more sense as you experiment with it.

---