# YOLOv8

YOLO stands for 'You Only Look Once', and it’s one of the most popular real-time object detection algorithms out there.

At a high level, YOLO looks at an image **once** and predicts:
- *What objects are present*
- *Where they are (bounding boxes)*
- *What class each object belongs to*

Unlike older object detection approaches that work in multiple steps, YOLO processes the entire image in a single pass. This makes it fast, efficient, and practical for real-time applications like self-driving cars, surveillance, robotics, and more. YOLOv8 is a modern and improved version that is easier to use, faster, and more flexible, which is why we’ll be exploring it here.

> Don’t worry about the internal architecture right now. The goal is to first understand *what YOLO does* and *how it thinks about images*. The details will make more sense as you experiment with it.

---

### Resources 

To build intuition, start with these in order:

#### 1. This video gives a clear, visual explanation of how YOLO works:
- https://youtu.be/ag3DLKsl2vk?si=ydjgrpnFUG-42tO8

#### 2. Once you’re comfortable with the basics, this goes a bit deeper into how YOLO functions internally:
- https://youtu.be/iy34dSwfEsY?si=OX26OYdgyhz7w4oM

#### 3. This is the official implementation and documentation:
- https://github.com/ultralytics/ultralytics
> You don’t need to understand things in the repo right now. Use it as a reference and come back to it as you progress.

#### 4. For a more visual and intuitive feel of what YOLO does:
- https://youtu.be/ag3DLKsl2vk?si=wJtPKQTYlTUUnGQJ

