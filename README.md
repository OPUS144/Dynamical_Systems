# Dynamical_Systems
Travelling through space and time.

## Introduction

This repository has the data sets, codes, and reports for the Data-Driven Methods for Dynamic Systems course. Please note that this is a work in progress, and as such, some results are not final nor do all the lines of code fully work.

Hi! I'm Myriam, a pure and applied mathematician at Concordia University. My research particular concerns mathemtical models and origami, and how we may integrate more tactile learning into mathematical education. In this course, observing the dynamics of different systems led to the idea of learning and predicting an origami crane's motion in space and time. Thus, below, you shall find the data sets and codes that composed the past four months of my education! 

Our Professor for this course, Jason Bramburger, PhD., has a Github of his own, which includes a very comprehensive basis for understanding dynamical systems. I strongly suggest you check it out! Here is the link to his Github: https://github.com/jbramburger

## Repository Contents

### Assignment 1: Dynamic Mode Decomposition

Purpose: To conduct a Dynamic Mode Decomposition (DMD) analysis of two videos to isolate the salient information (the moving car or the skier) and the static information (the background). Method: Initiation of a low-rank approximation Singular Value Decomposition (SVD), resulting in the DMD, providing a time-bound, low-error forecast of the initial frame to the next. Results: An attempt at the reconstruction of the frames containing only the object(s) in motion or containing only the static background. Conclusion: SVD provides an ability to dissociate space and time information, resulting in accurate DMD due to the forecasting of one frame to the next. 

### Assignment 2: Sparse Identification of Non-Linear Dynamics

This study has the goal of analyzing the nonlinear motion of an object on a spring through space using Principal Component Analysis (PCA) and Sparse Identification of Nonlinear Dynamics (SINDy) on six videos, three for different perspectives of a low-noise ideal case and three for different perspectives of a high-noise case. This is accomplished through the learning of equations of motion, created by the SINDy algorithm, to approximate Newton's Second Law of Motion using polynomials. Particularly, it was found that two principal components were required to do so up to some error, most likely due to tracking method error.

### Assignment 3: Recurrent Neural Networks

This study has three specific aims: to determine the loss function leading to the best predictions; to determine with how many time steps the prediction remains accurate; and to see whether the RNNs properly learned to predict data for values of parameter rho other than the training data. This is achieved through the use of ordinary differential equations, particularly the Lorenz equations, to train recurrent neural networks (RNNs) to take data from one time step to the next using the parameter rho. As the only tested loss function, the predictions for taking data from one time step to another were that of the mean square error (MSE).

### Final Project: Sparse Identification of Non-Linear Dynamics and Origami Cranes

This study has the aim of tracking and analyzing the motion of origami as the four corners of the paper fold into the traditional crane, using Principal Component Analysis (PCA) and Sparse Identification of Nonlinear Dynamics (SINDy) on three videos on the x-, y-, and z-axes. This is accomplished by approximating the motion of the folds in space and time, through the SINDy algorithm. Particularly, it was found that one principal component is typically required to do so up to some error, most likely due to tracking method error. Furthermore, model comparison is explored organically due to the symmetry of the origami crane.
