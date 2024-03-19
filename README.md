# K-means Clustering on Breast Cancer Dataset

This project implements the K-means clustering algorithm from scratch using NumPy and applies it to the UCI ML Breast Cancer Wisconsin dataset. The features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass, describing characteristics of the cell nuclei present in the image.

## Description

The K-means function in this project takes an array containing a dataset and a value of κ (number of clusters) and returns the cluster centroids along with the cluster assignment for each data point. The algorithm is tested for values of κ varying between 2 and 7, and the distortion for each κ is plotted using matplotlib.

## Getting Started

### Dependencies

- Python 3.8+
- NumPy
- Matplotlib (for plotting distortion figures)

### Installing

- Clone the repository to your local machine.
- Ensure you have the dependencies installed.

### Executing program

- Load the dataset using `sklearn.datasets.load_breast_cancer`.
- Run the K-means algorithm by executing the main script: `python k_means.py`.
