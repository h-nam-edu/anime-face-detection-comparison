# Anime Face Detection: A Comparative Study (Haar Cascades vs. HOG+SVM vs. YOLO)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/h-nam-edu/anime-face-detection/blob/main/notebooks/01_comparative_study.ipynb)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Abstract
This repository provides a fully reproducible comparative analysis of object detection methodologies applied to highly stylized anime faces. We systematically evaluate the accuracy and computational efficiency of traditional machine learning pipelines (Haar Cascades and HOG+SVM) against a modern single-pass deep learning architecture (YOLO11 Small). Empirical benchmarks demonstrate that YOLO fundamentally resolves the spatial rigidity and latency bottlenecks of sliding-window approaches, achieving 100% recall at real-time processing speeds.

## Directory Structure
* `notebooks/`: Contains the primary interactive computational pipeline.
* `docs/`: Contains the accompanying formal technical report.
* `data/`: Local directory for dynamically downloaded Kaggle and Hugging Face datasets.

## Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/h-nam-edu/anime-face-detection.git](https://github.com/h-nam-edu/anime-face-detection.git)
   cd anime-face-detection
