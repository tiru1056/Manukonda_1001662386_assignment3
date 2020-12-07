# Assignment 3

This Assignment has 2 sub-problems which are implemented individually 

## Problem 1 :- (Non-parameteric density estimation )Kernel Density Estimation
- Write the function [p, x] = mykde(X,h) for 1D data that perfroms the kernel density estimation on data X with the
  bandwidth parameters of h
- Generate Random data with the given mu1 = 5  and sigma1 =1 values for N = 1000, perform the mykde with parameters of h
- Generate Random data with the given mu1 = 5  and sigma1 =1, mu2 = 0  and sigma2 =0.2 values for N = 1000, perform the mykde     with parameters of h
- Generate 2 sets of 2-D Gaussian random data with N1 = 500 and N2 = 500 , µ1 = [1, 0], µ2 = [0, 2.5] and sig1, sig2.
- Implement 2D mykde function, which perfroms the kernel density estimation on data X with the
  bandwidth parameters of h
 

#### Open file from the command line 'jupyter notebook ML_assignment3_01.ipynb ', using jupyter notebook

## Problem 2:-Implementation of PCA -(Dimension Reduction)
- Read in Train and Test data set MNIST dataset
- Implement the  PC =myPCA(X, k),MyPCA class that does dimension reduction to k dimenssions from the X data
- Apply PCA on MNIST dataset,and observe the data
- Visualize the data using the first 2 PC, 
- Visualize 10 PC as images
- Apply 30 PC on the given data and do the classification using softmax logistic regression for 10 epochs
- Apply softmax logistic regression for 10 epochs on raw data and compare both the results

#### Open file from the command line 'jupyter notebook ML_assignment3_02.ipynb ', using jupyter notebook
