# Basil / Coriander Leaf Classifier (CNN + ResNet50)

## Overview
This project builds an image classification model to distinguish between basil and coriander leaves using a Convolutional Neural Network with transfer learning based on ResNet50. The model is implemented in PyTorch.

The system predicts one of three classes:
- Basil
- Coriander
- Unrecognized

## Dataset
The dataset is compiled from multiple sources:
- Kaggle
- Roboflow
- Google images
- Personally captured photos

Images were cleaned, labeled, and augmented before training.

Dataset Link:
```
https://www.kaggle.com/datasets/duhnesslove/basil-coriander-dataset

## Model
- Architecture: ResNet50 (pretrained backbone)
- Framework: PyTorch
- Transfer learning with modified final fully connected layer (3 outputs)
- Data augmentation applied during training

## Notebook
All preprocessing, training, evaluation, and testing code is contained in:

```
model_resnet50.ipynb
```

Run the notebook cells sequentially to reproduce results.

## Notes
This project demonstrates how transfer learning can be applied to small custom plant datasets for practical image classification tasks.
