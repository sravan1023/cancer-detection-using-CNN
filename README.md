# Cancer Detection using Streamlit

This is a simple cancer detection app built using Streamlit. It uses a machine learning model to predict whether a given medical image (either grayscale or RGB) contains signs of cancer.

## Installation

To run the app locally, you'll need to install the following dependencies:

Python 3.6+

Streamlit

PyTorch

Numpy

Matplotlib

You can install all of these dependencies using pip. For example:
pip install streamlit torch numpy matplotlib

## Usage

To start the app, run the following command in your search box:
https://sravan1023-cancer-detection-app-h17iqk.streamlit.app/

This will launch the app. From there, you can select an image to upload and the model will make a prediction based on the image.

## Model Details

The machine learning model used in this app is a convolutional neural network (CNN) that has been trained on a large dataset of medical images. The model has achieved a high level of accuracy in detecting signs of cancer in these images.

The CNN model used in the app has the following architecture:

Convolutional Layer with 32 filters of size 3x3, followed by Batch Normalization, ReLU activation, and Max Pooling
Convolutional Layer with 64 filters of size 3x3, followed by Batch Normalization, ReLU activation, and Max Pooling
Convolutional Layer with 128 filters of size 3x3, followed by Batch Normalization, ReLU activation, and Max Pooling
Convolutional Layer with 256 filters of size 3x3, followed by Batch Normalization, ReLU activation, and Max Pooling
Convolutional Layer with 512 filters of size 3x3, followed by Batch Normalization, ReLU activation, and Max Pooling
Average Pooling Layer with kernel size 8x8
Fully Connected Layer with output size 2 (one for each class)
