# Deployment-Oriented Benchmarking of Deepfake Detection Architectures

This repository contains the implementation of the experiments reported in:

"Deployment-Oriented Benchmarking of Deepfake Detection Architectures: 
Performance, Generalization, and Resource-Efficiency Analysis"

## Overview

This project benchmarks eleven deepfake detection architectures:

### CNN-based models
- XceptionNet
- ResNet-50
- MesoNet
- InceptionV3
- EfficientNetV2-B0

### Transformer-based models
- ViT-16
- ViT-32
- Swin V2
- CrossViT
- MaxViT
- DINOv2

## Datasets

Experiments were conducted on:

- DeepFake Challenge (DFC)
- Celeb-DF (V2)
- FaceForensics++
- WildDeepfake

The datasets are not redistributed due to licensing restrictions.

## Repository Structure

- `CNN/` : CNN architecture implementations
- `Transformer/` : Transformer-based implementations
- `supplementary_material/` : Additional scripts and analysis files

## Requirements

Python >= 3.10

Required packages:

- TensorFlow
- PyTorch
- Transformers
- OpenCV
- scikit-learn
- pandas
- numpy

## Reproducibility

The repository provides preprocessing, training, evaluation, and resource profiling scripts used in the study.

## Citation

If you use this repository, please cite the corresponding paper.
