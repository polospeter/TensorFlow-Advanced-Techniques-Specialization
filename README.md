# TensorFlow-Advanced-Techniques-Specialization

This repository will contain my solutions for the Tensorflow: Advanced Specialization course on Coursera.  

## Course 1: Custom Models,Layers, and Loss Functions with Tensorflow

This first course introduces you to Tensor Flow, a popular machine learning framework. You will learn how to build a basic neural network for computer vision and use convolutions to improve your neural network.

\underline{#### Week 1: A New Programming Paradigm}
Compare how the Functional API differs from the Sequential API, and see how the Functional API gives you additional flexibility in designing models. Practice using the functional API and build a Siamese network!

Good article describing the different versions of the Inception network:  
https://towardsdatascience.com/a-simple-guide-to-the-versions-of-the-inception-network-7fc52b863202

Papers about the Siamese network:  
http://yann.lecun.com/exdb/publis/pdf/chopra-05.pdf  
http://slazebni.cs.illinois.edu/spring17/lec09_similarity.pdf

Assignment: Multiple Output Models using Keras Functional API

#### Week 2: Custom Loss Functions
Loss functions help measure how well a model is doing, and are used to help a neural network learn from the training data. Learn how to build custom loss functions, including the contrastive loss function that is used in a Siamese network.


#### Week 3: Custom Layers
Custom layers give you the flexibility to implement models that use non-standard layers. Practice building off of existing standard layers to create custom layers for your models.


#### Week 4: Custom Models
Loss functions help measure how well a model is doing, and are used to help a neural network learn from the training data. Learn how to build custom loss functions, including the contrastive loss function that is used in a Siamese network.


## Course 2: Custom and Distributed training with Tensorflow

#### Week 1: Differentiation and Gradients
This week, you will get a detailed look at the fundamental building blocks of TensorFlow - tensor objects. For example, you will be able to describe the difference between eager mode and graph mode in TensorFlow, and explain why eager mode is very user friendly for you as a developer. You will also use TensorFlow tools to calculate gradients so that you don’t have to look for your old calculus textbooks next time you need to get a gradient!

Learning Objectives:

-Use various TensorFlow functions to create tensor objects  
-Describe the difference between graph-based execution and eager execution in TensorFlow  
-Use TensorFlow’s GradientTape to calculate derivatives of loss functions  



Reference: CNN for visual recognition https://cs231n.github.io/neural-networks-3/#summary

#### Week 2: Custom Training
This week, you will build custom training loops using GradientTape and TensorFlow Datasets. Being able to write your own training loops will give you more flexibility and visibility with your model training. You will also use a function to calculate the derivatives of functions so that you don’t have to look to your old calculus textbooks to calculate gradients.

Learning Objectives:

-Define the steps in a custom training loop  
-Implement custom training loops using GradientTape  
-Implement a custom training loop with data from TensorFlow Datasets  
