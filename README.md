

# Non-CNN MNIST Digit Classifier



# Project Overview

In this project, I am building a MNIST digit classifier using a 4-Layer (Non-CNN) neural network to classify handwritten digits using the famous MNIST dataset. This project is an extension project from Jeremy Howard's FastAI book - [Chapter 4]([https://link-url-here.org](https://github.com/fastai/fastbook/blob/master/04_mnist_basics.ipynb)) using PyTorch. I hope that fellow FastAI students can take inspiration from my work and have a better understanding of PyTorch functions that are beneficial in model training and fundamentals of neural networks. 


## Python Packages Used
- **Data Manipulation:** `pandas, numpy` and others.
- **Data Visualization:** `matplotlib`
- **Machine Learning:** `torch, torchvision`

# Data
I used PyTorch's `torchvision.datasets` module to load in MNIST built in dataset. The MNIST dataset is widely available among machine learning frameworks including `sklearn` and `fastai`.
This dataset includes 70000 greyscaled images of handwritten digits (0-9) each of size 28x28.


# Code structure
I used a low-level approach to model training which included creating a BasicMNISTLearner PyTorch wrapper that creates a gradient descent optimizer and completes a training loop. Additional functionality for analyzing model performance include printing validation metrics (accuracy) per epoch, graphing a training loss curve and a confusion matrix on test dataset predictions. 

# Results and evaluation
After 10 training epochs we are seeing a test accuracy of 95.79% with 9579/10000 properly labeled images. 

<img width="588" alt="Screenshot 2025-04-21 at 1 30 13 PM" src="https://github.com/user-attachments/assets/fdeaf1d9-95c5-48a7-9f15-364d5d810928" />

<img width="583" alt="Screenshot 2025-04-21 at 1 30 34 PM" src="https://github.com/user-attachments/assets/6f8559ef-8e64-4438-bb4c-1f47da927806" />

# Future work
I hope to continue with more experimentation and highlight the difference between my 4 layer model and a Convolutional Neural Network. 

# Acknowledgments/References
Jeremy Howard - FastAI Course
# License
For this github repository, the License used is [MIT License](https://opensource.org/license/mit/).
