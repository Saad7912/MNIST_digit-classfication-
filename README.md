# Neural Network for Image Classification
This project demonstrates a neural network for classifying grayscale images. Several libraries are used to load and process the dataset, build the model, and evaluate its performance. Additionally, the model can predict outcomes for new images not present in the training or test datasets.

# Libraries Used
numpy
matplotlib
seaborn
cv2 (OpenCV)
tensorflow
keras
# Project Overview
# Load Dataset: The MNIST dataset is loaded from keras.datasets.
# Image Preprocessing:
Convert images from RGB to grayscale for new images not in the dataset.
Change the dimensions of the images for model input.
# Model:
Built a neural network.
Used the Adam optimizer.
The loss function is categorical cross-entropy.
Evaluated the model using accuracy metrics.
# Conclusion
This project shows how to build and train a simple neural network for image classification using the MNIST dataset. The model preprocesses the images, trains on the data, and evaluates the performance using accuracy metrics. It can also predict outcomes for new images not in the dataset by converting them from RGB to grayscale and adjusting their dimensions.
