
# Overview
This README file serves as a professional introduction to the projects showcased in this repository. Each project demonstrates a practical application of deep learning techniques using TensorFlow and Keras, particularly focusing on convolutional neural networks (ConvNets) for various classification tasks.

![Tensorflow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![keras](https://img.shields.io/badge/Keras-FF0000?style=for-the-badge&logo=keras&logoColor=white)


## Project 1 - Mood Classifier
   - Developed using the TensorFlow Keras Sequential API.
   - Classifies images to determine if individuals are smiling or not.

## Project 2 - Sign Language Digit Recognition
   - Built utilizing the Keras Functional API.
   - Differentiates between 6 distinct sign language digits (0-5) using the SIGNS dataset.

## Model Architecture
   - **Sequential API**: Created simple models where each layer has exactly one input and output tensor.
   - **Functional API**: Allows for complex models with non-linear topologies, shared layers, and multiple inputs/outputs.

## Key Components

- **Data Loading**: Each project begins with loading and preprocessing datasets, ensuring data is normalized and structured correctly for model training.
  
- **Model Creation**:
  - **Sequential Model**: Implemented using ordered layers, such as Conv2D, BatchNormalization, ReLU, and MaxPooling2D.
  - **Functional Model**: Designed with flexibility for non-linear architectures, including skip connections.

- **Compilation and Training**:
  - Models are compiled with optimizers (e.g., Adam) and appropriate loss functions (e.g., binary_crossentropy for binary classification and categorical_crossentropy for multi-class).
  - Training and evaluation of models using training and testing datasets.

## Learning Outcomes

- Understanding of building and training ConvNets for both binary and multi-class classification problems.
- Familiarity with different use cases for the Sequential and Functional APIs in TensorFlow.
- Ability to implement and evaluate complex neural network architectures effectively.

## Future Work

Future enhancements may include:
- Expanding datasets to improve model generalization.
- Implementing advanced techniques such as data augmentation and transfer learning.
- Exploring real-time classification applications using the developed models.

## References
- Official TensorFlow documentation for Sequential and Functional APIs:
  - [Sequential API Documentation](https://www.tensorflow.org/guide/keras/sequential_model) 
  - [Functional API Documentation](https://www.tensorflow.org/guide/keras/functional) 

