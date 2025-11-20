# Assignment: week 5

## Objectives

The objectives of this assignment are:
1.	to learn about residual connections and layer normalization, and their implementation
2.	to assemble a model using these components (simplified Transformer encoder block)

## Setup

Use the IMDB dataset of movie reviews for this assignment; you can download the data (with integer indexing) directly from Keras.

## Task

In the [course material](../Attention.ipynb), a binary classifier model containing token and positional embedding and a multi-head attention layer has been built and trained. Using this model as a starting point, you should expand it by adding a few new components to mimic a simplified Transformer encoder block; see [this figure](../Images/transformer_encoder.png).

Your model should contain (in addition to the components mentioned above)

- a **fully connected feedforward network** after the attention layer (e.g. two Dense layers with ReLU and no activation, respectively),
- two **residual connections** (bypassing the attention layer and the feedforward network), 
- two **normalization layers** (directly after the two residual connections),
- a **GlobalAveragePooling1D** layer to connect the output of the encoder block to the final output layer, and
- an output layer appropriate for binary classification.

Use the Keras functional API to implement the residual connections, and the LayerNormalization layer provided by Keras. Select the hyperparameters (e.g., the number of units in the Dense layers) as you see fit; however, make sure that the tensor dimensions are compatible. 

Also, train the model, and test it with the test set.

## Deliverables

Submit your Jupyter Notebook **both** as an .ipynb file **and** in HTML form to the appropriate assignment in OMA workspace.
