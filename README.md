# Lab-1
AIDI 2004 Lab 1. Basics of Github

Basics of Git and Github
Basic of GitBash

Adding a file, Adding a branch
Adding a python code file. 

Python Code details
1.	Build and save an object classification model for CIFAR-10 dataset following the below step. [This dataset is already available in Keras library]

I.	Write a small description about this dataset.
II.	Design the CNN architecture as below:
Hidden layer1
CONV1a
Filter size=3 x 3 #filter = 32 Padding= same Activation= relu
Kernel_initializer=he_uniform CONV1b
Filter size=3 x 3 #filter = 32 Padding= same Activation= relu
Kernel_initializer=he_uniform POOL1
Max Pooling Pool_size = 2 x 2


Hidden layer2
CONV2a
Filter size=3 x 3 #filter = 64 Padding= same Activation= relu
Kernel_initializer=he_uniform CONV2b
Filter size=3 x 3 #filter = 64 Padding= same Activation= relu
Kernel_initializer=he_uniform POOL2
Max Pooling Pool_size = 2 x 2 

Hidden layer3
CONV3a
Filter size=3 x 3 #filter = 128 Padding= same Activation= relu
Kernel_initializer=he_uniform CONV3b
Filter size=3 x 3 #filter = 128 Padding= same Activation= relu
Kernel_initializer=he_uniform POOL3
Max Pooling Pool_size = 2 x 2


Fully connected layer Number of neurons= 128 Activation= relu Kernel_initializer=he_uniform


III.	Use a stochastic gradient descent with learning rate of 0.001, momentum=0.9
IV.	Use a batch_size= 32, epochs=10
V.	Save the model
VI.	Find the accuracy of the model from your saved model file.
VII.	Make prediction using the given sample image.

