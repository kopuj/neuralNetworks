# Assignment: week 6

## Objectives

The objectives of this assignment are:
1.	to build a sequence-to-sequence model
2.	to learn more about Transformer architectures.

## Setup

Use the dataset containing short sentences translated from English to Finnish (*fin-eng.zip*), that can be downloaded at [https://www.manythings.org/anki/](https://www.manythings.org/anki/).

## Task

Build and train a Transformer model to translate sentences from English to Finnish with the dataset referred to above. You can use the same classes for embedding (token + positional) layer and Transformer encoder and decoder as in Chollet's "Deep Learning with Python" and [weekly material](../Transformer.ipynb). As for the actual model, follow the similar example with English-Spanish translation in Chollet's book; also, you can use the code below to read the sentences from the file:

`text_file = "fin-eng/fin.txt"` <br/>

`with open(text_file, encoding='utf-8') as f:` <br/>
 &nbsp;&nbsp;&nbsp;&nbsp;`lines = f.read().split("\n")[:-1]` <br/>
`text_pairs = []` <br/>
`for line in lines:` <br/>
&nbsp;&nbsp;&nbsp;&nbsp;`english, finnish, rest = line.split("\t")` <br/>
&nbsp;&nbsp;&nbsp;&nbsp;`finnish = "[start] " + finnish + " [end]"` <br/>
&nbsp;&nbsp;&nbsp;&nbsp;`text_pairs.append((english, finnish))` <br/>

Provide the notebook also with a couple of examples showing translated sentences. If the results are less than impressive, never mind; a genuine effort is all that is expected of this exercise.

## Deliverables

Submit your Jupyter Notebook **both** as an .ipynb file **and** in HTML form to the appropriate assignment in OMA workspace.
