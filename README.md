# Dog Breed Identification
This notebook uses transfer learning to build a Multi-Class Image Classifier using TensorFlow 2.x and TensorFlow Hub.

## 1. Problem

We are provided with a training set and a test set of images of dogs. Each image has a filename that is its unique id. The dataset comprises 120 breeds of dogs. The goal is to create a classifier capable of determining a dog's breed from a photo.

## 2. Data

The data we're using is from Kaggle's dog breed identification competition.

https://www.kaggle.com/c/dog-breed-identification/data 

## 3. Evaluation

The evaluation is a file with prediction probabilities for each dog breed of each test image.

https://www.kaggle.com/c/dog-breed-identification/overview/evaluation

## 4. Features
* There are 120 breeds of dogs (this means there are 120 different classes).
* There are around 10,222 images in the training set (these images have labels.
* There are around 10,222 images in the test set (these images have no labels, because we'll want to predict them).
