# Assignment: week 3

## Objectives

The objectives of this assignment are:
1.	to work with image data
2.	to experiment with pretrained convnets

## Setup

Use the same CIFAR-10 dataset as in the course material [notebook](../ConvNets.ipynb). The data is also directly available in Keras: [https://keras.io/api/datasets/cifar10/](https://keras.io/api/datasets/cifar10/).

## Task

In the course material, a simple convolutional neural network is built, trained and tested to solve the multiclass classification task presented by the CIFAR-10 dataset. For this assignment, you should experiment with pretrained models. You can follow the instructions in Chollet's book "Deep Learning with Python", 3rd edition, Chapter 8 (Image classification): _Using a pretrained model_. With one of the pretrained ConvNet models available with Keras, you can preprocess the original images to a new representation. For this modified input data, you should build a simple fully connected classifier, train it, and test it.

Prepare a Jupyter notebook containing an account of the problem treatment. Note the following:

- You should arrange the available data into training, validation, and test sets.

- Pick a suitable convolutional base (e.g. VGG16), and load it without the Dense classifier top. Freeze the weights of the convolutional base.

- Use the convolutional base to preprocess the images into a suitable representation (see _"Fast feature extraction without data augmentation"_). 

- Build the fully connected classifier top, and train it together with validation data. Remember to present the training graphs in the notebook. Experiment with a few choices for hyperparameters, and present the one leading to the best results (do not include all your trials in the notebook).  

- Test your model with test set, and report the accuracy. (Do not be surprised if the accuracy is not very high.)

- Use markdown cells to document your work.

## Deliverables

Submit your Jupyter Notebook **both** as an .ipynb file **and** in HTML form to the appropriate assignment in OMA workspace.


