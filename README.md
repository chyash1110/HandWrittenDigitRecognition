# Handwritten Digit Recognition

This project implements a handwritten digit recognition system using a Convolutional Neural Network (CNN) trained on the MNIST dataset. It includes a graphical user interface (GUI) for drawing digits and recognizing them using the trained model.

## Getting Started

These instructions will help you set up and run the project on your local machine.

### Prerequisites

Make sure you have the following installed:
- Python (version 3.x)
- TensorFlow
- OpenCV
- NumPy
- PIL (Pillow)
- Tkinter (for GUI)

You can install the required Python packages using the following command:
- pip install tensorflow opencv-python numpy Pillow

### Running the Project

#### Clone the repository:
- git clone https://github.com/chyash1110/HandWrittenDigitRecognition.git

#### Change to the project directory:
- cd HandWrittenDigitRecognition

#### Run the GUI application:
- python gui.py

## Usage

- Use the GUI to draw a digit.
- Click the "Recognize Digit" button to process the drawn digit.
- The recognized digit and confidence percentage will be displayed on the image.

## Model Training

The pre-trained model is included in the repository (mnist_model.h5). If you want to retrain the model, you can use the provided Jupyter Notebook (train_model.py).

## Acknowledgments

- The MNIST dataset is used for training and evaluation.
- The CNN architecture is inspired by the LeNet-5 model.

### Feel free to contribute, report issues, or suggest improvements!
