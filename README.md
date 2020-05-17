# End-to-end Multil-class Dog Breed Classification

This notebook builds an end-to-end multi-class image classifier using TensorFlow 2.x and TensorFlow Hub.

Note: Project done on Colab. If interested in contributing, pull request...

## 1. Problem

Identifying the breed of a dog given an image of a dog. When an image of a dog is presented to the model, it should be able to predict the breed of the model with maximum accuracy.

## 2. Data

The data we're using is from Kaggle's dog breed identification competition.

https://www.kaggle.com/c/dog-breed-identification/data 

## 3. Evaluation

The evaluation is a file with prediction probabilities for each dog breed of each test image.

https://www.kaggle.com/c/dog-breed-identification/overview/evaluation


## 4. Features

Some information about the data:
* Since the data dealt with here are images; which are unstructured data, we are gonna use an already trained model available in TensorFlow hub (MobileNetV2 model for image classification). That is, we are gonna use deep learning/transfer learning.
* There are 120 different unique dog breeds, i.e., 120 different classes
* There are 10000+ images in the training set and they have labels
* There are 10000+ images in the test set

## 5. Results

1) Value count of unique breeds in training data

![value-counts-breeds](https://user-images.githubusercontent.com/25824881/82136651-7d381880-982d-11ea-9dee-4d0219c5af77.png)

2) Prediction on test dataset

![prediction](https://user-images.githubusercontent.com/25824881/82136658-993bba00-982d-11ea-8211-58b2943a483d.png)

3) Using model on custom images

![custom image prediction](https://user-images.githubusercontent.com/25824881/82136676-bb353c80-982d-11ea-9de4-5f0eb3c07129.png)

