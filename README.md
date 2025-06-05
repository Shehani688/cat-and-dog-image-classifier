# Cat and Dog Image Classifier (Deep Learning)

**Author:** Shehani Gunasekara  
**Tools:** TensorFlow, Keras, Python, Google Colab, NumPy, Matplotlib  
**Dataset:** [FreeCodeCamp Cats and Dogs Dataset](https://cdn.freecodecamp.org/project-data/cats-and-dogs/cats_and_dogs.zip)

---

## Project Overview

This project implements a convolutional neural network (CNN) to classify images of cats and dogs. Using deep learning techniques, the model learns image features and predicts whether a new image is a cat or a dog. The project demonstrates practical skills in computer vision, model building, and evaluation.

---

## Dataset

- **Source:** FreeCodeCamp Cats and Dogs Dataset
- **Content:** Labeled images of cats and dogs, split into training, validation, and test sets

---

## Workflow

- **Data Preprocessing:**  
  - Loaded and rescaled images using `ImageDataGenerator`  
  - Applied data augmentation (rotation, flips, zoom, etc.) to increase training data diversity

- **Model Building:**  
  - Designed a CNN with Conv2D, MaxPooling2D, Flatten, Dense, and Dropout layers  
  - Compiled the model with Adam optimizer and binary cross-entropy loss

- **Model Training:**  
  - Trained the model on training data with validation  
  - Monitored accuracy and loss to avoid overfitting

- **Evaluation:**  
  - Evaluated model performance on test data  
  - Achieved **74% accuracy**, surpassing the 63% challenge requirement

- **Visualization:**  
  - Plotted training/validation accuracy and loss  
  - Visualized predictions and confidence scores for test images

---

## Key Features

- Deep learning model for image classification
- Data augmentation for improved generalization
- Clear visualization of model performance
- Practical application of TensorFlow and Keras for computer vision

---

## How to Run

1. Upload the dataset and notebook to Google Colab or Jupyter.
2. Run the notebook cells in order.
3. View training progress, evaluation metrics, and prediction visualizations.

---

## Business Impact

- Demonstrates the application of deep learning to real-world image classification problems
- Useful for projects involving computer vision and automated image recognition

---

## License

This project is for educational purposes only.

