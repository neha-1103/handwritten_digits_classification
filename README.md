# Handwritten Digit Recognition using Deep Learning (Keras)
This project uses a Convolutional Neural Network (CNN) to recognize handwritten digits from the MNIST dataset using TensorFlow and Keras. The model is trained on 60,000 labeled images of digits and tested on 10,000 images to classify digits from 0 to 9.

# Features
Uses the MNIST dataset built into Keras

Convolutional Neural Network (CNN) for better accuracy

Accuracy of over 98% on test data

Dataset
MNIST Dataset
Handwritten digits (28x28 grayscale images) with 10 classes (0–9)
Automatically loaded from Keras:

# How to Run
1. Clone the repository
In terminal, type 
" git clone https://github.com/yourusername/handwritten-digit-recognition.git " 
" cd handwritten-digit-recognition "
2. Install requirements
pip install tensorflow
3. Run the project
In terminal, type 
" python digit_recognition.py "


# Model Architecture

Input Layer: 28x28 grayscale image
↓
Scaled 
↓
Flatten
↓
Dense (100) + ReLU
↓
Dense (10) + sigmoid

# Results
The model is trained at an accuracy  with 99.85%

The model is tested at an accuracy of 98%

# Saving the Model
The model is saved in keras file.

