# EEG Signal Processing and Functional Connectivity Analysis

## Overview
This project explores EEG signal processing and functional connectivity analysis using Python. It was developed as part of an advanced computational neuroscience training course.

The project uses the MNE sample dataset and demonstrates EEG preprocessing, spectral analysis, connectivity estimation, and functional network visualization.

## Objectives
- EEG preprocessing and filtering
- Power Spectral Density (PSD) estimation using Welch and Multitaper methods
- Cross-Spectral Density (CSD) analysis
- Functional connectivity estimation using coherence, Phase Locking Value (PLV), and envelope correlation
- Comparison of connectivity measures
- Functional network visualization using NetworkX

## Methods
- **Preprocessing:** Notch filtering, band-pass filtering, and average referencing
- **Spectral Analysis:** Welch PSD, Multitaper PSD, and CSD
- **Functional Connectivity:** Welch coherence, Multitaper coherence, PLV, and envelope correlation
- **Network Analysis:** Threshold-based graph construction and visualization

## Tools
Python, MNE-Python, SciPy, NumPy, Matplotlib, MNE-Connectivity, NetworkX

## Dataset
MNE Sample Dataset (`sample_audvis_raw.fif`)

The dataset is accessed through the MNE-Python dataset interface.

## Repository Contents
- Jupyter Notebook containing the analysis workflow
- Figures illustrating spectral and connectivity results
- PDF report documenting the methodology and findings

## Disclaimer
This project is for educational and research-training purposes. Functional connectivity estimates do not necessarily represent direct anatomical connections or causal relationships.