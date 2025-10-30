# Assignment: week 2

## Objectives

The objectives of this assignment are:
1.	to try out different model architectures
2.	to experiment with different kinds of regularization

## Setup

Use the same California housing dataset as in the course material [notebook](../Graphical_monitoring.ipynb), but this time select the "large" version to obtain more samples to work with.

## Task

Your task is to build a fully connected neural network model for predicting the median house value in California districts, using the available features in the dataset. You should start by first building a large enough model that you can recognize to overfit the training data. After this, you should try out different strategies for reducing overfitting, and select the one that leads to the best results on the validation set - in terms of mean average error (MAE).

Prepare a Jupyter notebook containing an account of the problem treatment. You do not have to report all the different experiments and their results (training printouts etc.) in detail: a short mention of the various trials is enough. However, the training and subsequent testing of the finally selected model must be presented in the notebook.

Note the following:

- You should use three separate datasets: training, validation, and test sets.

- First, try out a few different model architectures (without any regularization) until you find one that clearly overfits the training data. 

- Try out some of the strategies for reducing overfitting, and pick the ones leading to the most promising results on the validation set.

- Train the final model once more with training and validation sets combined, and evaluate it with the test set.

- Use markdown cells to document your work.

## Deliverables

Submit your Jupyter Notebook **both** as an .ipynb file **and** in HTML form to the appropriate assignment in OMA workspace.


