# Dynamic SVO-LSTM for Socially Adaptive AV Control

This repository contains the PyTorch implementation of **SociDriving**, a framework for socially compliant automated vehicle (AV) control in mixed traffic using dynamic Social Value Orientation (SVO).

## Overview
- Uses LSTM to predict acceleration based on surrounding vehicle states + dynamic SVO parameter φ(t)
- Incorporates enhanced loss terms: prediction, utility (SVO-weighted), smoothness, and trend consistency
- Trained and evaluated on the **Arizona Ring Experiments Dataset (ARED)**
- Features dynamic φ(t) computation based on front/rear danger levels

## Key Features
- Dynamic SVO calculation using spacing danger metrics
- Enhanced feature engineering for car-following prediction
- IDM-based verification and multi-vehicle simulation
- Training with adaptive loss weights and trend regularization

## Requirements
- Python 3.8+
- PyTorch 1.10+
- pandas, numpy, matplotlib, openpyxl

pip install torch pandas numpy matplotlib openpyxl
