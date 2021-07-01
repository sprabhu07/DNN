# DNN

## About this project

This project aims to build a Neural Network(NN) with two layers to solve an image classification task. The images are taken from the [CIFAR dataset](http://www.cs.toronto.edu/~kriz/learning-features-2009-TR.pdf) and for the scope of this project, only the images belonging to the below classes were used:

1) Ship
2) Dog


## Project structure
The project structure is as follows:

1) blobs250.csv

This file contains the data for part 2 and 3 of the project.

2) moons400.csv

This file contains the data for part 2 and 3 of the project.

3) cifar-10-batches-py

This is a folder that contains different batches of the CIFAR data.

4) .pkl files

These are the NN models which were trained using the code. One has the model with an implementation of Momentum as an optimzer while the other does not.

5) Code.ipynb

This .ipynb file has the code and explanations for the project. Parts 1 and 2 implement Logistic Regression and test it, part 3 implement a Shallow NN while part 4 and 5 deal with the CIFAR classification task.  

## Results
The results of the project can be seen closely by looking at the code in the .ipynb file.