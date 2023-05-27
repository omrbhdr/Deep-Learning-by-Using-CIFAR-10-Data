# Deep-Learning-by-Using-CIFAR-10-Data

This project is abouytasd

##   
....................libs...........................

            import numpy as np
            from tensorflow import keras
            from tensorflow.keras import layers
            import keras
            import matplotlib.pyplot as plt
            import numpy as np
            import tensorflow as tf
            from tensorflow.keras import Sequential
            from tensorflow.keras.layers import Conv2D,MaxPool2D,Dropout,Flatten,Dense,BatchNormalization
            import pandas as pd
            import cv2
            import matplotlib.pyplot as plt
            import seaborn as sns
            from PIL import Image

.....................................................

Loads the CIFAR10 dataset.

This is a dataset of 50,000 32x32 color training images and 10,000 test images, labeled over 10 categories. See more info at the CIFAR homepage.

                                The classes are:

                                Label	Description
                                    0	airplane
                                    1	automobile
                                    2	bird
                                    3	cat
                                    4	deer
                                    5	dog
                                    6	frog
                                    7	horse
                                    8	ship
                                    9	truck
                                Returns

Tuple of NumPy arrays: (x_train, y_train), (x_test, y_test). x_train: uint8 NumPy array of grayscale image data with shapes (50000, 32, 32, 3), containing the training data. Pixel values range from 0 to 255.

y_train: uint8 NumPy array of labels (integers in range 0-9) with shape (50000, 1) for the training data.

x_test: uint8 NumPy array of grayscale image data with shapes (10000, 32, 32, 3), containing the test data. Pixel values range from 0 to 255.
y_test: uint8 NumPy array of labels (integers in range 0-9) with shape (10000, 1) for the test data.


![image](https://github.com/omrbhdr/Deep-Learning-by-Using-CIFAR-10-Data/assets/12261537/836c7b8f-f0b7-47c1-908c-03529bfc1de1)
![image](https://github.com/omrbhdr/Deep-Learning-by-Using-CIFAR-10-Data/assets/12261537/06796cdd-cc86-48c6-9354-f65368485a34)


