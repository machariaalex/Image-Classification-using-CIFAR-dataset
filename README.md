# Image-Classification-using-CIFAR-dataset
CIFAR Image Classification Model
This repository contains a simple convolutional neural network (CNN) implemented in TensorFlow for classifying images from the CIFAR-10 dataset. The model has been trained on the CIFAR-10 dataset and tested on a holdout test set.

Requirements
The following libraries are required to run the code:

TensorFlow
Numpy
Getting Started
To get started with the model, follow these steps:

Clone the repository to your local machine using git clone https://github.com/[your-username]/cifar-image-classification.git
Navigate to the directory containing the code using cd cifar-image-classification
Install the required libraries using pip install -r requirements.txt
Run the code using python cifar_classification.py
Model Architecture
The model is a simple convolutional neural network consisting of two convolutional layers, each followed by a max pooling layer. The output from the final pooling layer is then flattened and passed through two dense layers before the final output layer with 10 units, one for each of the 10 classes in the CIFAR-10 dataset. Dropout is used to prevent overfitting.
Training and Evaluation
The model was trained for 10 epochs on the CIFAR-10 training set and evaluated on the holdout test set. The final test accuracy achieved was approximately 70%. This model can be further improved by using more complex architectures, training for more epochs, or using data augmentation techniques.
