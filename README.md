ML Supervised Regression – CNN Task
Overview

This project predicts the (x, y) position of a single bright pixel in a 50×50 grayscale image using a Convolutional Neural Network (CNN). Each image contains one pixel with value 255, and all others are 0. The task is treated as a regression problem.

Dataset

A synthetic dataset of 10,000 samples was generated. For each image, one pixel location was randomly selected and set to 255. The corresponding coordinate was used as the label. Uniform sampling ensures no spatial bias.

Model

A CNN was used to learn the spatial mapping from image to coordinates.

Output layer: 2 neurons (x, y)

Loss function: Mean Squared Error (MSE)

Optimizer: Adam

Results

Training and validation loss curves are plotted.

Ground truth vs predicted coordinates are visualized.

The model accurately predicts pixel positions with low error.

Dependencies
pip install numpy matplotlib tensorflow
