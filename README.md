# BrainViT: Vision Transformer for Brain Tumor Classification

## Description
This project implements a Vision Transformer (ViT) model to classify brain tumors using grayscale MRI scans.
Classes include: glioma, meningioma, no tumor, and pituitary.

## Project Structure
- `train.py`: Main training and evaluation script.
- `data/`: Place your training and test images here in subfolders for each class.
- `results/`: Generated output visualizations like accuracy plots and confusion matrices.

## Usage
1. Add images to `data/train` and `data/test`, organized by class folders.
2. Run `python train.py` to train the model.

## Installation
```bash
pip install -r requirements.txt
```

## Output
- Training/validation accuracy and loss plots
- Confusion matrix and classification report
