# Linear Regression using Burn Framework

## Introduction

This project implements a simple linear regression model using the Burn framework in Rust. The goal is to generate synthetic data, train a model, and visualize the results using text-based plotting.

## Approach

1. Data Generation:
   We generate synthetic data points where y = 2x + 1 with some added noise.

2. Model Definition:
   A simple linear regression model is defined using Burn's Linear module.

3. Training:
   The model is intended to be trained using gradient descent, but the current version only visualizes data.

4. Visualization:
   The generated data points are plotted using the textplots crate to provide a textual representation of the data distribution.

## Results and Evaluation

Currently, the program prints sample data points and plots them on a Cartesian plane. The next steps involve implementing training functionality and evaluating the model’s accuracy.

## Reflection

Working with the Burn framework in Rust provides an efficient and structured approach to deep learning. Future work includes adding a training loop, loss function, and model evaluation metrics.

## Usage

To run the program:

cargo run

Ensure dependencies like burn, rand, and textplots are included in Cargo.toml.

