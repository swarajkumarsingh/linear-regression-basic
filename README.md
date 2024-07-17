# Crop Prediction Using Simple Linear Regression with PyTorch

This repository contains a simple linear regression model built with PyTorch to predict crop yields based on rainfall, temperature, and humidity.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Predicting crop yields is crucial for efficient agricultural planning and management. This project uses a simple linear regression model implemented in PyTorch to predict crop yields based on key environmental parameters: rainfall, temperature, and humidity.

## Dataset

The dataset used in this project includes historical data on crop yields and corresponding values for rainfall, temperature, and humidity. Ensure your dataset is in a CSV format and follows this structure:
[ ] Rainfall 
[ ] Temperature 
[ ] Humidity
[ ] Crop_yield


## Model Architecture

The model is a simple linear regression model with the following structure:

- Input layer: 3 neurons (rainfall, temperature, humidity)
- Output layer: 1 neuron (predicted crop yield)

## Training

The training loop includes:

- Data loading and preprocessing
- Forward pass
- Loss calculation using Mean Squared Error (MSE)
- Backward pass and optimization using Stochastic Gradient Descent (SGD)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/crop-prediction-pytorch.git
   cd crop-prediction-pytorch
   ```

2. Install the required dependencies:
  ```bash
  pip install -r requirements.txt
  ```

## Usage

1. Prepare your dataset and place it in the data/ directory.
2. Train the model by running:
  ```bash
  python train.py
  ```

## Results
After training, the model will output the predicted crop yields. You can evaluate the model's performance using metrics like Mean Squared Error (MSE).

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any changes or enhancements.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

