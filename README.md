# DFB Intensity Map

Python script to compute and visualize the log-normalized field intensity in a distributed-feedback (DFB) structure as a function of **wavelength** and **amplifying length**.

## Features
- Computes normalized intensity from a low-gain coupled-mode model.
- Sweeps wavelength (`λ = factor · λ₀`) and device length.
- Plots a log-scaled heatmap.
- Exports results to `dfb_intensity_map.csv`.

## Requirements
- Python 3.9+
- numpy, matplotlib, pandas, scipy

Install via:
```bash
pip install numpy matplotlib pandas scipy
