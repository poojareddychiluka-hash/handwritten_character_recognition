# Handwritten Character Recognition using CNN

## Project Overview

This project uses a Convolutional Neural Network (CNN) to recognize handwritten digits from images. The model is trained using the MNIST dataset and classifies handwritten digits from 0 to 9.

## Objective

The main objective of this project is to identify handwritten digits using image processing and deep learning techniques.

## Dataset

The project uses the MNIST handwritten digit dataset.

* Training images: 60,000
* Testing images: 10,000
* Image size: 28 × 28 pixels
* Classes: 0–9

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

## Model

A Convolutional Neural Network (CNN) is used for classification. The model contains:

* Convolutional layers
* Max Pooling layers
* Flatten layer
* Dense layer
* Dropout layer
* Softmax output layer

## Preprocessing

The images are normalized by converting pixel values from 0–255 to a range of 0–1. The images are then reshaped into the format required by the CNN.

## Evaluation

The model is evaluated using:

* Test accuracy
* Training and validation accuracy
* Training and validation loss
* Confusion matrix
* Sample predictions

## Project Files

```text
handwritten-character-recognition/
│
├── handwritten_character_recognition.ipynb
├── handwritten_character_cnn.keras
├── requirements.txt
└── README.md
```

## Future Scope

The project can be extended to recognize handwritten alphabets using the EMNIST dataset. It can also be extended to recognize complete words or sentences using sequence models such as CRNN, RNN, or LSTM.

## Conclusion

This project demonstrates how CNNs can be used to recognize handwritten digits. The model learns important visual patterns from handwritten images and classifies them into digits from 0 to 9.
