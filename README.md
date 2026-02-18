# System Identification Projects

This repository contains MATLAB implementations for data-driven modeling using polynomial regression and nonlinear system identification(NARX). 
The algorithms utilize least squares method estimation to find optimal parameters.

## Overview
The project is divided into two main modules:

### 1. Polynomial Surface Fitting & Model Order Selection
Goal: Approximate a 3D surface using polynomial basis functions.
Key Features:
    * Iteratively tests polynomial degrees
    * Calculates Mean Squared Error (MSE) for both datasets.
    * Demonstrates the bias-variance tradeoff(identifies where overfitting occurs).
    * Visualizes results using 3D mesh plots.

### 2. Nonlinear System Identification (NARX)
Goal: Model a dynamic system using input-output data.
Method:dynamic polynomial regression (ARX structure with nonlinear extensions).
Key Features:
    * Manual construction of the regressor matrix
    * Supports Linear, Quadratic, and Cubic model degrees.
    * One-step-ahead Prediction: Uses past real outputs to predict the next step.
    * Free-run Simulation:Uses the model's own past predictions recursively.
    * Performance metrics (MSE) and time-series comparison plots.

