# NTU-AIYA: SVM Kernels Implementation

This project demonstrates the implementation of Support Vector Machine (SVM) kernels using Python. It focuses on visualizing and comparing the performance of linear and polynomial kernels on a synthetic dataset.

## Overview

The notebook `SVM_Kernels_Implementation.ipynb` contains the following key components:

1. Data Generation: Creation of a synthetic dataset with two classes in a circular pattern.
2. Data Visualization: 2D and 3D scatter plots to visualize the dataset.
3. SVM Implementation:
   - Linear kernel SVM
   - Polynomial kernel SVM
4. Performance Comparison: Accuracy evaluation of both kernels.

## Requirements

- Python 3.x
- NumPy
- Matplotlib
- Pandas
- Scikit-learn
- Plotly (for 3D visualizations)

## Key Findings

- The linear kernel SVM struggles with the circular dataset, achieving only 45% accuracy.
- The polynomial kernel SVM perfectly separates the classes, achieving 100% accuracy.

## Visualizations

The notebook includes several visualizations:
- 2D scatter plot of the original dataset
- 3D scatter plots showing the transformation of the data using polynomial features

## How to Use

1. Clone this repository.
2. Open the `SVM_Kernels_Implementation.ipynb` notebook in Jupyter or Google Colab.
3. Run the cells sequentially to see the data generation, visualization, and SVM implementations.

## Future Work

- Implement and compare other SVM kernels (e.g., RBF, sigmoid).
- Apply the kernels to real-world datasets.
- Optimize hyperparameters for better performance.
