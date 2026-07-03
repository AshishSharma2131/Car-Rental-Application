
# Face Mask Detection using CNN

This project implements a Convolutional Neural Network (CNN) to classify images as either **With Mask** or **Without Mask**. The model is built using TensorFlow/Keras and trained on a face mask image dataset.

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- OpenCV
- Matplotlib
- Scikit-learn

## Dataset

The dataset contains two classes:

- With Mask
- Without Mask

Images are resized, normalized, and split into training and testing sets before training the model.

## Model

The CNN consists of convolution, max-pooling, flatten, and dense layers for binary image classification.

## Results

The notebook includes:
- Model training
- Accuracy and loss graphs
- Prediction on sample images

## Project Structure

```
Face-Mask-Detection/
│── code.ipynb
│── README.md
└── dataset/
    ├── with_mask/
    └── without_mask/
```

## How to Run

1. Install the required libraries.
2. Download the dataset.
3. Open `code.ipynb`.
4. Run all cells in order.

## Author

Developed as a deep learning project for face mask classification using CNN.
