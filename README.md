# Plant-disease-classification-using-Deep-Learning

## Overview
This repository contains the code for a plant disease classification project using machine learning. The project aims to classify plant diseases using various deep learning models. We have implemented 6 different models and compared their performance.

## Models Overview
| Model Name     | Description                                       | Performance                           | Model Weights Link                                    |
|----------------|---------------------------------------------------|---------------------------------------|--------------------------------------------------|
| VGG-19         | Deep convolutional neural network architecture.   | Acc=86.09, P=86.85, R=86.09, F1=85.83 | [Download Weights](https://shorturl.at/eyLZ2)    |
| EfficientNet   | Efficient convolutional neural network.           | Acc=93.15, P=93.85, R=93.15, F1=92.99 | [Download Weights](https://shorturl.at/eyLZ2)    |
| GoogLeNet      | CNN architecture with efficient inception modules.| Acc=93.99, P=94.31, R=93.99, F1=93.77 | [Download Weights](https://shorturl.at/eyLZ2)    |
| ResNet50       | Deep neural network with residual connections.    | Acc=94.75, P=94.84, R=94.75, F1=94.57 | [Download Weights](https://shorturl.at/eyLZ2)    |
| DenseNet       | CNN with dense connections between layers.        | Acc=93.0 , P=94.0 , R=93.0 , F1=93.5  | [Download Weights](https://shorturl.at/eyLZ2)    |
| ViT            | Transformer-based model for image classification. | Acc=88.86, P=90.08, R=88.75, F1=88.88 | [Download Weights](https://shorturl.at/eyLZ2)    |

## Usage
- Instructions on how to use the models.

### Running Environment:
- This project has been developed and tested using VS Code and Jupyter Notebook as the running environments.
- GPU acceleration is utilized for the complex computations, and CUDA availability is required for optimal performance.

### Common Dependencies:
- PyTorch
- torchvision
- scikit-learn
- matplotlib
- tqdm
- NumPy
- Scikit-learn (optional, used for data shuffling and splitting)

### Additional Dependencies by Model:
- **VGG-19**, **DeIT (Vision Transformer)**, **EfficientNet**, **GoogLeNet**, **ResNet-50**:
  - None additional.

- **DenseNet**:
  - TensorFlow
  - TensorFlow Addons
  - Pandas

- **ViT (Vision Transformer)**:
  - TensorFlow
  - OpenCV
  - TensorFlow Addons
  - Patchify

## Contributing
Contributions to the project are welcome. To contribute, please follow these guidelines:
- Fork the repository.
- Create a new branch for your feature or bug fix.
- Make your changes and test them thoroughly.
- Submit a pull request, explaining the changes you've made and their purpose.


## Contact
For inquiries or collaborations, please contact: 
- [Kumar Mridul](mailto:bt20ece060@students.vnit.ac.in)
- [Sarthak Atal](mailto:bt20ece088@students.vnit.ac.in).

