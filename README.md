# Gaussian Mixture Model (GMM) using Expectation-Maximization (From Scratch)

## Overview
This work implements the Gaussian Mixture Model (GMM) algorithm from scratch using the Expectation-Maximization (EM) approach.  
It is focused on understanding how probabilistic clustering works through iterative parameter updates.

---

## Type of Work
Machine Learning Algorithm Implementation (Educational / Conceptual)

---

## What This Project Does
- Generates synthetic data from multiple Gaussian distributions
- Initializes random parameters (means, variances, mixing coefficients)
- Applies the EM algorithm:
  - Expectation step (E-step): computes responsibilities
  - Maximization step (M-step): updates parameters
- Iteratively learns the underlying distributions
- Visualizes the learning process step by step

---

## Key Concepts
- Gaussian Distribution
- Probability Density Function (PDF)
- Expectation-Maximization (EM) Algorithm
- Unsupervised Learning
- Parameter Estimation

---

## Workflow
1. Generate synthetic Gaussian data
2. Initialize random cluster parameters
3. Repeat for multiple iterations:
   - Compute responsibilities (E-step)
   - Update parameters (M-step)
4. Visualize intermediate and final distributions

---

## Visualization
- Original Gaussian distributions
- Random initialization of clusters
- Step-by-step convergence of learned distributions
- Final fitted model

---

## Libraries Used
- numpy
- matplotlib
- seaborn
- scipy

---

## Results
- The EM algorithm successfully converges
- Learned parameters approximate the original Gaussian distributions
- Demonstrates how unsupervised clustering works in practice

---

## Note
This is an algorithm-level implementation using synthetic data and is intended for educational purposes rather than real-world deployment.

---

## Author
Arwaa Mamdoh
