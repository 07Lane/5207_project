# DSAI5207 Course Project

## CNN vs MLP for Low-Data Image Classification

This project compares Multi-Layer Perceptron (MLP) and Convolutional Neural Network (CNN) models on the Rock-Paper-Scissors image dataset under different training data sizes, with a focus on low-data regimes.

## Project Objective

To investigate how neural network architecture affects performance when labeled training data is limited.

We evaluate:
- Test Accuracy
- Macro-F1 Score
- Stability across repeated runs

## Dataset

Rock-Paper-Scissors dataset with 3 gesture classes:
- Rock
- Paper
- Scissors

Preprocessing:
- Images resized to 128 x 128
- Converted to tensors
- Loaded with PyTorch DataLoader

Low-data settings:
5%, 10%, 20%, 50%, 100%

## Repository Structure

DSAI5207-project/
- README.md
- requirements.txt
- notebooks/project_pipeline.ipynb
- figures/
- runs/
- report/

## Main File for Reproducibility

Use:
notebooks/project_pipeline.ipynb

Includes:
- preprocessing
- subset generation
- MLP baseline
- CNN model
- repeated experiments
- plotting
- error analysis

## How to Run

1. pip install -r requirements.txt
2. Open notebooks/project_pipeline.ipynb
3. Run all cells

## Main Findings

CNN consistently outperformed MLP across all data ratios with better accuracy, Macro-F1, and stability.

## Authors

DSAI5207 Group Project Team
