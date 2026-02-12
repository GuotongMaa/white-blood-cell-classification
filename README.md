# White Blood Cell Classification

CNN-based classification of lymphoblasts vs normal white blood cells from microscopy images.

## Problem
Support leukemia screening by classifying white blood cell images into lymphoblast vs normal.

## Approach
Train CNN baselines with augmentation and evaluate model variants for improved generalization.

## Highlights
- Baseline CNN and augmentation strategy
- Model refinements and comparative evaluation
- Error analysis and class-wise performance inspection

## Data
Microscopy image dataset (zip). Place under `data/` and unzip.

## Project Structure
- notebooks/ - Main workflow notebooks
- data/ - Datasets (as noted above)
- models/ - Model checkpoints (optional)
- results/ - Metrics, plots, and outputs
- assets/ - Figures for README

## How to Run
- Unzip dataset into `data/`
- Run `notebooks/wbc_classification_part1.ipynb` then Part 2

## Status
Ready for rerun; metrics can be recomputed from notebooks.

## Git LFS
This repo contains large files. Track `*.pth`, `*.pt`, `*.zip` with Git LFS.

## Results Showcase
- Recommended outputs in `results/`: confusion matrix, class-wise precision/recall/F1, and representative error cases.
- Add final figures to `assets/` and link them in this section after reruns.
