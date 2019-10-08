# MNIST-Tutorial-Japanese
A simple tutorial in Japanese, for solving the MNIST dataset regression problem using tensorflow,numpy,keras, and visualizing the results (confusion matrix) of the NN prediction using seaborn.

The tutorial walks through the following:

1. Importing necesscary packages and the dataset "keras.datasets.mnist".

2. Setting up the provided input and output vectors, viewing their structure(x_train,y_train). 

3. Visualizing a sample from MNIST dataset.

4. Conversion of output vector to a one-hot-encoding 2d vector. Required for setting up NNs.

5. NN1: Implement Perceptron , using sequential(),fit() from keras. 

6. Confusion matrix result visualization for perceptron,as below

![alt text](https://raw.githubusercontent.com/parthnan/MNIST-Tutorial-Japanese/master/seaborn.png)

7. NN2: Implement 2-layer-Perceptron , using sequential(),fit() from keras. 

8. NN3: Implement Dense Neural Network , using sequential(),fit() from keras. 
