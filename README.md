# Machine Learning Model Comparison

This repository contains Python code for comparing the performance of a Decision Tree Regressor and a Linear Regression model on a dataset.

## Table of Contents
- [Introduction](#introduction)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [File Descriptions](#file-descriptions)
- [Results](#results)
- [License](#license)

## Introduction
This project aims to evaluate the effectiveness of two different machine learning models, a Decision Tree Regressor and a Linear Regression model, on a given dataset. The models are trained, evaluated using metrics like Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared score, and compared based on their performance.

## Setup Instructions
To run the code in this repository, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/KanishkThamman/India-Housing
    cd India-Housing
    ```

2. Install the required dependencies:
    Ensure you have Python installed. Install necessary libraries using pip:
    ```bash
    pip install pandas matplotlib scikit-learn
    ```

3. Run the Jupyter Notebook or Python script:
    Execute the main script or open the Jupyter Notebook:
    ```bash
    jupyter notebook main.ipynb
    ```

## Usage
1. Modify the dataset path or data loading code in the notebook/script (`main.ipynb`) to use your own dataset.
2. Adjust hyperparameters or add more models for comparison as needed.
3. Run cells sequentially to train models, tune hyperparameters, evaluate performance, and visualize results.

## File Descriptions
- `main.ipynb`: Jupyter Notebook containing Python code for model training, hyperparameter tuning, evaluation, and visualization.
- `README.md`: This file, providing an overview of the project and instructions for usage.
- `House Price India.csv`: This file provides the data.

## Results
### Decision Tree Regressor:
- Achieved an R-squared score of 0.2.
- Hyperparameters optimized using GridSearchCV.
- Visualized decision tree structure.

### Linear Regression:
- Achieved an R-squared score of 0.5 (update with your actual score).
- Provided a baseline comparison against the Decision Tree model.

## License
This project is licensed under the MIT License