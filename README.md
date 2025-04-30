# DogVision

# End-to-end Multi-class Dog Breed Classification (v2)

Building an end-to-end multi-class image classifier using TensorFlow

## 1. Problem

Identifying the breed of a dog from a given image

## 2. Data

We're going to use the Stanford Dogs dataset, which is available from several sources:
* The original project website: http://vision.stanford.edu/aditya86/ImageNetDogs/
* Inside the Tensorflow datasets: https://www.tensorflow.org/datasets/catalog/stanford_dogs
* On Kaggle: https://www.kaggle.com/datasets/jessicali9530/stanford-dogs-dataset

## 3. Using the data

To make sure we don't have to download the data every time we come back to Colab:
* Download the data to the attached Google Drive if it doesn't already exists
* Copy the data to the Google drive if it isn't already there
* If the data already exists on Google Drive We'll import it

## 4. Features

Some information about the data:
* We are dealing with unstructured data (images), so it is probably best we use deeep learning/transfer learning.
* There are 120 breeds of dogs, this means there are 120 different classes).
* Around 10,000+ images in the training set (these images have labels)
* Around 10,000+ images in the test set
