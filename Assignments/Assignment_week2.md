# Assignment: week 2

## Objectives

The objectives of this assignment are:
1.	to try out different model architectures
2.	to experiment with different kinds of regularization

## Setup

Use the same California housing dataset (the small-size version) as in the course material [notebook](../Graphical_monitoring.ipynb).

## Task

In the course material, a neural network is trained and tested to have the mean average error of approximately 0,3 (in units of 100000$), when computed with the test set containing 20% of the available labeled data. Your task is to try out some strategies for obtaining a better model, and try to achieve a lower MAE than the above.

Prepare a Jupyter notebook containing an account of the problem treatment. You do not have to present all the different experiments you have performed in detail: a short mention of the various trials is enough. However, the training and subsequent testing of the finally selected model must be presented in the notebook.

Note the following:

- You should use three separate datasets: training, validation, and test sets.

- Check out a few different model architectures (e.g. change the number of neurons in the hidden layers). 

- Select the model with optimal architecture among the ones you tried. Ideally, the model should still show some signs of overfitting (to make sure it has enough predictive power).

- Try out some of the strategies for reducing overfitting, and pick the one leading to the most promising results.

- Train the final model once more with training and validation sets combined, and evaluate it with the test set.

- Use markdown cells to document your work.

## Deliverables

Submit your Jupyter Notebook **both** as an .ipynb file **and** in HTML form to the appropriate assignment in OMA workspace.


