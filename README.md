# Plant Trait Prediction
This project is built to predict plant traits using images and tabular data.

## Overview
- Image Data: Plant images processed using a vision transformer (DINO-V2)
- Tabular Data: Metadata including environmental conditions 
The goal is to build a regression model that can accurately estimate plant traits based on multi-modal input data

## Requirements
To set up the environment to run the project. Make sure the following packages are installed.
Since this project involves using a vision transformer, running on a GPU is strongly recommended:
[CUDA Installation Guide (NVIDIA)](https://developer.nvidia.com/cuda-downloads)
```
!pip install torch torchvision pandas numpy scikit-learn xgboost Pillow
```
