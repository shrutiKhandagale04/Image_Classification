# Cats and Dogs Image Classification

This project trains a deep learning model to classify images of cats and dogs using TensorFlow and Keras. It demonstrates downloading a dataset, preparing data, building a model, and evaluating the trained model.

## Overview
The goal of this project is to classify images of cats and dogs with a Convolutional Neural Network (CNN) using the TensorFlow library. This model achieves image classification by training on a set of labeled images and then evaluates its performance on a test set.

## Dataset
The dataset is from [TensorFlow Datasets](https://www.tensorflow.org/datasets) and contains a labeled collection of cats and dogs images.

- **Training Data**: 80% of the images
- **Validation Data**: 20% of the images

You can download the dataset directly within the script using TensorFlow’s `tf.keras.utils.get_file()` function.

## Requirements
- Python 3.6+
- TensorFlow 2.x
- Keras (integrated with TensorFlow 2.x)
- NumPy
- Matplotlib (for visualizing results)
