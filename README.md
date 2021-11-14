# Dog Breed classifier using CNN
This is my repo of Dog breed classifier project in the Udacity ML Nanodegree (The Udacity's original repo is [here](https://github.com/udacity/deep-learning-v2-pytorch/tree/master/project-dog-classification)

# Project Overview
The goal of this project is to build a pipeline to process real-world user-supplied images. The algorithm predicts the breed of a dog given an image and if a human image is passed to it, it predicts the closest matching dog breed. If Neither, it should return that it cant detect if the image is human or a dog

# Datasets
The Datasets used for this project:
1. Human Dataset: https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip
2. Dog Dataset: https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip

# Methodology
Pytorch
Convolutional Neural Networks (CNN)
Data Augmentation
OpenCV pre-trained face detectors (haarcascades & lbpcascade)
Pre-trained VGG-16 convolutional network
Transfer Learning 

# Results from Models Trained
1. CNN model from scratch was trained using GPU acceleration for 30 epochs to achieve test accuracy of 12%
2. CNN model using pre-trained ResNet50 model with Transfer learning was trained using GPU acceleration for 10 epochs to achieve test accuracy of 75%
