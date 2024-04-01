# Lab 1 – Develop a Multilayer (Deep) Neural Network
# Lab 2 – Training the Multilayer Neural Network

## Pre-requisite

1. Visual Studio Code
2. Python

# Requirement

## Task 1: Develop a Multilayer Neural Network

Develop a multilayer (deep) neural networks for binary classification problem according to the following specification.

Model: (10/ReLU) – (8/ReLU)² – (4/ReLU) – (1/Sigmoid)

The specification above means the following:

layer 1 with 10 neurons and ReLU activation function
layers 2 and 3 (2 layers shown as power 2 in the spec) with 8 neurons per each layer and ReLU activation function
layer 4 with 4 neurons and ReLU activation function
one (last) layer 5 with one neuron and Sigmoid activation function

## Task 2: Train the Multilayer Neural Network

Train your neural network using your training set both developed in Lab 1.

**** Check train.ipynb **********

## OUTPUT

Model: (10/ReLU) – (8/ReLU)² – (4/ReLU) – (1/Sigmoid)

![Model Deep Neural network](https://github.com/harshilaNEU/Multilayer_NN/blob/main/Output/output.png)

## Task 2: Develop a training set

Choose objects to train the network and develop a training set.

## Dataset
CIFAR-10 is a dataset consisting of 60000, 32×32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images. More details about the datset can be found [here](https://www.cs.toronto.edu/~kriz/cifar.html).

Sample images from each class of the CIFAR-10 dataset is shown below:


![Dataset](https://github.com/harshilaNEU/Neural_Networks/blob/Training_Sets/Reference_Images/CIFAR-10_dataset.png)

## To Generate the Prototype

1. Took 10% of the of Train dataset, 1% of each class 'airplane', 'automobile', 'bird', 'cat', 'deer', 'dog', 'frog', 'horse', 'ship', 'truck'. So considered 5000 images.

## Steps to generate the training set

1. Take clone of repository.
2. Locate jupyter_notebook "generate_prototype_cifar_10.ipynb"
3. Run the notebook "generate_prototype_cifar_10.ipynb"

## Steps to train the network Task - 2
1. Take clone of repository.
2. Locate jupyter_notebook "generate_prototype_cifar_10.ipynb"
3. Run the notebook "generate_prototype_cifar_10.ipynb"
4. Run train.ipynb

## Downloaded CIFAR-10 dataset

![Original CIFAR-10 dataset](https://github.com/harshilaNEU/Neural_Networks/blob/Training_Sets/Reference_Images/Downloaded_CIFAR-10_data.png)

## Output of Generated Prototype 

Uploaded all training set images in prototype_generated.zip

![Generated_Prototype](https://github.com/harshilaNEU/Neural_Networks/blob/Training_Sets/Reference_Images/output.png)


![Classwise_prototype_generation](https://github.com/harshilaNEU/Neural_Networks/blob/Training_Sets/Reference_Images/internal_folder_structure.png)



## Task 3: GitHub

Repository : Multilayer_NN

HTTPS: https://github.com/harshilaNEU/Multilayer_NN.git

SSH: git@github.com:harshilaNEU/Multilayer_NN.git

