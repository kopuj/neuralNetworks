# Assignment: week 4

## Objectives

The objectives of this assignment are:
1.	to learn how to obtain and use pretrained word embeddings
2.	to gain a better understanding of word vectors

## Setup

Use the pretrained GloVe embeddings, that can be downloaded [from this link](https://nlp.stanford.edu/projects/glove/); pick any of the recently uploaded versions (e.g., one of the "2024 Wikipedia + Gigaword 5" zip files).

## Task

* With the selected pretrained embeddings, find the word vectors for the three words "man", "woman", and "king". With these, calculate the vector obtained from the expression

&nbsp;
    vec("woman") - vec("man) + vec("king")

&nbsp;
    and find the nearest vector(s) to it, using the cosine similarity as the distance measure. You can use the code in [weekly material](../Text_preprocessing.ipynb) as the starting point.

&nbsp;
    Can you explain your result?

* Find another example case involving word vectors that leads to an interesting result, and reflects the semantic connections between words. Explain your example.

## Deliverables

Submit your Jupyter Notebook **both** as an .ipynb file **and** in HTML form to the appropriate assignment in OMA workspace.
