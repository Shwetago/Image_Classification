# Image_Classification

This is basically a binary classification which is used to classify the images of a cat or a dog. I have implemented this on 'jupyter notebook'.
- I have used CNN for the classification.
- I have used keras library which is a framework built on top of tensorflow and used tensorflow as backend.

# Installation

Install Anaconda from here [Anaconda] (https://www.anaconda.com/download/#windows)

First install tensorflow otherwise you will get an error because keras is a framework which needs a backend, it can be either tensorflow or theano. I have tested this using tensorflow.
Easiest way is open 'Anaconda Navigator' and from top upper lest corner change base(root) to tensorflow.
Then install jupyter notebook from there and then launch it.

## Activate Tensorflow
- Open anaconda prompt
- Type below commands because you need to activate tensorflow and these are the steps that worked for me.
```
conda create -n tensorflow python=3.5
activate tensorflow
conda install -c conda-forge tensorflow
```
## Install keras 
- After activating tensorflow type 'conda install keras' or 'pip install keras' in anaconda prompt.

There you go. 
