# Assignment: week 2

## Objectives

The objectives of this assignment are:
1.	to work with image data
2.	to experiment with pretrained convnets

## Setup

Use the same CIFAR-10 dataset as in the course material [notebook](../ConvNets.ipynb). The data is also directly available in Keras: [https://keras.io/api/datasets/cifar10/](https://keras.io/api/datasets/cifar10/).

## Task

In the course material, a simple convolutional neural network is built, trained and tested to solve the multiclass classification task presented by the CIFAR-10 dataset. To improve the accuracy, you should experiment with pretrained models. Follow the instructions in Chollet's book "Deep Learning with Python", 2nd edition, Chapter 8, pp. 225-231: _Feature extraction with a pretrained model_. Pick one of the pretrained models available with Keras, and discard the Dense classifier top. You should only use the convolutional base to preprocess the original images to a new representation, using its `predict` method. For this modified input data, you should build a simple fully connected classifier, train it, and test it.

Prepare a Jupyter notebook containing an account of the problem treatment. Note the following:

- You should create three separate Dataset objects for training, validation, and testing.

- Pick a suitable convolutional base, and use it for fast feature extraction with all three Datasets (see page 229 in Chollet's book). 

- Build the fully connected classifier top, and train it together with validation data. Remember to present the training graphs in the notebook. Experiment with a few choices for hyperparameters, and present the ones with the best results (do not include all your trials in the notebook).  

- Test your model with test set, and report the accuracy. Try to improve the accuracy obtained with the model in the course material.

- Use markdown cells to document your work.

## Deliverables

Submit your Jupyter Notebook **both** as an .ipynb file **and** in HTML form to the appropriate assignment in OMA workspace.


