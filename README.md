# CIFAR-10 Image Classification

A comparative image-classification project using the CIFAR-10 dataset. The notebook explores three approaches: a decision tree baseline, a multi-layer perceptron implemented with NumPy, and a convolutional neural network built with TensorFlow/Keras.

## Highlights

- Explores class balance, pixel distributions, RGB statistics, and image complexity.
- Builds preprocessing pipelines tailored to tree-based, fully connected, and convolutional models.
- Implements forward propagation, backpropagation, mini-batch SGD, L2 regularisation, and early stopping for a custom MLP.
- Tunes model architecture and training hyperparameters.
- Evaluates models with accuracy, classification reports, and confusion matrices.

## Technology

- Python
- NumPy and pandas
- scikit-learn
- TensorFlow / Keras
- Matplotlib and seaborn

## Repository contents

- `cifar10_image_classification.ipynb` - analysis, modelling, tuning, and evaluation workflow.
- `requirements.txt` - Python dependencies.

The CIFAR-10 data files and generated model artefacts are intentionally excluded. Download CIFAR-10 from its official source or adapt the notebook's data-loading paths before running it.

## Results

The experiments compare a decision tree baseline with neural approaches. The custom MLP achieved 47.68% test accuracy, outperforming the decision tree baseline by 19.53 percentage points. The CNN provided the strongest representation for the spatial structure of CIFAR-10 images.

## Notes

This repository is a portfolio presentation of university coursework. Personal identifiers, assessment instructions, raw data, and generated model files have been excluded.
