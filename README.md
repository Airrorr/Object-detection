# Object-detection


In this code, we will write an object detection application using CNN as well as the following: keras, numpy and matplotlib libraries.

(trainimg,trainlb),(testimg,testlb) = datasets.cifar10.load_data()

Here we are downloading the data, which is the objects in this case.

Requirments:

from keras import datasets import numpy import matplotlib.pyplot as plt from keras import models from keras import layers from keras.utils import to_categorical from keras.layers import Dense, Activation, Flatten, Dropout, BatchNormalization import cv2
