# Project Title

This is the Neural Network Modeling challenge 13! I begin by importing a csv file and preparing the data in the csv file
so I can create a logistic regression style model where I want to predict if an applicant will be successful or not.

The methodology is more or less the same for all three iterations of the model:
In the original model I start with 116 input nodes, 2 nodes for the first hidden layer, 1 node for the second
hidden layer, and 1 output layer.  I compile, fit, and evaluate the model with 50 epochs.  There are a total
of 239 params.

For the first optimize attempt I start with 116 nodes but then for my first hidden layer I take half the nodes used
for my input nodes.  That gives me 58 nodes. I use 1 node for my output layer.  I also up the epoch number to 100.  Total params used for this model are 6845.

For the second optimize attempt I start with 116 nodes and have a first hidden layer of 58 nodes just like above.  I add a second hidden layer, however, by taking half of the first layer and that gives me 29 more nodes.  I use up the epoch number to 200.
This model has a total param number of 8527.


The original model gave me a loss and accuracy of 0.6915 and 0.5292, respectively.  Not too great from the look of it.

The first updated model gave me a loss and accuracy of 0.5630 and 0.7306, respectively . I tried to improve it by adding more nodes in the first hidden layer. I removed the second hidden layer. I also increased the number of epochs to 100 from 50 previously.  It seemed to help quite a bit but only 73% accuracy doesn't impress me!

For the last updated model I had the same model as the first update but I added a second hidden layer. I then updated the number of epochs to 200. This didn't seem to help much with a loss and accuracy of 0.5917 and 0.7284.  A slight drop in accuracy if anything. Interesting!  I would have thought adding another hidden layer and more epochs would help but apparently not!


## Story

To predict whether Alphabet Soup funding applicants will be successful, you will create a binary classification model using a deep neural network.

This challenge consists of three technical deliverables. You will do the following:

Preprocess data for a neural network model.

Use the model-fit-predict pattern to compile and evaluate a binary classification model.

Optimize the model.

---

## Technologies

I am using python version 3.7.10 and am importing the following from the built-in libraries and from functions i've created myself:

# Imports
import pandas as pd
from pathlib import Path
import tensorflow as tf
from tensorflow.keras.layers import Dense
from tensorflow.keras.models import Sequential
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler,OneHotEncoder

---

## Installation Guide

I have python version 3.7.10 and git version 2.33.0.windows.2 installed on a laptop running windows 10 pro.

I launch jupyter lab, run venture_funding_with_deep_learning.ipynb and that's it!


---

## Usage

Just run the venture_funding_with_deep_learning.ipynb notebook and run the code. User can feel free to change any nodes or epochs for any model.

---

## Contributors
Just me, Paul Lopez.


---

## License
No licenses required. Just install everything for free, pull from my repository, and enjoy!
