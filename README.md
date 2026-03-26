# Experanto exporter


A Python library to export neurosicence experiments into [Experanto](https://github.com/sensorium-competition/experanto) format. Data exported will be interpolated by Experanto and later be used to train existing ML models.

# Progress
See progress of loading and processing BWM on colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/abdelrahman725/experanto-exporter/blob/main/bwm_playground.ipynb)

# Upcoming

Currently, this repo only supports [Brain Wide Map](https://www.nature.com/articles/s41586-025-09235-0) (BWM) dataset, but ultimately it will expand to support all big datasets for experanto (e.g., allen data, BWM).
So in the future, this repo is intended to replace [allen-exporter](https://github.com/sensorium-competition/allen-exporter).

**That's why the source code here is designed to be generic.**

# Data strucutre

## Original BWM
If you want to explore the original BWM before any processing done by this repository:
 - See the dataset strucutre from [International Brain Laboratory](https://docs.internationalbrainlab.org/notebooks_external/data_structure.html) docs.
 - Visit [International Brain Laboratory](https://viz.internationalbrainlab.org/app) and select a session to see helpful **visualization** for a session, trials, and clusters.

## Exported BWM
Upcoming ...