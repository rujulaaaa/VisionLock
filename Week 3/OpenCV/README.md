# Image Preprocessing – OpenCV

Before we feed images to any deep learning model, we need to make sure the images are in a form that the model can actually learn from. Raw images straight from a camera or dataset are often noisy, inconsistent in size, or poorly structured and that can hurt performance badly. Techniques include resizing, normalization, noise reduction, and augmentation. These steps standardize inputs, improve feature extraction, and increase dataset diversity, leading to more robust and efficient neural network training and performance.

---

## Why OpenCV?

Frameworks like TensorFlow and PyTorch do provide basic image preprocessing utilities (resizing, normalization, simple augmentation, etc.), and those are perfectly fine for **simple datasets**.

However:
- OpenCV is built **specifically for computer vision**
- It is faster, more flexible, and more powerful
- It allows advanced image manipulation that frameworks don’t easily support

Use framework-based preprocessing for simple tasks.  
Use **OpenCV** when you need deeper control over image quality and structure.

---

> **Tip:** All the videos for this section can be comfortably watched at **2× speed**.

---

## Basics

In computer vision and deep learning, an image is usually represented as a NumPy array.

- Each value in the array represents a pixel
- Pixel values typically range from 0 to 25 and indicate the intensity of the colour
- This representation allows efficient manipulation using NumPy's prevalent operations

**[What is Image?](https://youtu.be/oUJs03eZ0S8?si=bi_RGIS0kFu0FBPl)**
**[Image Reading](https://youtu.be/wRtAoZF50Jc?si=mvJ0XRC3_y9pu1Xt)**

---

## Color Channels

For a grayscale image, it's a 2D array with dimensions (height, width), and for a color image, it's a 3D array with dimensions (height, width, channels), where channels typically represent RGB values.

The channels usually represent color information.

- **[BGR2GRAY](https://youtu.be/AFrZ3JOQ0Qg?si=ldXZi_9lWMnNllQX)**
- **[BGR Channels](https://youtu.be/wlH9w1eA6PQ?si=MMQtTz5thDBx1ti7)** 
- **[BGR vs RGB](https://youtu.be/kSqxn6zGE0c?si=iPLH0e_4wMVLkjNL)**  (9:41 to 11:50)
- **[HSV](https://youtu.be/eDIj5LuIL4A?si=35pIEMfa7WdusXg8)**  (2:09:31 to 2:29:00)

---

## Playing with Images

Before feeding images into a model, we often modify them by cropping, resizing, rotating and flipping them to:
- Standardize input sizes
- Enhance model training
- Augmenting data

You’ll experiment with:
- **[Resizing](https://youtu.be/DPkpI2ezVO4?si=pyyyv8RvYGDFC0x2)**
- **[Flipping](https://youtu.be/Y_78ARbpSwo?si=WVN0pdaiCTV8x3nz)**
- **[Cropping](https://youtu.be/fanEPKLRbPk?si=k96NIEFCzHDSWgfj)**
- **[Rotation](https://youtu.be/MtHvL1emJSE?si=4s_HrQP9-W9MB9IK)**
- **[Drawing shapes and bounding boxes](https://youtu.be/shfXj_Og7ak?si=6WpD2tRN0c-8VFhr)** 

---

## Blurring and Noise Removal

Real-world images often contain noise, which is nothing but random variations that doesn’t carry useful information.

### Why blur images?
- Reduces unwanted noise
- Smoothens images
- Helps models focus on important structures

**[Blurring](https://youtu.be/eDIj5LuIL4A?si=WUT2V_Ec8uqfDBHq)** (51:39 to 1:07:00)

---

## Thresholding and Edge Detection

### Thresholding

Thresholding converts grayscale images into binary by setting pixel intensity limits. This simplifies images and makes structure more obvious.

### Edge Detection
Edge detection techniques (like Canny or Sobel) highlight boundaries in images which are nothing but places where pixel intensity changes sharply.

These edges often correspond to:
- Object boundaries
- Shape outlines
- Important visual features

**[Threshold and Edge Detection](https://youtu.be/eDIj5LuIL4A?si=vo_pEGwp-8M4OBxV)** (1:07:06 – 1:31:30)

---

## Contours

### What are Contours?
Contours are curves that join continuous points along the boundary of an object. They help represent the shape and structure of objects in an image.

Contours are useful for:
- Object detection
- Shape analysis
- Recognition tasks

### Edge Detection vs Contours
- **Edge detection** finds abrupt changes in brightness
- **Contours** use those edges to form meaningful object boundaries

**[Contours Detection](https://youtu.be/eDIj5LuIL4A?si=RG0nvkdy6PpHn8xl)** (1:45:17 – 2:01:20)

---

## Image Saving

After processing images, it’s very important to save them properly.

**[Image Saving](https://youtu.be/b_vVNCVDrbw?si=NKHkfrpNOGOx5z7t)** 


