# Convolutional Neural Network (CNN)

In the previous week, we learned about **Neural Networks** and how they model relationships in data using layers of neurons.  
This week, we move one step further and study a specialized and extremely powerful class of neural networks known as **Convolutional Neural Networks (CNNs)**.

Convolutional Neural Networks are primarily designed to work with **visual data** such as images and videos. They are especially effective at automatically learning spatial features like edges, textures, and shapes, which makes them the backbone of modern computer vision systems.

---

## What is a Convolutional Neural Network?

A **Convolutional Neural Network (CNN)** is a type of deep learning model that uses **convolution operations** to extract meaningful features from input data.  
CNNs leverage concepts from **linear algebra** and **signal processing** to detect patterns and hierarchies in data.

While CNNs are most commonly applied to images, they can also be adapted for:
- Audio signals
- Time-series data
- Medical scans
- Video processing

Because of their ability to preserve spatial relationships, CNNs outperform traditional neural networks on most vision-related tasks.

---

## CNN Architecture

A typical Convolutional Neural Network is composed of three main types of layers:

### 1. Convolutional Layer
This layer applies filters (kernels) to the input image to extract features such as edges, corners, and textures.

### 2. Pooling Layer
Pooling layers reduce the spatial dimensions of feature maps, helping:
- Reduce computation
- Control overfitting
- Retain the most important features

### 3. Fully Connected Layer
These layers perform final classification or regression by combining the extracted features.

To understand these layers in more depth, refer to the **theory section** provided with this module.

---

## How Does a CNN Work?

Before implementing CNNs in applications, it is important to understand how information flows through the network.

A CNN:
1. Takes an image as input
2. Applies convolution operations to detect low-level features
3. Gradually builds higher-level representations
4. Uses fully connected layers to make predictions

To build intuition:
- Watch the introductory video
- Read through the provided theory material for deeper insights

---

## Maths Behind CNNs

CNNs rely heavily on mathematical concepts such as:
- Convolution operations
- Matrix multiplication
- Dot products
- Gradient-based optimization

To gain a stronger mathematical understanding of CNNs, you can refer to the following resources:

- **Video 1**
- **Playlist**

These resources explain the math intuitively and visually, making it easier to grasp how CNNs learn.

---

Happy Learning! 🚀
