# change-detection-remote-sensing
Bachelor's thesis: Fair controlled comparison of FC-EF, Siamese UNet, and BIT (CNN+Transformer) for binary change detection on LEVIR-CD dataset using PyTorch.

# Deep Learning-Based Change Detection in Remote Sensing Images

A fair controlled comparison study of three deep learning architectures 
for binary change detection in satellite imagery.

## Overview
This Bachelor's thesis implements and evaluates three change detection 
methods under identical training conditions to address reproducibility 
gaps in existing literature.

## Models Compared
- FC-EF (single-stream UNet baseline)
- FC-Siam-diff (Siamese UNet)
- BIT (CNN + Transformer hybrid)

## Dataset
- Primary: LEVIR-CD (637 image pairs, 0.5m GSD, building change detection)
- Secondary: WHU-CD / DSIFN-CD (cross-dataset validation)

## Evaluation Metrics
- Primary: F1-score, IoU
- Secondary: Precision, Recall

## Early Results
| Model | F1-Score |
|-------|----------|
| FC-EF (baseline) | 0.76 |
| FC-Siam-diff | In progress |
| BIT | In progress |

## Tech Stack
Python · PyTorch · scikit-learn · Pandas · Matplotlib

## Status
 Active development — thesis in progress (2025–2026)

## Supervisor
Bachelor's thesis supervised at GUC Cairo / GIU Berlin
