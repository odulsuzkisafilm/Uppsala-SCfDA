# Scientific Computing for Data Analysis - Mini Projects

This repository contains my solutions for the mini-projects of the course **Scientific Computing for Data Analysis** that I have taken in Uppsala University. The projects focus on exploring different computational methods for analyzing scientific data, with a strong emphasis on reproducibility and performance evaluation.

## Project 1: Exploring the Reproducibility of Circadian Clock Models in Systems Biology

### Overview
This project explores the reproducibility of circadian clock models, specifically focusing on the genetic mechanisms that drive biological clocks in organisms. The study involves replicating and analyzing the results of a key research article that models these clocks using both deterministic and stochastic approaches.

### Key Features
- **Models Implemented**:
  - **Ordinary Differential Equations (ODEs)**: To simulate the continuous, deterministic behavior of the circadian oscillator.
  - **Stochastic Simulation Algorithm (SSA)**: Using the Gillespie algorithm to model the random fluctuations inherent in biological systems.

- **Parameter Sensitivity Analysis**:
  - Investigated how changes in reaction rates and other model parameters affect the stability and behavior of the circadian oscillator.

- **Reproduction of Key Figures**:
  - Successfully reproduced figures from the reference article, demonstrating the oscillatory dynamics of activator and repressor proteins under different modeling approaches.

- **Implementation**:
  - The models were implemented using Python, with the `gillespy2` library used for simulation and `matplotlib` for visualization.
  - Simulations reproduce key results from the reference article, providing insights into the oscillatory behaviors of activator and repressor proteins.


## Project 2: Digit Classification Using the Singular Value Decomposition Approach

### Overview
This project focuses on the classification of handwritten digits using a basis vector approach derived from Singular Value Decomposition (SVD). The goal is to develop an efficient algorithm that accurately classifies digits by leveraging the most significant components of the digit images.

### Key Features
- **Data Preprocessing**:
  - Handwritten digit images are flattened and prepared for SVD.

- **Singular Value Decomposition (SVD)**:
  - SVD is applied to the training data to extract basis vectors, which are then used for classification.

- **Residual Calculation**:
  - Classification is based on the residuals computed for each digit, with the smallest residual indicating the predicted digit.

- **Performance Evaluation**:
  - The algorithm's accuracy is evaluated across different numbers of basis vectors, providing insights into the trade-off between computational complexity and classification performance.

- **Cross-Digit Analysis**:
  - Investigated similarities between digits (e.g., 3 and 8) based on their singular values, leading to a deeper understanding of digit classification challenges.
