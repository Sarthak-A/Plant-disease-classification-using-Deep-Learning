# Plant Disease Classification Using Deep Learning

This repository contains the implementation of a deep learning-based approach for classifying plant diseases. We have classified 88 different plant diseases belonging to 23 species using a dataset of 79,806 images. The models were trained and evaluated using 6 different deep learning architectures to determine the best performing model for this task.

## Models used

The following deep learning models were used to classify the plant diseases:

DenseNet (Densely Connected Convolutional Networks)

EfficientNet (Efficient Neural Networks)

GoogLeNet (Inception v1)

ResNet50 (Residual Networks)

VGG19 (Visual Geometry Group Network)

ViT (Vision Transformers)



## Dataset

Dataset Link: https://www.kaggle.com/datasets/alinedobrovsky/plant-disease-classification-merged-dataset


## Demo Web App

A demo web application has been deployed on HuggingFace Spaces, allowing users to interact with the trained models and classify plant diseases from images.

HuggingFace Space Link: https://huggingface.co/spaces/SarthHF088/Plant-Disease-Classifier

## Model Comparison

Below is a comparison of the training and validation accuracy of the different models used in this project, and link to download model weights:

| Model name | Validation Accuracy | Precision | Model Weights
| --- | --- | --- | --- |
| VGG19 | 82.35% | 86.85 |  |
| EfficientNet | 88.96% | 93.85 |  |
| GoogLeNet | 92.49% | 94.31 |  |
| ResNet50 | 91.84% | 94.84 |  |
| DenseNet | 88.65% | 94.0 |  |
| ViT | 88.93% | 90.08 |  |

## Usage

1. Clone the repository: 
```
git clone https://github.com/Sarthak-A/Plant-disease-classification-using-Deep-Learning.git
```

2. Install the required dependencies:
```
pip install -r requirements.txt
```

3. Use the web-app on HuggingFace to classify disease from plant images





