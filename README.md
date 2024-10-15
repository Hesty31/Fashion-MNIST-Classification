# Fashion-MNIST-Classification

## Project Overview
This project implements a Convolutional Neural Network (CNN) to classify images from the Fashion MNIST dataset using both Python and R. The model includes six layers, as per requirements.

## How to Run the Code

### Python
1. Ensure Python is installed (version 3.6+).
2. Install the required libraries: `pip install keras tensorflow numpy`.
3. Run `python index.py` to train the model and make predictions.

### R
1. Install R and RStudio.
2. Install the necessary libraries by running the following commands:
   ```
   install.packages("keras")
   install.packages("tensorflow")
   ```
3. Open `index.R` in RStudio and run the code.

## Code Explanation
The CNN consists of:
- Three Convolutional Layers with ReLU activation
- Two MaxPooling layers for down-sampling
- A Dense layer followed by a final Softmax layer for classification

## Output
- Predictions are made on two test images from the Fashion MNIST dataset.
