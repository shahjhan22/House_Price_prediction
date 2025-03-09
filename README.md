# House Price Prediction with Embeddings

## Overview

This project explores the use of embeddings for categorical features in a Kaggle dataset. The goal was to implement a feature processing pipeline using PyTorch and train an Artificial Neural Network (ANN) for house price prediction.

## Dataset

We used a dataset from a Kaggle competition that includes various categorical and continuous features. The dataset was relatively small, which posed challenges in model performance.

## Methodology

### 1. Feature Processing

- **Categorical Features**: Converted using a label encoder and then passed through embeddings.
- **Continuous Features**: Processed using batch normalization to standardize values.

### 2. Data Splitting

The dataset was divided into training and testing sets after preprocessing.

### 3. Model Architecture

- Designed an ANN using PyTorch with embedding layers for categorical features.
- Continuous features were fed through batch normalization.
- Fully connected layers were added to process the concatenated features.

### 4. Training

- The model was trained using PyTorch with a suitable loss function and optimizer.
- Due to computational limitations, training epochs were limited, affecting model performance.

## Challenges Faced

- **High Loss**: Likely due to limited training epochs and dataset size.
- **Computational Constraints**: Large computations were difficult to handle on the available hardware.


