# MNIST-Tutorial-Japanese
A simple tutorial in Japanese, for solving the MNIST dataset regression problem using tensorflow,numpy,keras, and visualizing the results (confusion matrix) of the NN prediction using seaborn.

# Objective of the tutorial
Comparison of Test-time and training-time accuracy of Perceptron, 2-layer-Perceptron, CNN and 2-layer-CNN as below:

![alt text](https://raw.githubusercontent.com/parthnan/MNIST-Tutorial-Japanese/master/training.png)

![alt text](https://raw.githubusercontent.com/parthnan/MNIST-Tutorial-Japanese/master/test.png)

# Topics covered (in English)
The tutorial walks through the following:

1. Importing necesscary packages and the dataset "keras.datasets.mnist".

2. Setting up the provided input and output vectors, viewing their structure(x_train,y_train). 

3. Visualizing a sample from MNIST dataset.

4. Conversion of output vector to a one-hot-encoding 2d vector. Required for setting up NNs.

5. NN1: Implement Perceptron , using sequential(),fit() from keras. 

6. Confusion matrix result visualization for perceptron,as below

![alt text](https://raw.githubusercontent.com/parthnan/MNIST-Tutorial-Japanese/master/seaborn.png)

7. NN2: Implement 2-layer-Perceptron + seaborn visualization. 

8. NN3: Implement Convolutional Neural Network(Conv layer+ 1 dense layer+ output layer) ,plotting accuracy as below. 

![alt text](https://raw.githubusercontent.com/parthnan/MNIST-Tutorial-Japanese/master/graphcomparison.png)

9. NN4: Implement CNNk(2 Conv layers+ 1 dense layer+ output layer) 

10. Comparison of Test and training data accuracy of Perceptron, 2-layer-Perceptron, CNN and 2-layer-CNN

# The Dataset

Standard MNIST dataset as shown below:

![alt text](https://raw.githubusercontent.com/parthnan/MNIST-Tutorial-Japanese/master/mnistdata.png)
