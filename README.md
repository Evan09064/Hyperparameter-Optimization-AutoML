# Hyperparameter Optimization AutoML Assignment 2 – Group 36

## About
This repository contains our work for Automated Machine Learning Project 2. We implement Sequential Model-Based Optimization (SMBO) to tune hyperparameters for scikit-learn models (SVM & AdaBoost) and explore meta-learning using MAML. The project includes our complete SMBO and MAML implementations, utilities for data loading and plotting, and a detailed project report.

## Repository Structure
- **dataloaders.py:**  
  Provides functions to load meta-learning datasets (e.g., Omniglot, MiniImagenet) and extract tasks.
- **main.py:**  
  The main script for running MAML training and evaluation.
- **maml.py:**  
  Contains the implementation of the MAML algorithm for meta-learning.
- **networks.py:**  
  Defines the network architectures used (e.g., the Conv4 model).
- **plots.py:**  
  Includes utilities for plotting experimental results.
- **requirements.txt:**  
  Lists all required Python packages and their versions.
- **Hyperparameter_Optimization_AutoML_Assignment_2_Evan_Meltz_Giulia_Rivetti.pdf:**  
  The full project report with methodology, experiments, and analysis.
- **README.md:**  
  This file, providing an overview of the project and instructions.

## How to Run
1. **Install Dependencies:**  
   Make sure you have Python 3.8+ installed. Then run:
   ```bash
   pip install -r requirements.txt
