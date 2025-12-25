# Deep Learning Frameworks 

Before we jump into models and architectures, let’s pause for a moment and understand **why Deep Learning frameworks exist** and **how they fit into our learning journey**.

In theory, neural networks can be implemented completely from scratch using basic Python and NumPy, Pandas and other modules. In practice, this quickly becomes slow, messy, and hard to scale. This is where **Deep Learning frameworks** come in. 

For example, something that would normally require writing multiple steps manually (forward pass, loss computation, gradient calculation, and parameter updates) might look like this in a very simplified NumPy-style approach
```python
y_pred = np.dot(x, w) + b
loss = np.mean((y_pred - y) ** 2)
grad_w = np.dot(x.T, (y_pred - y))
w = w - lr * grad_w
```
In PyTorch, the framework automatically tracks gradients for us
```python
loss = torch.nn.MSELoss()(model(x), y); loss.backward()
```
And in TensorFlow, the entire training step can be abstracted into a single call
```python
model.fit(x, y, epochs=1)
```
>Most people usually learn frameworks *after* understanding basic machine learning and neural network concepts.
So if this feels challenging, you’re wlcome to learn this after the neural networks and yolov8 portion.

---

## TensorFlow vs PyTorch 

You DO NOT need to master both. Pick ONE and stick with it.
>I would prefer TensorFlow incase you're a beginner.

#### TensorFlow
- Widely used in industry and production systems  
- Strong deployment and tooling support  
- Uses `tf.keras` for high-level model building  
- Slightly more structured

#### PyTorch
- Very popular in research and academia  
- More flexible and Python-like  
- Easier to experiment and debug  
- Great for understanding how models work internally

---
## Resources

### TensorFlow

1. **[Installation and Setup](https://youtu.be/5Ym-dOS9ssA?si=CTsliNj2tBBUwaSg)**
   - If using on local notebook/editor, use pip install tensorflow
   - If working on Colab, you can skip this.
3. **[Basics](https://youtu.be/HPjBY1H-U4U?si=5vF_loJXJ5_WBu_Q)**
4. **[Neural Networks with Sequential and Functional API](https://youtu.be/pAhPiF3yiXI?si=eHdm4MMo8DNeobbA)**
5. **[Regularization](https://youtu.be/kJSUq1PLmWg?si=9fVZYzpt2vz_x_6G)**
6. **[Model Subclassing](https://youtu.be/WcZ_1IAH_nM?si=OLhzVaXUcM9nRDVM)**
7. **[Model Saving and Loading](https://youtu.be/idus3KO6Wic?si=B-MI9bLz8XDWSExe)**
8. **[Custom Dataset for Images](https://youtu.be/q7ZuZ8ZOErE?si=y2rz5gXVsgvy2PVL)**

**[Tensorflow Official Documentation](https://www.tensorflow.org/api_docs/python/tf/keras)**

### PyTorch

1. **[Installation and Setup](https://youtu.be/2S1dgHpqCdk?si=TTSCqcKMkhonV3as)**
2. **[Basics](https://youtu.be/x9JiIFvlUwk?si=Q7kS35_anh6_ZXEH)**
3. **[Neural Networks](https://youtu.be/Jy4wM2X21u0?si=oRv-Yd2UE5l4UUO0)**
4. **[Model Saving and Loading](https://youtu.be/g6kQl_EFn84?si=2X969BBBxWl8-QjG)**
5. **[Custom Dataset for Images](https://youtu.be/ZoZHd0Zm3RY?si=7xVRiHBJedmpGNaD)**

**[PyTorch Official Documentation](https://docs.pytorch.org/tutorials/beginner/basics/intro.html)**
