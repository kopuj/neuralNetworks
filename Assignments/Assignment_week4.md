# Assignment: week 4

## Objectives

The objectives of this assignment are:
1.	to learn how to obtain and use pretrained word embeddings
2.	to gain a better understanding of word vectors

## Setup

Use the pretrained [GloVe embeddings](https://nlp.stanford.edu/projects/glove/) (file "glove.6B.100d.txt"), that are also available e.g. in [Kaggle](https://www.kaggle.com/datasets/anmolkumar/glove-embeddings).

## Task

With the pretrained GloVe embeddings, find the word vectors for the three words "man", "woman", and "king". With these, calculate the vector obtained from the expression

vec("woman") - vec("man) + vec("king")

and find the nearest vector(s) to it, using the cosine similarity as the distance measure. You can use the code in [weekly material](../Text_preprocessing.ipynb) as the starting point.

Can you explain your result? 

## Deliverables

Submit your Jupyter Notebook **both** as an .ipynb file **and** in HTML form to the appropriate assignment in OMA workspace.
