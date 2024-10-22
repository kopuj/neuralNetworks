# Assignment: week 1

## Objectives

The objectives of this assignment are:
1.	to learn to build and train a simple neural network with Keras
2.	to learn to follow and interpret the progress of training

## Setup

Use the iris dataset for this assignment: [https://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.data](https://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.data).

## Task

Fetch the iris dataset (e.g. from the above link) and execute the necessary preprocessing to convert the input features and target labels to a form suitable for inserting into neural networks built with Keras. 

Your task is to build a multiclass classifier that takes the four numerical features of the iris samples as input, and outputs the prediction for its species. The classifier should be a minimal neural network model, created with Keras library, and consisting of **a single (output) layer of three units with softmax activation**.

Prepare a Jupyter notebook containing a full account of the problem treatment, including the training of the model. Please take into account the following:

- Remember to one-hot-encode the target labels.

- It might be a good idea to apply random shuffling to the data, check out `np.random.shuffle`.

- Use the parameter `validation_split` with the `fit` method to extract a part of data from training for validation purposes (you don't need to extract a separate test set).

- Pick accuracy as the relevant metric, and aim to achieve approx. 95% for both training and validation accuracy with your model.

- If you experience problems in having your model to learn, try modifying the **learning rate** parameter of your optimizer; see [https://keras.io/api/optimizers/](https://keras.io/api/optimizers/) how this can be done.

- Use markdown cells to document your work.

## Deliverables

Submit your Jupyter Notebook **both** as an .ipynb file **and** in HTML form to the appropriate assignment in OMA workspace.


