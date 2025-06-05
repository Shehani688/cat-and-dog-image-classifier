#Cat and Dog Image Classifier (Deep Learning)
Author: Shehani Gunasekara
Tools: TensorFlow, Keras, Python, Google Colab, NumPy, Matplotlib
Dataset: FreeCodeCamp Cats and Dogs Dataset

Project Overview
This project builds a convolutional neural network (CNN) to classify images of cats and dogs. The model uses deep learning techniques to learn features from images and accurately predict the class of new images.

Dataset
Source: FreeCodeCamp Cats and Dogs Dataset

Content: Images of cats and dogs split into training, validation, and test sets

Workflow
Data Preprocessing:

Loaded and rescaled images using ImageDataGenerator

Applied data augmentation to increase training data diversity

Model Building:

Designed a CNN with Conv2D, MaxPooling2D, Flatten, Dense, and Dropout layers

Compiled the model with appropriate optimizer and loss function

Model Training:

Trained the model on training data with validation

Monitored accuracy and loss to avoid overfitting

Evaluation:

Evaluated model performance on test data

Achieved 74% accuracy, surpassing the 63% challenge requirement

Visualization:

Plotted training/validation accuracy and loss

Visualized predictions with confidence scores

Key Features
Deep learning model for image classification

Data augmentation to improve generalization

Clear visualization of model performance

Practical application of TensorFlow and Keras

How to Run
Upload the dataset and notebook to Google Colab or Jupyter

Run the notebook cells sequentially

View the training progress, evaluation metrics, and prediction visualizations

Business Impact
Demonstrates ability to apply deep learning to real-world image classification problems

Useful for projects involving computer vision and automated image recognition

License
This project is for educational purposes only.
