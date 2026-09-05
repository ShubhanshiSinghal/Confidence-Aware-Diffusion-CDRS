# CAD-CDRS

Confidence-Aware Diffusion-Based Cross-Domain Recommendation System

## Overview

CAD-CDRS is a confidence-aware diffusion-based cross-domain
recommendation framework designed to mitigate negative knowledge
transfer between heterogeneous domains.

The framework estimates the reliability of cross-domain knowledge
using multiple confidence signals and employs confidence-aware
diffusion to preserve reliable information while suppressing noisy
transfer.

## Datasets

Source Domain:
- Goodreads Books

Target Domain:
- IMDB Movies

## Framework

The proposed framework consists of:

1. Data preprocessing
2. GloVe-based representation
3. Cross-domain embedding representation
4. Confidence estimation
5. Confidence-aware diffusion
6. Reverse denoising
7. Confidence-guided fusion
8. Top-K recommendation
9. Evaluation

## Requirements

See requirements.txt.

## Usage

Open:

CAD-CDRS-Goodreads-IMDB.ipynb

in Google Colab and execute the cells sequentially.

## Evaluation

The framework is evaluated using:

- HR@10
- NDCG@10

## Citation

Citation information will be added after publication.
