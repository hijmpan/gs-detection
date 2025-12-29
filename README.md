# gs-detection
Minimal Gulf Stream (GS) path detection code based on latitudinal SST gradients.

This repository supports the analysis in:
Pan, J. et al., *A Thermal Sea Surface Temperature Gradient–Based Approach to Gulf Stream Detection applied to CANARI Large-Ensemble Future Projections*,
submitted to Geophysical Research Letters.

## What is included
- `gs_detection.py`: core functions for smoothing SST gradients and detecting the GS path
- `run_example.py`: a minimal runnable example

## Description
The code detects the Gulf Stream path using SST latitudinal gradient and
produces the figures and diagnostics reported in the paper.

## Requirements

Python >= 3.9

Core dependencies:
- `numpy`
- `xarray`
- `scipy`

Optional (only needed if you want to visualize the synthetic example):
- `matplotlib`

Install (example):
```bash
pip install numpy xarray scipy matplotlib

## about
`jiamin.py
