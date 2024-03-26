# Handwritten Digits Recognition Project

## Overview

This project aims to develop a Convolutional Neural Network (CNN) model to accurately categorize handwritten digits from the MNIST dataset. The MNIST dataset, easily accessible via [http://yann.lecun.com/exdb/mnist/](http://yann.lecun.com/exdb/mnist/), serves as the primary dataset for this study.

## Dataset
The MNIST dataset comprises 10 unique classes ranging from 0 to 9. It was divided into a training set of 60,000 entries and a testing set of 10,000 entries. Each entry in the training and testing sets had dimensions of 28 by 28 pixels. However, the dataset lacked a channel dimension, necessitating reshaping before processing.

## Methodology

To initiate the task, a baseline CNN model was constructed. This baseline model consisted of three convolutional blocks with a 2 by 2 kernel size, "same" padding, max pooling, a learning rate set at 0.001, a dropout rate of 0.5, and two fully connected layers. The baseline model was trained for 20 epochs using stochastic gradient descent optimization and a batch size of 32.

## Results

The primary evaluation metric for this project is the accuracy of the model in predicting the correct labels of the testing set images. Further analysis includes calculating precision, recall, and F1-score to assess the model's performance comprehensively. These results were compared with previous studies to determine the competitiveness of the baseline model.

## Conclusion

In conclusion, this project aims to train a robust model capable of accurately classifying handwritten digits from the MNIST dataset. The results obtained  provided insights into the effectiveness of the implemented CNN architecture for handwritten digit recognition tasks.