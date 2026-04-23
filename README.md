# Comparative Analysis of Kalman Filter Variants for Orbital State Estimation

Course project for Digital Signals and Images Processing (DSIP).

## Overview
This repository contains a study of orbital state estimation in a 3D simulation scenario. The analysis is based on noisy observations and focuses on Kalman filter-based estimation.

## Objective
The primary objective is to examine the tradeoff between estimation accuracy and uncertainty in Kalman filtering.

The project compares multiple Kalman filter variants to evaluate how each model balances:
- numerical estimation error;
- uncertainty representation through covariance/confidence behavior.

## Methodological Scope
- Simulation of orbital motion and noisy measurements.
- State estimation and trajectory reconstruction.
- Comparative assessment of filter variants using quantitative error indicators and uncertainty-related measures.
- Visual inspection through 3D plots and animation outputs.

## Repository Structure
- REAL_WORLD_SIMULATION.ipynb: simulation workflow and data generation/handling.
- FINAL_PPRESENTATION.ipynb: estimation analysis, metric computation, and visualization.
- orbiting.csv: baseline trajectory data.
- orbiting_noisy.csv: noisy observation data.
- results_2.csv, results_n.csv: exported experimental results.
- imgs/: generated image frames for visual outputs.
- *.mp4: generated animation files.

## Software Requirements
Install the following Python packages:
- numpy
- matplotlib
- plotly
- scipy
- opencv-python
- perlin-noise
- jupyter

Example installation command:
pip install numpy matplotlib plotly scipy opencv-python perlin-noise jupyter

## Execution
1. Open REAL_WORLD_SIMULATION.ipynb and run all cells in order.
2. Open FINAL_PPRESENTATION.ipynb and run all cells in order.
3. Review generated CSV, image, and video outputs for comparison results.

## Expected Outputs
- Predicted vs reference trajectory visualizations.
- Quantitative comparison of Kalman filter variants.
- Error and uncertainty-oriented evaluation artifacts.