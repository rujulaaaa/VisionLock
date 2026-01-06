# Convolutional Neural Network (CNN)


In the previous week, we learned about Neural Networks and how they model relationships in data using layers of neurons. This week, we move one step further and study a specialized and extremely powerful class of neural networks known as Convolutional Neural Networks (CNNs).

Convolutional Neural Networks are primarily designed to work with visual data such as images and videos. They are especially effective at automatically learning spatial features like edges, textures, and shapes, which makes them the backbone of modern computer vision systems.

---

## What is a Convolutional Neural Network?

A Convolutional Neural Network (CNN) is a type of deep learning model that uses convolution operations to extract meaningful features from input data. CNNs leverage concepts from linear algebra and signal processing to detect patterns and hierarchies in data.

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

To understand these layers in more depth, refer to the **[theory](https://medium.com/latinxinai/convolutional-neural-network-from-scratch-6b1c856e1c07)** provided with this module.

---

## How Does a CNN Work?

This **[video](https://youtu.be/zfiSAzpy9NM?si=WieIUoeame_djbb9)** provides an intuitive introduction to how Convolutional Neural Networks work, explaining the core ideas behind convolution, feature extraction, and hierarchical learning in images. It focuses on building visual and conceptual intuition rather than heavy mathematics, making it ideal for beginners starting with CNNs.

Go through this **[theory](https://medium.com/thedeephub/convolutional-neural-networks-a-comprehensive-guide-5cc0b5eae175)** to get some more insights.

---

## Maths Behind CNNs

To gain a stronger mathematical understanding of CNNs, you can refer to the following resources:

- **[Video 1](https://youtu.be/Lakz2MoHy6o?si=I7x6HDaWkt-jmbuX)**
- **[Playlist](https://youtube.com/playlist?list=PLuhqtP7jdD8CD6rOWy20INGM44kULvrHu&si=0F57CDqjnL1c2cJt)**

These resources explain the math intuitively and visually, making it easier to grasp how CNNs learn.

