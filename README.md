# Digit-and-character-recognition
Basic CNN model trained using MNIST and NIST dataset to predict handwritten characters (letters and digits), each image is resized to grayscale 28x28px image. The model included in this repo is not perfect as I'm still learning to improve it. More explanation below:
The Data
NIST characters dataset


MNIST digits dataset


To add more relevant data, Data Augmentation with the following properties were added:

Rotation (10 degree)
Scaling (10%)
Shifting (10%)
CNN Architecture


Then the model is trained using the ADAM gradient descent algorithm, logarithmic loss, and a mini-batch gradient descent with mini-batch size 64 then saved model will be used to predict canvas image in Tkinter GUI.

App Demo


Prerequisites
Python 3.5 and up
Tkinter
Tensorflow
Keras
Scikit-learn
Pillow 7.1.2
Running
Put model and model in the same folder as main.py
Run main.py
Built With
Python 3.8.1 - The main programming language used
Tensorflow 2.2.0 - One of the best ML library to ease developing
Tkinter 8.6 - Used to make the program GUI
Pycharm 2020.1.2 - Main Python IDE used
