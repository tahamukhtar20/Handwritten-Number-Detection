# Handwritten Number Detection with Keras

This project uses Keras to detect handwritten numbers. It is a simple neural network model trained on the MNIST dataset of handwritten digits. The model is then used to predict the digit in a given image.

## Requirements

To run this project, you will need the following dependencies:

- Python 3.6 or later
- Keras 2.4.3 or later
- TensorFlow 2.4.1 or later
- NumPy 1.19

## Usage

1. Clone the repository:
> git clone https://github.com/tahamukhtar20/Handwritten-Number-Detection.git
2. Install the dependencies:
> pip install keras tensorflow numpy
3. Run the script:
> python predict.py <path-to-image>
Replace `<path-to-image>` with the path to the image you want to predict.

## Results

The model achieves an accuracy of 97% on the MNIST test dataset. The accuracy on your own images may vary depending on the quality of the image and the similarity to the MNIST dataset.

