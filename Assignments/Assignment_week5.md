# Assignment: week 5

## Objectives

The objectives of this assignment are:
1.	to learn about residual connections and their implementation
2.	to add layer normalization to a NN model.

## Setup

Use the IMDB dataset of movie reviews for this assignment; you can download the data directly from Keras, as e.g. in [course material](../Attention.ipynb).

## Task

In the [course material](../Attention.ipynb), a simple binary classifier containing an attention layer has been built and trained. Using this model as a starting point, you should modify it by adding

- a **residual connection** (around the attention layer), and
- **layer normalization** (directly after the attention layer),

as shown in the image in section 11.4.3 (**The Transformer encoder**) in Chollet's "Deep Learning with Python", 2nd ed. Use the functional API to implement the residual connection, and the LayerNormalization layer provided by Keras. (You do not need to construct a complete Transformer encoder, the two elements mentioned above are enough.)

Also, train the model, and test it with the test set.

## Deliverables

Submit your Jupyter Notebook **both** as an .ipynb file **and** in HTML form to the appropriate assignment in OMA workspace.
