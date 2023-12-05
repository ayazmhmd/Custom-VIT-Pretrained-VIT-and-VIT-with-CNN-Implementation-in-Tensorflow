# Custom VIT (Vision Transformer) Models in TensorFlow

This repository contains the implementation of three models for image classification: Custom VIT, Pretrained VIT, and VIT with CNN features. These models were built from scratch using TensorFlow in a Colab environment.

## Models Overview

1. **Custom VIT**
   - Implemented a custom Vision Transformer from scratch.
   - Architecture includes self-attention layers, positional embeddings, and MLP blocks.
   - Trained on a specific image dataset for image classification tasks.

2. **Pretrained VIT**
   - Used a pretrained Vision Transformer model from a TensorFlow/Keras library.
   - Fine-tuned the model on a custom dataset or task.

3. **VIT with CNN Features**
   - Explored the combination of Convolutional Neural Network (CNN) features with Vision Transformer.
   - Initial image features extracted using a CNN without changing the spatial dimension, followed by feeding into the Vision Transformer.

## Colab Notebooks

The project is organized into Colab notebooks for each model:

1. `Custom_VIT.ipynb`: Implementation and training of the custom Vision Transformer from scratch.

2. `Pretrained_transformer.ipynb`: Fine-tuning a pretrained Vision Transformer on a specific image classification task.

3. `VIT_with_CNN.ipynb`: Combining Convolutional Neural Network (CNN) features with Vision Transformer for improved performance.

## Usage

Each Colab notebook is self-contained and includes step-by-step instructions for:

- Importing necessary libraries and dependencies.
- Loading and preprocessing the image dataset.
- Building the respective model architecture.
- Training and evaluating the model
