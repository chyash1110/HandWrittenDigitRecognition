# Handwritten Digit Recognition using Convolutional Neural Network

This repository contains a simple application for handwritten digit recognition using a Convolutional Neural Network (CNN) implemented in Keras with a Tkinter-based GUI for user interaction.

## Project Overview

The project involves training a CNN on the MNIST dataset for handwritten digit recognition. The trained model is then saved and integrated into a Tkinter-based GUI application. Users can draw a digit on the canvas, and the application will predict the drawn digit using the trained model.


## Usage

### Run the train_model.py script to train the CNN and save the model:
    train_model.py
### Run the GUI application:
    python gui.py
  
- The Tkinter-based GUI will open, allowing you to draw a digit on the canvas.
- Click the "Search" button to initiate the digit recognition process.
- The predicted digit and the confidence level will be displayed on the GUI.

## File Descriptions

### train_model.py:
- Python script to load the MNIST dataset, train the CNN model, and save the trained model as mnist.h5.

### gui_app.py: 
- Tkinter-based GUI application for handwritten digit recognition using the trained model.
  
### mnist.h5:
- Pre-trained CNN model for handwritten digit recognition.

## Contributing
Feel free to contribute to the project by opening issues or submitting pull requests. Your feedback and suggestions are welcome!
