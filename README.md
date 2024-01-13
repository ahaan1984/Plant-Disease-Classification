# Plant Disease Classification using ResNet34 Architecture

## Overview

This project aims to develop a robust machine learning model for the classification of plant diseases using the ResNet34 architecture. 
The ResNet34 model is known for its deep architecture with skip connections, enabling effective training of deep neural networks. 
By leveraging this architecture, we can accurately identify and classify different plant diseases based on input images.

# Requirements

You can install the required packages using:

```
pip install -r requirements.txt
```

# About the Dataset

The dataset used for training and evaluation can be obtained from the following link: [Plant Disease Recognition Dataset](https://www.kaggle.com/datasets/rashikrahmanpritom/plant-disease-recognition-dataset/data) by He et al. 
This dataset contains three labels, "Healthy", "Powdery", "Rust" referring to plant conditions. There is a total of 1530 images divided into train, test, and validation sets.

# About the Model

The ResNet34 model is a State of the Art, convolutional neural network architecture first proposed in '(Deep Residual Learning for Image Recognition)'(https://arxiv.org/abs/1512.03385).
It is a 34 layer neural network pre-trained on ImageNet-1k dataset, commonly used for image classification tasks. 
RestNet is different from traditional neural networks in the sense that it takes residuals from each layer and uses them in the subsequent connected layers (similar to residual neural networks used for text prediction).
