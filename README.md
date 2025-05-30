# First PyTorch Project: Rice Classification

This repository contains my first project exploring the PyTorch deep learning framework. The goal of this project is to build a simple neural network to classify rice grains based on their characteristics.

## Project Description

This project demonstrates the fundamental steps involved in building and training a neural network with PyTorch, including:

- Loading and preprocessing data (from a Google Sheet in this case).
- Creating a custom PyTorch `Dataset` and `DataLoader`.
- Defining a simple feedforward neural network model using `torch.nn`.
- Implementing the training loop with a loss function (`BCELoss`) and optimizer (`Adam`).
- Evaluating the model's performance on a test set.
- Visualizing the training and validation loss and accuracy over epochs.

## Dataset

The project uses a dataset containing features of rice grains and their corresponding class (presumably representing different varieties). The dataset is loaded directly from a Google Sheet for convenience.

## Model

A simple feedforward neural network is implemented with a single hidden layer and a sigmoid activation function for binary classification.

## Training and Evaluation

The model is trained using the Adam optimizer and Binary Cross-Entropy loss. The training process is monitored by tracking the training and validation loss and accuracy over a specified number of epochs. The final model performance is evaluated on a separate test set.

## Results

The project includes plots visualizing the training and validation loss and accuracy curves, providing insights into the model's learning progress and potential overfitting.
