# White Blood Cell Classification

## Objective
Classify white blood cell images into lymphoblast vs normal categories for leukemia-related screening workflows.

## Method
- CNN baseline with data augmentation.
- Model refinement and comparative evaluation.
- Error analysis with class-level metrics.

## Repository Structure
- `notebooks/` training and evaluation notebooks.
- `src/` reusable code modules.
- `results/` metrics and plots.
- `assets/` README figures.
- `models/` saved models (optional).
- `data/` local dataset directory (not versioned).

## Data Access
Use local microscopy image data under `data/`.

## Run
1. Put dataset files under `data/`.
2. Run notebooks in `notebooks/`.
3. Save final metrics and figures to `results/`.

## Result Artifacts
- Confusion matrix
- Class-wise precision/recall/F1
- Representative error samples
