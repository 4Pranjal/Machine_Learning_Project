# Unsupervised Learning Comparison README

## Overview

This repository contains Python code for comparing five different unsupervised learning techniques: Principal Component Analysis (PCA), t-distributed Neighbor Stochastic Embedding (t-SNE), k-means, Agglomerative Hierarchical Clustering (AHC), and Self-Organizing Maps (SOM). The objective is to apply these techniques to two datasets and analyze their performance in identifying underlying patterns.

## Objective

The objective of this project is to:

1. Apply unsupervised learning techniques to two datasets: a synthetic dataset and a dataset obtained from the internet.
2. Compare the performance of PCA, t-SNE, k-means, AHC, and SOM in visualizing and clustering the data.
3. Provide explanations of the implementation decisions and analysis in the report.

## Part 1: Selecting and Analyzing Datasets

The unsupervised learning techniques are applied to two datasets:

1. Synthetic dataset (A3-data.txt):
   - Features: 4 variables, 1 class
   - Patterns: 360 patterns

2. Dataset obtained from the internet:
   - Features: at least 6 variables, and a class attribute
   - Patterns: at least 200 patterns
   - Class attribute refers to at least 4 different classes

## Part 2: Comparing Unsupervised Learning Algorithms

The following unsupervised learning algorithms are compared:

- PCA
- t-SNE
- k-means
- AHC
- SOM

For each algorithm:

- PCA: Plot PCA projection in two dimensions and scree plot with accumulated variance.
- t-SNE: Plot t-SNE projection in two dimensions with different parameter settings.
- k-means: Use k-means for different values of k and compare obtained classes with real ones.
- AHC: Use UPGMA and complete linkage methods of AHC and plot resulting dendrograms.
- SOM: Visualize the data using SOM with different settings and plot component planes.

## Instructions

To implement the code, follow these steps:

1. Clone this repository:

   ```bash
   git clone <repository_url>
   ```

2. Install the required libraries:

   ```bash
   pip install numpy pandas scikit-learn matplotlib
   ```

3. Navigate to the directory:

   ```bash
   cd <repository_directory>
   ```

4. Run the Python scripts provided in the repository for applying unsupervised learning techniques and comparing results.

## Usage

The main Python scripts are as follows:

- `apply_unsupervised_learning.py`: This script applies unsupervised learning techniques to the datasets and compares the results.
  
- `visualize_results.py`: This script visualizes the results obtained from different unsupervised learning techniques.
  
 
## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributors

- [Pranjal Jain](https://github.com/4Pranjal)
