# Uncertainty-Aware EuroSAT Classification

Monte Carlo Dropout for epistemic uncertainty quantification in satellite imagery land-use classification.

## Overview

This project extends probabilistic deep learning techniques to geospatial Earth Observation data, demonstrating how epistemic uncertainty estimation improves trustworthiness in remote sensing AI systems.

## Dataset

- **EuroSAT**: 27,000 Sentinel-2 satellite images, 10 land-use classes
- 64×64 pixel resolution, 13 spectral bands (RGB used)

## Method

- CNN with Monte Carlo Dropout
- 50 stochastic forward passes for uncertainty estimation
- Epistemic uncertainty = variance across MC samples

## Results

- **Accuracy**: 78.2% (10 epochs)
- Uncertainty visualization identifies low-confidence predictions
- Higher uncertainty correlates with misclassifications and ambiguous regions

## Files

- `uncertainty_aware_eurosat_classification.ipynb` — Full training & inference pipeline
- `uncertainty_visualization.png` — Sample predictions with uncertainty scores
- `sample_results.json` — Quantitative uncertainty metrics

## Author

Rahul Sajith — Data Science researcher specializing in probabilistic ML and uncertainty estimation.
- LinkedIn: linkedin.com/in/rahulsajith2206
- Email: rahulsajith06@gmail.com
