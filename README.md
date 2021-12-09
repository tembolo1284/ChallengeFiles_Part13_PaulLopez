# Project Title

This is the Neural Network Modeling challenge 13! I begin by importing a csv file and preparing the data in the csv file
so I can create a logistic regression style model where I want to predict if an applicant will be successful or not.

The methodology is more or less the same for all three iterations of the model:
In the original model I start with 2 input nodes, 2 nodes for the first hidden layer, 1 node for the second
hidden layer, and 1 output layer. 


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
